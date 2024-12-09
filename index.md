---
title: MulTiSA 2025
feature_text: | 
  ## MulTiSA 2025
  ##### 2nd Workshop on Multivariate Time Series Analytics 
  in conjunction with ICDE'25 | 19th May 2025, Hong Kong, China.
feature_image: "/assets/banners/banner.png"
excerpt: ""
---

<style>
  .profile-card {
    display: flex;
    width: 100%;  /* Adjust width as needed */
    margin: 10px;
    /* border: 1px solid #ddd; */
    /* border-radius: 5px; */
  }
  .profile-card img {
    width: 150px;  /* Set image width */
    height: 200px; /* Set image height */
  }
  .profile-info {
    padding: 10px;
  }
  .profile-info h3, .profile-info p {
    margin: 5px 0;
  }
  /* Styles for the "go to top" link */
  .go-to-top {
    text-align: right;  /* Align text to the right */
  }
</style>

## About
Contemporary algorithms for time series management predominantly handle univariate time series. Modern data sources frequently generate richer, multivariate time series. Examples include sensors monitoring multiple variables (e.g., temperature, wind, rainfall), financial time series (bid/ask prices, volume), and data from scientific and medical equipment. Currently, only very few algorithms address the management, analysis, and extraction of insights from such multivariate data. Moreover, existing work is tailored to specific needs. Foundational functionalities that have propelled advancements in univariate time series analysis, e.g., indexing, cannot be trivially extended to the multivariate case. This limitation significantly restricts existing efforts for analyzing multivariate time series. 

This workshop will bring together researchers and practitioners working with multivariate time series, to present and discuss open problems and solutions, and to foster collaborations. Industry will participate for presenting requirements and current approaches, and to reach out to the ICDE community. Researchers will share their novel and ongoing work. The full-day workshop will feature:
(a) 10 paper presentations (short papers and demos up to 6 pages, long papers up to 12 pages),
(b) two invited talks from industry and domain experts, 
(c) panel discussion, and time for fostering collaborations. 

The accepted papers will be included in the ICDEW proceedings.

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>
---

## Topics of interest
The topics of interest include (but are not limited to):
- Open challenges in multivariate time series management
- Similarity search on multivariate time series, and detection of multivariate correlations and similarity measures
- Online analytical processing for multivariate time series 
- Streaming and/or distributed analytics on multivariate time series
- Storing, indexing, and querying multivariate time series
- Sketching and summarizing multivariate time series
- Data preparation (data cleaning, noise removal, handling missing values) on multivariate time series
- Forecasting and anomaly detection for multivariate time series
- Machine learning and deep learning techniques for multivariate time series
- Interactive visualization and analytics on (streaming) multivariate time series
- Handling uncertainty
- Privacy-preserving analytics on multivariate data
- Requirements, applications, and query languages for multivariate time series analytics
- Foundation models for multivariate time series

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>
---

## Submission Guidelines
The workshop will accept regular papers (up to 8 pages, excluding references) and short papers describing work in progress, demos, vision/outrageous ideas (up to 4 pages, excluding references). All submissions must be prepared in accordance with the IEEE template available [here](https://www.ieee.org/conferences/publishing/templates.html). The workshop follows the same rules of Conflicts of Interest (COI) as ICDE 2025. The following are the page limits (excluding references):

| **Regular papers:** | 8 pages |
| **Short papers:** | 4 pages |

All submissions (in PDF format) should be submitted to [Microsoft CMT](https://cmt3.research.microsoft.com/MULTISA2025/).

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>
---

## Important Dates
All deadlines are 11:59PM AoE.

| **Submission deadline:** | February 2, 2025 |
| **Notifications:** | March 6, 2025 |
| **Camera-ready deadline:** | March 25, 2025 |
| **Workshop date:** | May 19, 2025 |

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>
---

## Program
To be announced.

<!-- **9:00 Welcome Message** 

**9:05 - 10:00 Keynote Talk 1:** [Multivariate Time-Series in Airbus](#keynote-1-multivariate-time-series-in-airbus) \
  Ammar Mechouche (Airbus Helicopters), Adil Soubki (Airbus Commercial)

**10:00 - 10:30 Coffee Break**

**10:30 - 12:00 Research Session 1**
- [Parameter-free Streaming Distance-based Outlier Detection](#program) (10 min) \
    Apostolos Giannoulidis (Aristotle University of Thessaloniki)*; Nikodimos Nikolaidis (Atlantis Engineering); Anastasios Gounaris (Aristotle University of Thessaloniki)
- [Data-Hungry Fault Detection Algorithms Can Try Transfer Learning for Starters](#program) (10 min) \
    Jurgen van den Hoogen (Osnabrück University)*; Dan Hudson (Osnabrück University); Martin Atzmueller (Osnabrück University & DFKI)
- [Exploiting Individual Graph Structures to Enhance Ecological Momentary Assessment (EMA) Forecasting](#program) (15 min) \
    Mandani Ntekouli (Maastricht University)*; Gerasimos Spanakis (Maastricht University); Lourens Waldorp (University of Amsterdam); Anne Roefs (Maastricht University)
- [MultiCast: Zero-Shot Multidimensional Time Series Forecasting Using LLMs](#program) (15 min) \
    Georgios Chatzigeorgakidis (Athena Research Center)*; Konstantinos Lentzos (Athena Research Center); Dimitrios Skoutas (Athena Research Center)
- [Subset Models for Multivariate Time Series Forecast](#program) (10 min) \
    Raphael F Saldanha (Inria)*; Victor Ribeiro (LNCC); Eduardo Pena (UTFPR); Marcel Pedroso (Fiocruz); Reza Akbarinia (INRIA); Patrick Valduriez (INRIA); Fabio Porto (LNCC)
- [Challenges in Modeling Drug Shortage Events in the Pharmaceutical Domain](#program) (10 min) \
    Laura-Maria Tolosi-Halacheva (Teva Pharmaceuticals)*; Eran Nevo (Teva Pharmaceuticals); Radoslav Andreev (Teva Pharmaceuticals); Oleg Shcherbakov (Teva Pharmaceuticals)
- [Time Series Problems in the Energy Sector](#program) (10 min) \
    Christos Dalamagkas (Public Power Corporation); Angelos Georgakis (Public Power Corporation); Kostas Hrissagis-Chrysagis (Public Power Corporation); George Papadakis (University of Athens)* 

**12:00 - 13:30 Lunch Break**

**13:30 - 15:00 Research Session 2**
- [Data Augmentation for Multivariate Time Series Classification: An Experimental Study](#program) (15 min) \
    Romain Ilbert (Huawei Paris Research Center)*; Thai V. Hoang (TH Consulting); Zonghua Zhang (CRSC)
- [Extended Framework and Evaluation for Multivariate Streaming Anomaly Detection with Machine Learning](#program) (15 min) \
    Andreas Koch (Technical University of Munich)*; Michael Petry (Airbus Defence and Space / Technical University of Munich); Martin Werner (TU München)
- [Anomaly Detectors for Multivariate Time Series: The Proof of the Pudding is in the Eating](#program) (10 min) \
    Phillip Wenig (Hasso Plattner Institute, University of Potsdam)*; Sebastian Schmidl (Hasso Plattner Institute, University of Potsdam); Thorsten Papenbrock (Philipps University of Marburg)
- [Linear-trend normalization for multivariate subsequence similarity search](#program) (15 min) \
    Thibaut Germain (ENS Paris Saclay)*; Charles Truong (ENS Paris Saclay); Laurent Oudre (ENS Paris Saclay)
- [Beyond the Dimensions: A Structured Evaluation of Multivariate Time Series Distance Measures](#program) (10 min) \
    Jens d'Hondt (Eindhoven University of Technology)*; Odysseas Papapetrou (TU Eindhoven); John Paparrizos (The Ohio State University)
- [Towards Ptolemaic metric properties of the z-normalized Euclidean distance for multivariate time series indexing](#program) (10 min) \
    Max Pernklau (FernUniversität in Hagen)*; Christian Beecks (FernUniversität in Hagen)
  
**15:00 - 15:30 Coffee Break**

**15:30 - 16:30 Keynote Talk 2:** [Multivariate time series in healthcare: challenges and open questions](#keynote-2-multivariate-time-series-in-healthcare-challenges-and-open-questions) \
  Laurent Oudre, Centre Borelli, ENS Paris Saclay 

**16:30 - 17:30 Panel Discussion**\
Panelists: Ammar Mechouche, Adil Soubki, Laurent Oudre, and John Paparrizos -->

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>
---

## Panelists
To be announced.

<!-- <div class="profile-card">
<img src="https://github.com/multisa2025/multisa2025.icde/assets/45044727/48954c29-aaa8-46d8-ada3-75bdfeb04808" alt="Ammar">
<div class="profile-info">
    <h4>Ammar Mechouche</h4>
    <p>Airbus Helicopters</p>
</div>
</div>

**Bio:** Ammar Mechouche is a Big Data & Advanced Analytics expert at Airbus Helicopters (AH). He joined Airbus in 2013 as a research engineer. He first developed a big data solution which enables the processing of the big amounts of time series data collected from helicopters flying worldwide. He has been since contributing to the development of the helicopter data analytics topic in order to generate business value for AH and its customers.
Previously, Ammar has been awarded a Ph.D. from the University of Rennes 1 in 2009. He worked on the development of an ontology-based system for brain MRI image annotation. Before joining Airbus, he has been working as 1) post-doc on data integration at the research department of the French Mapping Agency (IGN); 2) research assistant at the LIS Lab of Aix-Marseille University; and 3) software engineer at Thales. Ammar is co-author of more than 20 papers published in peer reviewed conferences / journals; mainly in the computer science / helicopter domains.

<div class="profile-card">
<img src="https://github.com/multisa2025/multisa2025.icde/assets/45044727/7d2c062f-3157-4b2a-b60c-897abafb6500" alt="Adil">
<div class="profile-info">
    <h4>Adil Soubki</h4>
    <p>Airbus Commercial</p>
</div>
</div>

**Bio:** Adil Soubki is a Time Series analytics expert at Airbus Commercial (AIC). He joined Airbus in 2009 as a software engineer, and now, he is working as a Data scientist / Data architect for a time series solution hosting data collected from test & development aircrafts. He contributes to enhancing the usage of IA and data analytics within the test center activity. Graduated from INSA Toulouse in automatic and computer science in 2004, Adil started working as a software engineer at NEXEYA developing test benches.

<div class="profile-card">
<img src="https://github.com/multisa2025/multisa2025.icde/assets/45044727/4b41cc63-0a4f-4307-9952-8240c2ac04da" alt="Laurent">
<div class="profile-info">
    <h4>Laurent Oudre</h4>
    <p>Centre Borelli, ENS Paris Saclay</p>
</div>
</div>

**Bio:** Laurent Oudre is a full professor at the Centre Borelli of the Ecole Normale Supérieure Paris-Saclay (France). He leads a team of more than ten young researchers and has been working for about fifteen years on signal processing, pattern recognition and machine learning for time series. His work covers a wide range of topics: event detection (including change-point, pattern and anomaly detection), feature extraction, unsupervised or semi-supervised approaches, representation learning and graph signal processing. His scientific projects are mainly focused on AI applications in health and industry, often with a strong interdisciplinary component. He is also involved in initiatives around reproducible research and acculturation to AI (especially for the medical community). He is the author of more than 70 patents and articles in international peer-reviewed journals and conferences. He is also the director of the MVA (Mathematics, Vision and Learning) master's degree at the ENS Paris-Saclay, considered one of the best master's degrees in AI in Europe.

<div class="profile-card">
<img src="https://github.com/multisa2025/multisa2025.icde/assets/45044727/72ea28ce-4e77-4d55-aca3-75dccba1cf33" alt="John">
<div class="profile-info">
    <h4>John Paparrizos</h4>
    <p>The Ohio State University</p>
</div>
</div>

**Bio:** [Cirriculum Vitae](https://www.paparrizos.org/cv/PaparrizosCV.pdf) -->

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>

---

## Keynote Talks
To be announced.

<!-- ##### Keynote 1: Multivariate Time-Series in Airbus 
*Ammar Mechouche, Airbus Helicopters; Adil Soubki, Airbus Commercial*

**Abstract:** This presentation is about Airbus time series coming from testing aircrafts and operating helicopters. First, the collection and management of these data are briefly described. Then, it is shown how these time series data are organized and stored in order for their processing to be performant. After that, some Airbus made tools, dedicated to time series analysis, are presented. Finally, a focus is made on problems / challenges emerging from the analysis of these multivariate data series, encountered in the framework of predictive maintenance and automatic events detection in testing data.

##### Keynote 2: Multivariate time series in healthcare: challenges and open questions 
*Laurent Oudre, Centre Borelli, ENS Paris Saclay*

**Abstract:** Most sensors currently used in healthcare (EEG, 3D motion analysis, accelerometry, ECG...) produce multivariate time series. The different dimensions of these time series are often highly correlated and structured, and prior knowledge of the structure can help to improve the way these signals are handled and processed. In this talk we will discuss some strategies to exploit this additional information for various tasks such as change point detection or filtering, with applications to gait analysis and EEG data. The talk will also provide an introductory overview of the promising framework of Graph Signal Processing (GSP), along with a discussion of the main remaining challenges and open questions in this area.

[Link to Slides](https://github.com/multisa2025/multisa2025.icde/files/15389208/PlenaryICDE2025_LOudre.pdf) -->

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>
---

## Organizers
- Themis Palpanas, Universite Paris Cit&eacute;
- Odysseas Papapetrou, Eindhoven University of Technology
- Dimitris Skoutas, Athena Research Center
- Peng Wang, Fudan University

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>
---

## Program Committee
To be announced.

<!-- - Paul Boniol, Postdoctoral researcher at Ecole Normale Supérieure (ENS) Paris Saclay, France
- Jessica Lin, Associate professor at George Mason University, USA 
- Abdullah Mueen, Associate professor at University of New Mexico, USA
- Patrick Schäfer, Postdoctoral researcher at the Humboldt University of Berlin
- Saurabh Agrawal, Senior Machine Learning Engineer at Tubi, San Francisco, USA
- Germain Forestier, Professor at University of Haute-Alsace, IRIMAS, France
- Peng Wang, Professor at Fudan University, China
- Shen Liang, Postdoctoral researcher at Université Paris Cité, France
- Anthony Bagnall, Professor at University of Southampton, UK
- Søren Kejser Jensen, Postdoctoral researcher at Aalborg University, Denmark
- Michele Linardi, Assistant professor at ETIS lab, France
- Karine Zeitouni, Professor at Université Paris-Saclay, France
- John Paparrizos, Assistant Professor at Ohio State University, USA
- Thorsten Papenbrock, Professor at Philipps-Universität Marburg, Germany
- Qitong	Wang, Université Paris Cité
- Tristan	Allard,	Associate professor at	Univ Rennes, CNRS, IRISA
- Johann Gamper, Professor at	Free University of Bozen-Bolzano
- Rodica	Neamtu, Professor at	Worcester Polytechnic Institute
- Georgios	Chatzigeorgakidis, Postdoctoral researcher at Athena Research Center
- Giorgos	Giannopoulos, Postdoctoral researcher at Athena Research Center -->

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>
---

## Web and publicity chair
- Jens d'Hondt, Eindhoven University of Technology

<!-- Back to top button -->
<div class="go-to-top">
    <a href="#">[ Go to Top ]</a>
</div>
