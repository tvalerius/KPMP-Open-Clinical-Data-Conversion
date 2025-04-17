## Converting KPMP Open Access Clinical Data into an AnnData object
This code is to ingest, examine, and produce a useful AnnData object of available open access clinical data from KPMP. The AnnData object is indexed on participant_id and can be used to link a subset of clinical data to other data from KPMP (e.g. scRNA-seq transcriptomics).



## Open Access Clinical Data
A subset of clinical variables are available as open access data in the Atlas Repository. These variables were reviewed for sharing and some aggregated (e.g. binned) to ensure data safety for study participants. 

Using the filters on the left side under the Dataset metadata section, select "Clinical" under Data Category. The link below opens the Atlas Repository with these conditions.

[Repository - Open Access Clinical Metadata](https://atlas.kpmp.org/repository/?size=n_20_n&filters%5B0%5D%5Bfield%5D=data_category&filters%5B0%5D%5Bvalues%5D%5B0%5D=Clinical&filters%5B0%5D%5Btype%5D=any)

More information on all study data can be found on the [Available Data](https://www.kpmp.org/available-data) page.

The current release of openly available clinical data is provided as a csv file (after expanding the zip download) listing all participants and the associated open clinical variable data. The date of the compiled release is indicated in the filename (e.g. `20241202_OpenAccessClinicalData.csv`).

The column names of the current release are as follows:

- Participant ID  
- Tissue Source  
- Protocol  
- Sample Type  
- Enrollment Category  
- Primary Adjudicated Category  
- Sex  
- Age (Years) (Binned)  
- Race  
- KDIGO Stage  
- Baseline eGFR (ml/min/1.73m2) (Binned)  
- Proteinuria (mg) (Binned)  
- A1c (%) (Binned)  
- Albuminuria (mg) (Binned)  
- Diabetes History  
- Diabetes Duration (Years)  
- Hypertension History  
- Hypertension Duration (Years)  
- On RAAS Blockade  
