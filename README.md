# CBTOPE: Identification of Conformational B-cell Epitopes

**CBTOPE** is the first computational method developed to predict conformational B-cell epitopes in an antigen from its primary amino acid sequence. This resource is particularly valuable for vaccine design, as most B-cell epitopes are conformational
(discontinuous) and identifying them usually requires knowledge of the antigen's tertiary structure, which is not always available.

**Web Server:** [http://webs.iiitd.edu.in/raghava/cbtope/](https://www.google.com/search?q=http://webs.iiitd.edu.in/raghava/cbtope/)


## About the Research

Predicting B-cell epitopes is a fundamental challenge in immunoinformatics and vaccine development. While several methods exist to predict epitopes from 3D structures,
CBTOPE allows researchers to identify these regions when only the protein sequence is known.

* **Dataset:** The models were trained and tested on 187 non-redundant protein chains containing 2,261 antibody-interacting residues.


* **Methodology:** The tool utilizes Support Vector Machine (SVM) models based on the Composition Profile of Patterns (CPP).



## Key Features

### 1. Sequence-Based Prediction

* **Conformational Epitope Identification:** Predicts discontinuous epitopes using only the amino acid sequence of the antigen.


* **High Accuracy:** The CPP-based model achieved a maximum Matthews Correlation Coefficient (MCC) of 0.73 and an accuracy of 86.59%.


* **Benchmarking:** Performance analysis indicates that this sequence-based method is comparable to existing structure-based prediction methods.



### 2. Predictive Models

* **Composition Profile of Patterns (CPP):** The primary model that utilizes the amino acid composition of local segments to predict epitopic residues.


* **Other Profiles:** The study also evaluated Binary Profile of Patterns (BPP) and Physicochemical Profile of Patterns (PPP).



### 3. Integrated Web Interface

* **Epitope Prediction:** Users can submit an antigen sequence to identify potential epitopic residues.


* **User-Friendly Output:** Results are presented with a probability score for each residue, highlighting the most likely antigenic regions.



## Applications

* **Vaccine Design:** Identifying target regions for developing synthetic vaccines or monoclonal antibodies.


* **Immunology:** Understanding the interaction between antigens and the humoral immune system.


* **Drug Discovery:** Selecting optimal antigenic candidates for experimental validation.



## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.

## Support

This study and the development of CBTOPE were supported by the **Council of Scientific and Industrial Research (CSIR)** and the **Department of Biotechnology (DBT)**, Government of India.
