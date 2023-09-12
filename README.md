<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- PROJECT LOGO -->
<br />
<div align="center">

  <a href="https://www.mpiwg-berlin.mpg.de/research/research-IT">
    <img src="misc/images/mpiwglogo.png" alt="MPIWG-ResearchIT">
  </a>

  <h3 align="center">MPIWG Research-IT Machine Learning Projects</h3>

  <!-- <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p> -->
</div>



<!-- TABLE OF CONTENTS -->
<!-- <details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details> -->



<!-- ABOUT THE PROJECT -->

## About

This page is dedicated to the collection of the Machine Learning papers, repos, and datasets created and curated by the Research IT Group at the Max Planck Institute for the History of Science in Berlin. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Humanities ML Datasets

### Sacrobosco Visual Elements Dataset (S-VED)
The SVED dataset is a large object detection dataset produced by the [Sphere Project](https://sphaera.mpiwg-berlin.mpg.de/). The dataset contains images and labelled bounding boxes covering four different classes: "Content Illustrations", "Initials", "Decorations", and "Printer's Marks". This dataset is associated with XXX insert paper XXX and a service XXX insert hyperlink to service XXX. 


## Presentations & publications
### [CorDeep and the Sacrobosco Dataset: Detection of Visual Elements in Historical Documents](https://doi.org/10.3390/jimaging8100285)
#### Authors
Jochen Büttner, Julius Martinetz, Hassan El-Hajj, Matteo Valleriani
#### Abstract
Recent advances in object detection facilitated by deep learning have led to numerous solutions in a myriad of fields ranging from medical diagnosis to autonomous driving. However, historical research is yet to reap the benefits of such advances. This is generally due to the low number of large, coherent, and annotated datasets of historical documents, as well as the overwhelming focus on Optical Character Recognition to support the analysis of historical documents. In this paper, we highlight the importance of visual elements, in particular illustrations in historical documents, and offer a public multi-class historical visual element dataset based on the Sphaera corpus. Additionally, we train an image extraction model based on YOLO architecture and publish it through a publicly available web-service to detect and extract multi-class images from historical documents in an effort to bridge the gap between traditional and computational approaches in historical studies.
#### Cite

```
@article{Buttner2022,
author = {Jochen Büttner and Julius Martinetz and Hassan El-Hajj and Matteo Valleriani},
year = {2022},
journal = {Journal of Imaging},
volume = {8},
number = {285},
title = {CorDeep and the Sacrobosco Dataset: Detection of Visual Elements in Historical Documents},
doi = {10.3390/jimaging8100285}
}
```

### [An Ever-Expanding Humanities Knowledge Graph: The Sphaera Corpus at the Intersection of Humanities, Data Management, and Machine Learning](https://link.springer.com/article/10.1007/s13222-022-00414-1)

#### Authors
Hassan El-Hajj, Maryam Zamani, Jochen Büttner, Julius Martinetz, Oliver Eberle, Noga Shlomi, Anna Siebold, Grégoire Montavon, Klaus-Robert Müller, Holger Kantz & Matteo Valleriani 

#### Abstract
The Sphere project stands at the intersection of the humanities and information sciences. The project aims to better understand the evolution of knowledge in the early modern period by studying a collection of 359 textbook editions published between 1472 and 1650 which were used to teach geocentric cosmology and astronomy at European universities. The relatively large size of the corpus at hand presents a challenge for traditional historical approaches, but provides a great opportunity to explore such a large collection of historical data using computational approaches. In this paper, we present a review of the different computational approaches, used in this project over the period of the last three years, that led to a better understanding of the dynamics of knowledge transfer and transformation in the early modern period.

#### Cite
```
@article{ElHajj2022,
author = {El-Hajj, Hassan and Zamani, Maryam and Büttner, Jochen and Martinetz, Julius and Eberle, Oliver and Shlomi, Noga and Siebold, Anna and Montavon, Grégoire and Müller, Klaus-Robert and Kantz, Holger and Valleriani, Matteo},
title = {An Ever-Expanding Humanities Knowledge Graph: The Sphaera Corpus at the Intersection of Humanities, Data Management, and Machine Learning},
journal = {Datenbank-Spektrum: Zeitschrift für Datenbanktechnologien und Information Retrieval},
DOI = {10.1007/s13222-022-00414-1},
year = {2022},
type = {Journal Article}
}
```

### [Prompt me a Dataset: An investigation of text-image prompting for historical image dataset creation using foundation models](https://arxiv.org/abs/2309.01674)

#### Author
Hassan El-Hajj and Matteo Valleriani

#### Abstract
In this paper, we present a pipeline for image extraction from historical documents using foundation models, and evaluate text-image prompts and their effectiveness on humanities datasets of varying levels of complexity. The motivation for this approach stems from the high interest of historians in visual elements printed alongside historical texts on the one hand, and from the relative lack of well-annotated datasets within the humanities when compared to other domains. We propose a sequential approach that relies on GroundDINO and Meta's Segment-Anything-Model (SAM) to retrieve a significant portion of visual data from historical documents that can then be used for downstream development tasks and dataset creation, as well as evaluate the effect of different linguistic prompts on the resulting detections.

#### Cite
```
@misc{elhajj2023prompt,
title={Prompt me a Dataset: An investigation of text-image prompting for historical image dataset creation using foundation models}, 
author={Hassan El-Hajj and Matteo Valleriani},
year={2023},
eprint={2309.01674},
archivePrefix={arXiv},
primaryClass={cs.CV}
}
```


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Code Repositories
### Sacrobosco Visual Elements Dataset (S-VED) Model Weights 
The code and trained weights to run the S-VED YOLOv5 model can be found [here](https://gitlab.gwdg.de/MPIWG/Department-I/sphaera/s-ved-object-detection)

### Prompt me a dataset pipeline code
The code to use the prompt me a dataset can be found [here](https://github.com/hassanhajj910/prompt-me-a-dataset). Information on how to run it is in the repo's readme


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Tools
### CorDeep
In order to bridge the gap between humanists and computer scientists. A simple webpage was created where reseachers can upload their text scans in multiple formats and get back the detected regions. You can access the [CorDeep service here](https://cordeep.mpiwg-berlin.mpg.de/)



<!-- <p align="right">(<a href="#readme-top">back to top</a>)</p> -->

<!-- ## Notebooks -->

<!-- LICENSE -->

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


