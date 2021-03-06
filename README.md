
# Identifying and mitigating bias in deep learning for biomedical data through open science practices

## Project Objectives 

1. To investigate how open science can mitigate bias in biomedical datasets; raising awareness about racial inequalities in biomedical sciences.

2. to raise awareness about (a) racial inequalities in the biomedical and AI fields; (b) the negative consequences of the lack of diversity in biomedical data (c) ways to render biomedical data sharing more equitable through the open movement.


## Project Summary 

Artificial intelligence (AI) has an astonishing potential to assist clinical decision-making and revolutionize global health. However, the use of AI in the biomedical field needs to ensure that it can be accessed by everyone, taking into account the needs of diverse populations. Most AI algorithms need large datasets to learn from, but vulnerable groups have a long history of being absent or misrepresented in existing datasets. If the training data is misrepresentative of the population variability, AI is prone to reinforcing inequality and bias, which can lead to dangerous outcomes and misdiagnoses.

In one of many examples, AI algorithms used health costs as a proxy for health needs and falsely concluded that Black patients are healthier than equally sick White patients, as less money was spent on them (10.1126/science.aax2342). Biased data and dangerous AI conclusions exist in most medical fields, but attempts to control for that bias remain limited.

When it comes to dermatology,  artificial intelligence is being widely implemented to classify and diagnose skin lesions. A study published in Nature demonstrated that artificial intelligence is capable of classifying skin cancer with a level of competence comparable to dermatologists. Other studies employing similar algorithms reported the same. After widely analyzing some of the most popular open datasets used to train the algorithms in which these studies are based, we discovered the data predominantly contains images of lesions in caucasian skin. To avoid replicating existing bias, it is crucial to make sure the data collected reflects the diversity of existing populations.

In this project, we will use openly available biomedical data to explore how bias affects diagnosis in underrepresented populations. We will focus on skin lesion data, where diversity can be quantified by the data samples’ color. We will train convolutional neural networks (CNNs) to classify leasioned vs. healthy samples (10.1038/nature21056). As most available datasets are heavily biased towards caucasian samples, we will first present to the CNNs only caucasian samples and test their performance on darker skin. We will then gradually increase the number of non caucasian samples in the training data. We expect the networks’ performance on darker skin to increase as a function of the diversity in the data that the algorithm has already seen. 

To our knowledge, there are no studies that have tested the accuracy of ai-driven skin lesion classification technologies in dark-skinned patients. To quantify the problem, we are working on training a deep learning algorithm with caucasian skin samples and testing how it performs on darker skin.  Our end goal is to expand the ethnic variability of the dataset and compare how it performs against algorithms trained with imbalanced data. 

## Project Deliverables 
Thanks to the support of the Mozilla Foundation, following materials will be produced as a result of our project:

1. A neural network trained to classify skin lesion data. This network will be adapted from existing open online tool (e.g. ResNet50) and work that we are doing at the University of Bern for classifying other types of biomedical data (i.e. electroencephalography).
2. An algorithm that can automatically extract skin color from skin lesion data. So far we have been manually computing that from a corner of the image of skin data samples, but we need to automate this procedure and include some quality checks, as the data might not always be homogeneous.
3. Results of the network’s training and testing performance as a function of the diversity in the training and test samples.
4. A set of openly available Jupyter Notebooks that will allow anyone to replicate the analyses of steps 1-3 and build upon them.
5. Depending on our findings for (3), a set of guidelines for how to mitigate bias or how to acknowledge and deal with bias when it is not possible to mitigate it (e.g. when the training samples are not diverse enough).
6. A research paper describing our findings.
7. A white paper summarizing our existing ideas and recommendations. The short guide will briefly describe existing user cases help  understand the consequences of systemic racism in Global Health and sensitise them on racial bias. 
8. An online workshop communicating our findings to the open community.
9. The material of the online workshop, so that others can re-use and add to it, and run their own workshops.
  
## Our team 

### [Athina Tzovara](https://twitter.com/aath0) - University of Bern, Switzerland 

Athina is an assistant professor in the Institute for Computer Science of the University of Bern, Switzerland. Her research focuses at the intersection of biomedical data & Artificial Intelligence. In her work, she is constantly advocating for open and inclusive science practices. Her interest in biomedical data and AI has led her to join open events, where she recently co-hosted sessions on societal impacts of AI and sharing of personal data. Moreover, she has been working on the lack of diversity in biomedical data sharing initiatives (https://bit.ly/30dmqmp). In 2019, through a Mozilla mini-grant she created an open resource for AI in neuroscience (https://bit.ly/2B4zQsC), which has helped introduce students and researchers to open science tools. 

### [Natalia Norori](https://twitter.com/natalianorori) - University of Bristol, United Kingdom
Natalia is an Msc in Epidemiology student with open science and public health research expertise exploring the social determinants of health through Open Data. A year ago, she started Health Data Sharing is Caring, a  project that aims to raise awareness about the lack of representation of minorities in healthcare datasets. The project initially started as an advocacy campaign,  but she has been working to expand it to conduct research and build tools that help uncover racial inequality in existing medical technologies, prevent misdiagnosis, and help reduce racial and social disparities in healthcare. 


### [Florence Aellen](https://www.inf.unibe.ch/about_us/people/ccn/aellen_florence/index_eng.html) - University of Bern, Switzerland
Florence Aellen is a PhD student at the University of Bern working on CNNs for biomedical data (https://bit.ly/2OwAOAR). She will advise the AI implementation of this project.

This is a unique moment to build consensus around the urgent need for trustworthy biomedical datasets and raise awareness about racial injustice.  We are confident that our combined backgrounds will lead to tangible results that will help cultivate a greater sense of data responsibility and accelerate the creation of inclusive biomedical practices. 


## How to contribute 
This project is still in its early stages. We are currently studying existing technologies, collecting and analyzing data to develop the algorithm we will be using. If you are interested in contributing, get in touch with us. 

