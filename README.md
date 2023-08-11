# Process-model-repository
- The data and code for paper: Business Process Retrieval from Large Model Repositories for Industry 4.0
==========================================================

update 2023.8.11
- AP-Group-10000-pnml.zip file is the AP Group Experiment dataset, which contains 10,000 randomly and automatically generated models were recorded using PLG[60]. These PLG-generated models contain four basic structures, that is, sequence, selection, concurrency, and iteration, and their node labels are composed of character numbers.
- BP-Group-1000-pnml.zip file is the BP Group: 1,000 process models proposed by Polyvyanyy et al.[61]. These models contain not only the four basic structures, but also some complex non-TEPM structures.
- CP-Group-651-hdBPMN-pnml.zip is the CP Group: This repository contains the hand-drawn BPMN dataset published in paper “Sketch2BPMN: Automatic recognition of hand-drawn BPMN models”. 651 representative real-life process models were contained. This group contains BSPM models, TEPM models with complex structures, and non-TEPM models.
- AQ1-6.zip file is six different query conditions (labeled AQ1–AQ6) were constructed. AQ1 contained 10 transitions, and each sub-sequent query condition had 10 more transitions than the previous one. The query conditions AQ1–AQ6 were combined with AP group models of different sizes (100–1,000) for the query.
- BQ1-6.zip and CQ1-6.zip file are six different query conditions (labeled BQ1–BQ6 and CQ1-CQ6) were also constructed, respectively. 
===========================================================
- pmr.rar file is the code of process model repository retrivel algrithom using Java.
- pnml-repository.7z file is all pnml data for evaluation and experiments.
