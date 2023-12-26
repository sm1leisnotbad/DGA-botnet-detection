# DGA-botnet-detection
Paper: [DGA-based botnets detection using DNS traffic mining](https://www.sciencedirect.com/science/article/pii/S1319157822000726)
Author: Ahmed M. Manasraha, Thair Khdourc, Raeda Freehat

## Introduction
Botnet is a network of infected wokstations that are remotely managed by BotMaster via the command and control (C&C) server. Botnets are the source of a variety of malicious behaviors such as information theft, phishing, and DDOS assaults. 
Using a Domain Generation Algorithm (DGA) to produce a vast set of domain names is one of the most prevalent ways for  hiding the identity of the C&C server. As a result, existing defensive methods have a limited chance of detecting and defeating such infrastructure. 
Purpose of paper: This susggested system employs machine learning techniques to categorize domain names into malicious or legitmate domain names based on assessing the linguistic qualities of domain names wording to determine the degree of randomization, rarity, typing difficulty, and other related factors. 
The protested system is tested with DNS requests gatherd from various sources and seven distinct DGA botnet families.

This repo is a project which I rebuild the system from paper but the system is not completely likely what paper say. I hope this source can help you understand something about the dga-botnet detection.

