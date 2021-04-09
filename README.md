# ACME (Armed Conflict In The Middle East) 
- This repository is a collection of general studies of armed conflict in the Middle East Regions. Most of the codes in this repository implemented using Python or R programming languages. All the analyses conducted using techniques and methodologies covered in this DSC Master degree program. Here are some of the topics of my interest for my milestones: 

## Topics
* Islamic State.
* Casualties of War in the Middle East and Airstrikes in the Middle East (Note: Emphasis on Iraq, Syria, and Yemen).
* Misc: North Korea Missile Developments.

## Milestone Summary
* This milestone aims to study Islamic State recruitment through Social Media such as JustPasteIt and Twitter. In this milestone, I collected posts and tweets that belong to the Islamic State organization. The majority of the posts collected from the JustPasteIt were in Arabic or some other languages. Therefore, to help me translate all the documents, I used the Google Cloud API translations. Additionally, I collected images posted by the Islamic State organization that contain violence, battlefield footage, or recruitment messages. To understand the contents embedded in these footages, I used the Google Cloud OCR API to extract all the text and store them in my MySQL RDBMS for further analysis. Furthermore, to build my tone classifier model, I used the IBM Tone analyzer to label all the posts on my initial dataset. 
* This milestone aims to conduct a general study of war casualties and conflict in the Middle East either from airstrikes, domestic or international terrorist organizations, and natural causes. Especially in the Middle Eastern regions such as Yemen, Iraq, and Syria because they were a stronghold for the Islamic State organization. 
* This milestone aims to conduct a general study of North Korea's missile capabilities, such as missile types, missile ranges, test locations, and missile manufacturers (i.e., missile technologies similarities with Iran, China Russia). Additionally, North Korea's missile capabilities pose a significant threat to neighboring countries such as Japan, South Korea, and the eastern Asia block.
* This milestone aims to create a deep-learning model that could produce a basic form of natural-language understanding and classify news articles as weather, finance, current trends, politics, sports, and science and technology categories for the given middle east region. Additionally, this milestone aims to study how the news can be a great propaganda tool and influence people's behaviors.

#### **This repository has the following private and public dependencies**:

## Private Python Dependencies: 
* acmenewscollectors-pkg-rioatmadja2018
* acmecontentcollectors-pkg-rioatmadja2018
* orionservermanager-pkg-rioatmadja2018 ( EC2 Instances Managers to deploy codes)

## Public Python Packages: 
* Google Cloud OCR (Google Character Recognitions)
* Google Cloud Translation (Documents Translations)
* Twitter API
* IBM Watson

## **Repository Contents**
* IraqConflict.ipynb
* Atmadja_Rio_DSC520_Final_Project.Rmd
* DSC630MileStone_Atmadja_Rio.ipynb
* DSC540_MileStone_Atmadja_Rio.ipynb
* DSC530_Milestone_AtmadjaRio.ipynb

## **External Private Repository (Bitbucket)** 
* https://portfolio_ratmadja@bitbucket.org/portfolio_ratmadja/whl.acme-contents-collector.git
* https://portfolio_ratmadja@bitbucket.org/portfolio_ratmadja/acme_news_collectors.git
* https://portfolio_ratmadja@bitbucket.org/portfolio_ratmadja/middle_east_dashboard.git
* https://portfolio_ratmadja@bitbucket.org/portfolio_ratmadja/acme_dash_board.git
* https://portfolio_ratmadja@bitbucket.org/portfolio_ratmadja/whl.orion-server-managers.git

## **Technologies**:

#### **Servers**
* Ubuntu 20.04 LTS (Infrastructure)
* Linux Academy Instances 
    
#### **Programming Languages**
* Python
* R 
* Bash

#### **Databases** 
* MySQL Server 
* SQLite

#### **External Libraries** 
* Google Character Recognitions 
* Google Cloud API Translations 
* Plotly Dash 
* IBM Tone Analyzer 
* Scikit-Learns
* Keras 
* Matplotlib 
* Seaborn

#### **Dashboard Applications** 
* http://www.textminingdaesh.ml/
* http://www.textminingdaesh.ml:10000/

#### **Data Sources** 
* ACLED 
* JustPasteIt 
* Global Terrorism Database
* Wikipedia
* Defense Language Institute (General Information References) 

## **MIT License** 

**Copyright (c) 2020 ratmadjads** 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



