![2023 AMS GOES-R/JPSS Short Course: Making Beautiful Images of NOAA Satellite Data using Python](img/logo.png)


## Welcome!
Please see the [official course page](https://www.star.nesdis.noaa.gov/atmospheric-composition-training/training_AMS_Short_Course_2023.php) for the agenda, pre-training actions, and post-training materials.

Observations from NOAA’s geostationary (GOES-R) and polar-orbiting (JPSS) satellites provide vital information for a myriad of research and operational applications in Atmospheric and Oceanic Sciences. NOAA satellite data are distributed in netCDF4 (.nc) format, however, and the process of accessing the files and processing the contents correctly can be challenging. This short course will break down these barriers by teaching participants how to use Python to perform the basic steps necessary to work with NOAA netCDF4 satellite data files, with the end goal of making professional-quality imagery suitable for use in scientific presentations and journal articles, or in social media. 

## Pre-requisites
To get the most practical experience, we recommend installing python, the required packages, and the downloading the notes before the training. 

To install additional packages:

```bash
conda env update --name base --file environment.yml
```

We understand that some may not have administrative permissions on their computer or have another problem during the class. You can run the course interactively on the cloud using: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/modern-tools-workshop/AMS-python-workshop-2023.git/HEAD)

## Introduction

[Here are some introduction slides](https://www.canva.com/design/DAFU3XviLUM/mkORYrU5Zu7hGTyPo9mgEw/view?utm_content=DAFU3XviLUM&utm_campaign=designshare&utm_medium=link&utm_source=publishpresent) that we'll present before getting started.

First we ask, what makes an image beautiful? 

### What makes a beautiful image?
Creating a beautiful image is about making a "work of art" (although some are!), but rather adhere to the following principles:

1. The image has a **purpose** - the viewer knows what they're looking at and why
2. The image is **well-composed** - are the elements arranged in a way that it makes the purpose more clear. Text and lines are readable and take up appropriate space on graphic
3. **Colors** focus what is important (and are accessible!) which again, furthers the purpose
4. The image shows **clarity**, the viewer easily understands what they're looking at

 We recommend you read Simplified Sciences's guide on [How to Make Good Graphs and Figures for Scientific Papers](https://www.simplifiedsciencepublishing.com/resources/how-to-make-good-graphs-and-figures-for-scientific-papers) to learn more!

### How can I share my beautiful image?
Sharing figures has always been a part of the scientific process and here are some applications:

* Research publications
* Social media - discuss major weather events with peers and engage with the public
* Graphical abstracts - increasingly required by journals
* Blog posts, newsletters, white papers. AMS requests extended abstracts after the conference, can apply what you learned

### What are the steps to creating a beautiful image?
We break the typical workflow down into 8 steps, depending on your plot:

Steps:
0. Read dataset  documentation
1. Launch Jupyter Notebook
2. Download satellite data file(s)
3. Understand the structure and contents of file
4. Handle data arrays
5. Make composite (RGB) image
6. Work with map projections
7. Add professional touches to maps
8. Create a Skew-T plot from satellite soundings

We will apply this workflow to a variety of sensors and satellites: imagers, sounder, geo orbits, and leo orbits!!

## Getting started

First, we'll check that you installed the right packages by running the check_python_packages.ipynb notebook. If there are no errors, fantastic!

Each notebook contains the full workflow for a single "beautiful" image. The instructors will walk through each one and provide additional context on the steps.

## Course Philosophy

* Increase accessibility of NOAA satellite data and lower barriers to analysis
* Teach Python using practical examples and real-world satellite datasets
* Promote reproducible and transparent scientific research

## Acknowledgements

* The live course received generous support from Raytheon Corp. to subsidize tuition cost
* We would like to thank the session organizers, Steve Goodman, Sherrie Morris, Bill Sjoberg, Gary Williams
* Gian Dilawari and Lihang Zhou for their quick turnaround for preparing resources in the NOAA Open Data Dissemination (NODD) for this short course
* Assistance and feedback provided by Philip Casey, Jorel Tores, and William Straka
