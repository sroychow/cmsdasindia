---
layout: default
---

# CMS DAS Pre-Exercises

These exercises cover the basic software skills you will need for the CMS Data Analysis school. The material of these pre-exercises have been taken from a series of lectures and tutorials aimed for India-CMS students over the period of February to June 2025. The links to all the lectures and the recordings are available on this indico [page](https://indico.cern.ch/event/1553817/).

All students should aim to complete the pre-exercises with the same laptop they'll use during the school. The goal is to setup your computing environment ahead of time, so you can dive into the real material on day one of CMSDAS. Advanced participants (i.e., those who have spent time on LHC experiments already) may not need to complete the pre-exercises as thoroughly, but please do read through everything to make sure everything works (e.g., accounts, certificates, and environments).

**Requirements**: Participants must have access to a computer with internet access. They should have an computing account at CERN/TIFR.

**How to approach the exercise?**: For each topic, the particpants are required to go through the lectures linked from the indico page and listen to the recordings. Specific instructions for each topic will be provided below.

**Submission of answers**: After completing the lectures, you are asked to fill out this **google form** with answers to specific problems.

**Instructors**: Subir Sarkar, Suvankar Roy Chowdhury 

**Contact**: Please email sroychow@cern.ch, subir.sarkar@cern.ch for more information or assistance on any topic. 

## Topic 1: Introduction to Linux and bash programming

Follow the three part lecture from this [link](https://indico.cern.ch/event/1553817/#b-622142-linux-commands-and-ba). The first two lectures introduces basic Linux commands you shall need, while the third lecture introduces bash programming. After completing these lectures, you shall be able to answer Questions 1-3 from the exercise.

## Topic 2: Obtain a Grid Certificate and CMS VO Registration

A Grid Certificate and CMS VO registration will be needed for the DAS school. There are two main requirements which can be simply summarized: A certificate ensures that you are who you claim to be. A registration in the VO recognizes you (identified by your certificate) as a member of CMS. Follow the instructions in this [twiki](https://twiki.cern.ch/twiki/bin/view/CMSPublic/SWGuideLcgAccess#Getting_a_personal_certificate) to obtain a personal certificate. Then, install the certificate on lxplus/tifr following the [twiki](https://twiki.cern.ch/twiki/bin/view/CMSPublic/WorkBookStartingGrid#ObtainingCert). If the certificate installation is successful, test the installation by executing the command _ voms-proxy-init --rfc --voms cms_.

*Advanced participants (i.e., those who have spent time on CMS experiment already) may skip this step if they have done it.

Now, you should be able to answer question 4.

## Topic 3: Setup a a GitHub Account

Most CMS software is hosted on GitHub. GitHub is a Git repository web-based hosting service, while git is a distributed version control system. In your future analysis work, version control of your analysis code will become a very important task and git will be very useful. In order to checkout and develop CMS software, you will need a github account, which is free.

* In case you don’t have one already, simply go to [https://github.com/join](https://github.com/join) and follow the instructions to create a new account. Choose your username wisely, ideally based on your actual name, as it will be used to sign all of your contributions to CMS code!
* In case you already have an account you can simply use the “Sign in” dialog and put your username and password.
* Make sure you register an SSH key in GitHub, following these instructions for generating a SSH key([link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)) and adding it to your GitHub account([link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)).

Now, submit your answr for Question 5.

## Topic 4: Using Git

In this lecture, the basic concepts of Git will be discussed. Specific git commands needed for development of CMS software shall also be discussed. Lecture and recording can be found [here](https://indico.cern.ch/event/1553817/#b-622143-introduction-to-git-b).

Following this, try to answer Questions 6-7.

## Topic 5: CMSSW basics

Material for this topic is taken from a 5 part lecture and tutorial series held in February-March 2025 for India-CMS students. The slides and recording can be found [here](https://indico.cern.ch/event/1553817/#b-622182-cmssw-tutorial). You are encouraged to go through the lecture slides and recordings for the three lectures and Hands-on session 1 & 2. The detailed instructions for the tutorial can be found in this gitlab [link](https://gitlab.cern.ch/sroychow/cmssw-tutorial).

After completing these lectures you shall be able to answer the Questions 8-10.
