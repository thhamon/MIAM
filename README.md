# MIAM
### MIAM Corpus

## 63 Medline abstracts annotated with Food-Drug Interactions
## 14 Medline abstracts marked as irrelevant regarding Food-Drug Interactions

Version: 1.0
Creation Date: November 10, 2020
Realease Date: January 21, 2022

Thierry Hamon, hamon@limsi.fr (corresponding author),
Camille Allely,
Pierrick Bedouch,
Georgetta Bordea,
Amélie Daveluy,
Stephan Garcia,
Cyril Grouin,
Ghada Miremont,
Fleur Mougin,
Jessica Mourao,
Marie-Stéphane Pujol


## 1. Corpus Description

MIAM is a corpus of 77 titles and abstracts issued from The MEDLINE
bibliographical base [1]. Citations related to food-drug interactions
have been selected because they appear in the Stockley catalog
[2]. Some citations can also occur in the POMELO corpus [3].

The titles and abstracts has been manually annotated in order to make
explicit the information on food/drug interactions. Pharmacovigilance
and pharmacologist experts have been involved in the annotation
process. The annotation has been performed by two experts and a
consensus has been done. The BRAT software [4,5] has been used for the
annotation process.


## 2. Repository Structure

MIAM/README.md
	Current readme file

MIAM/LICENSE
	License file

MIAM/corpus/annotated
        Directory containing the relevant abstracts in text format and
        the annotations in Brat format (entities and relations), but also the brat
        configuration files (annotation.conf, tools.conf, visual.conf)


MIAM/corpus/irrelevant
        Directory containing the irrelevant abstracts in text format
        and the annotations in Brat format (text part justifying the
        irrelevance of the abstract), but also the brat configuration
        files (annotation.conf, tools.conf, visual.conf)


## 3. Acknowledgements


This work was supported by the MIAM project (https://miam.limsi.fr/)
and Agence Nationale de la Recherche through the grant
ANR-16-CE23-0012 France [6].


## 4. License

This work (the annotations) is licensed under the Creative Commons
Zero v1.0 Universal.


## 5. References

[1] https://pubmed.ncbi.nlm.nih.gov/

[2] J. W. F. van Mil. Stockley’s drug interactions 11th
    edition. International Journal of Clinical Pharmacy, 38(4) :
    1003–1004, Aug 2016. ISSN 2210-7711. doi :
    10.1007/s11096-016-0325-2. URL https://doi.org/10.1007/
    s11096-016-0325-2.

[3] https://github.com/thhamon/POMELO

[4] Pontus Stenetorp, Sampo Pyysalo, Goran Topić, Tomoko Ohta, Sophia
Ananiadou, and Jun’ichi Tsujii. 2012. brat: a web-based tool for
nlp-assisted text annotation. In Proceedings of the Demonstrations at
the 13th Conference of the European Chapter of the Association for
Computational Linguistics. Association for Computa- tional
Linguistics, Avignon, France, pages 102–107.
http://www.aclweb.org/anthology/E12-2021.

[5] http://brat.nlplab.org/

[6] https://miam.limsi.fr/