# BalancED
This repository contains tools written for the [BalancED](https://www.gu.se/en/research/teachers-digital-work-inbalance-between-demands-and-support) research project at the University of Gothenburg. It includes analysis tools for data from packet sniffing and screen activity tracking applications designed to help reveal the platform usage of users along with the infrastructures at play.

## Analysis tools
### [infrastructureReveal.py](https://github.com/paddle-cluster/balanced/blob/master/infrastructureReveal.py)
A Python script that categorizes and visualizes data from packet sniffing tools such as [Wireshark](https://www.wireshark.org) to reveal the service providers with whom data is exchanged. The category scheme is contained in [providers.csv](https://github.com/paddle-cluster/balanced/blob/master/providers.csv).

## Data extraction tools
These scripts can be imported in to the [webscraper.io](https://webscraper.io) Chrome plugin
### [edtechkartan_scraper.json](https://github.com/paddle-cluster/balanced/blob/master/edtechkartan_scraper.json)
Collects all the categories and entries in the Swedish EdTech [database](https://www.edtechkartan.se) of companies selling digital services to schools in Sweden
### [unikumClients_scraper.json](https://github.com/paddle-cluster/balanced/blob/master/unikumClients_scraper.json)
Collects all the login instances for the [Unikum](https://www.unikum.net) school platform producing a list of all the schools and school providers using the platform
### [itsLearningClients_scraper.json](https://github.com/paddle-cluster/balanced/blob/master/itsLearningClients_scraper.json)
Collects all the login instances for the [itsLearning](https://www.itslearning.com) school platform producing a list of all the schools and school providers using the platform
