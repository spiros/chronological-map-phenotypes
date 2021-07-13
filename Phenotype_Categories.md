# Mapping 306 CALIBER phenotypes to 16 disease categories  

This maps 306 of the CALIBER phenotypes by *Kuan et al.* to the following 16 categories:

* Diseases of the Circulatory System  
* Diseases of the Digestive System  
* Skin conditions  
* Diseases of the Genitourinary system  
* Haematological/Immunological conditions  
* Mental Health Disorders  
* Diseases of the Respiratory System  
* Musculoskeletal conditions  
* Diseases of the Eye  
* Neurological conditions  
* Infectious Diseases  
* Benign Neoplasm/CIN  
* Perinatal conditions  
* Diseases of the Endocrine System  
* Diseases of the Ear  
* Cancers  

These 16 categories are taken from *Supplementary Table S1. Medical Conditions with the abbreviated terms used in this article and their disease categories* from the paper:  

<br>

>Kuan V., Denaxas S., Gonzalez-Izquierdo A. et al. _A chronological map of 308 physical and mental health conditions from 4 million individuals in the National Health Service_ published in the Lancet Digital Health - DOI <a href="https://www.thelancet.com/journals/landig/article/PIIS2589-7500(19)30012-3/fulltext">10.1016/S2589-7500(19)30012-3</a>  

<br>

Please note: 
* *Supplementary Table S1* does not provide a direct mapping to CALIBER phenotypes and there are cases where different names are used (e.g. `Scleroderma` vs `Systemic Sclerosis`). 
* Conditions `Type 1 Diabetes Mellitus` and `Type 2 Diabetes Mellitus` are present in *Supplementary Table S1* but not listed as phenotypes within `dictionary.csv` and therefore these conditions are not included in the mapping (although they would be classified under `Diseases of the Endocrine System`)  

<br>

The below mapping is produced and shared by [Dr Chris Tomlinson](https://ctomlinson.net).  

<br>

# `phenotype_categories_mapping.csv`  
Content reproduced in markdown below for ease of browsing:

| Phenotype                                                                     | Category                                |
|-------------------------------------------------------------------------------|-----------------------------------------|
| Abdominal aortic aneurysm                                                     | Diseases of the Circulatory System      |
| Abdominal Hernia                                                              | Diseases of the Digestive System        |
| Acne                                                                          | Skin conditions                         |
| Actinic keratosis                                                             | Skin conditions                         |
| Acute Kidney Injury                                                           | Diseases of the Genitourinary system    |
| Agranulocytosis                                                               | Haematological/Immunological conditions |
| Alcohol Problems                                                              | Mental Health Disorders                 |
| Alcoholic liver disease                                                       | Diseases of the Digestive System        |
| Allergic and chronic rhinitis                                                 | Diseases of the Respiratory System      |
| Alopecia areata                                                               | Skin conditions                         |
| Other anaemias                                                                | Haematological/Immunological conditions |
| Anal fissure                                                                  | Diseases of the Digestive System        |
| Angiodysplasia of colon                                                       | Diseases of the Digestive System        |
| Ankylosing spondylitis                                                        | Musculoskeletal conditions              |
| Anorectal fistula                                                             | Diseases of the Digestive System        |
| Anorectal prolapse                                                            | Diseases of the Digestive System        |
| Anterior and Intermediate Uveitis                                             | Diseases of the Eye                     |
| Anxiety disorders                                                             | Mental Health Disorders                 |
| Aplastic anaemias                                                             | Haematological/Immunological conditions |
| Appendicitis                                                                  | Diseases of the Digestive System        |
| Asbestosis                                                                    | Diseases of the Respiratory System      |
| Aspiration pneumonitis                                                        | Diseases of the Respiratory System      |
| Asthma                                                                        | Diseases of the Respiratory System      |
| Atrial fibrillation                                                           | Diseases of the Circulatory System      |
| Atrioventricular block, first degree                                          | Diseases of the Circulatory System      |
| Atrioventricular block, second degree                                         | Diseases of the Circulatory System      |
| Atrioventricular block, complete                                              | Diseases of the Circulatory System      |
| Autism and Asperger's syndrome                                                | Mental Health Disorders                 |
| Autoimmune liver disease                                                      | Diseases of the Digestive System        |
| Disorders of autonomic nervous system                                         | Neurological conditions                 |
| Bacterial Diseases (excl TB)                                                  | Infectious Diseases                     |
| Barrett's oesophagus                                                          | Diseases of the Digestive System        |
| Bell's palsy                                                                  | Neurological conditions                 |
| Benign neoplasm of brain and other parts of central nervous system            | Benign Neoplasm/CIN                     |
| Benign neoplasm of colon, rectum, anus and anal canal                         | Benign Neoplasm/CIN                     |
| Benign neoplasm of ovary                                                      | Benign Neoplasm/CIN                     |
| Benign neoplasm of stomach and duodenum                                       | Benign Neoplasm/CIN                     |
| Benign neoplasm and polyp of uterus                                           | Benign Neoplasm/CIN                     |
| Hyperplasia of prostate                                                       | Diseases of the Genitourinary system    |
| Bifascicular block                                                            | Diseases of the Circulatory System      |
| Bipolar affective disorder and mania                                          | Mental Health Disorders                 |
| Visual impairment and blindness                                               | Diseases of the Eye                     |
| Bronchiectasis                                                                | Diseases of the Respiratory System      |
| Other Cardiomyopathy                                                          | Diseases of the Circulatory System      |
| Carpal tunnel syndrome                                                        | Musculoskeletal conditions              |
| Cataract                                                                      | Diseases of the Eye                     |
| Cerebral Palsy                                                                | Neurological conditions                 |
| Carcinoma in situ_cervical                                                    | Benign Neoplasm/CIN                     |
| Cholangitis                                                                   | Diseases of the Digestive System        |
| Cholecystitis                                                                 | Diseases of the Digestive System        |
| Cholelithiasis                                                                | Diseases of the Digestive System        |
| Non-acute cystitis                                                            | Diseases of the Genitourinary system    |
| Postviral fatigue syndrome, neurasthenia and fibromyalgia                     | Neurological conditions                 |
| Chronic Kidney Disease                                                        | Diseases of the Genitourinary system    |
| COPD                                                                          | Diseases of the Respiratory System      |
| Chronic sinusitis                                                             | Diseases of the Respiratory System      |
| Chronic viral hepatitis                                                       | Infectious Diseases                     |
| Liver fibrosis, sclerosis and cirrhosis                                       | Diseases of the Digestive System        |
| Coeliac disease                                                               | Diseases of the Digestive System        |
| Collapsed vertebra                                                            | Musculoskeletal conditions              |
| Congenital malformations of cardiac septa                                     | Perinatal conditions                    |
| Coronary heart disease not otherwise specified                                | Diseases of the Circulatory System      |
| Crohn's disease                                                               | Diseases of the Digestive System        |
| Cystic Fibrosis                                                               | Diseases of the Endocrine System        |
| Hearing loss                                                                  | Diseases of the Ear                     |
| Delirium, not induced by alcohol and other psychoactive substances            | Mental Health Disorders                 |
| Dementia                                                                      | Mental Health Disorders                 |
| Depression                                                                    | Mental Health Disorders                 |
| Dermatitis (atopc/contact/other/unspecified)                                  | Skin conditions                         |
| Diabetes                                                                      | Diseases of the Endocrine System        |
| Diabetic ophthalmic complications                                             | Diseases of the Eye                     |
| Diabetic neurological complications                                           | Neurological conditions                 |
| Diaphragmatic hernia                                                          | Diseases of the Digestive System        |
| Dilated cardiomyopathy                                                        | Diseases of the Circulatory System      |
| Diverticular disease of intestine (acute and chronic)                         | Diseases of the Digestive System        |
| Down's syndrome                                                               | Perinatal conditions                    |
| Dysmenorrhoea                                                                 | Diseases of the Genitourinary system    |
| Anorexia and bulimia nervosa                                                  | Mental Health Disorders                 |
| Encephalitis                                                                  | Infectious Diseases                     |
| End stage renal disease                                                       | Diseases of the Genitourinary system    |
| Endometrial hyperplasia and hypertrophy                                       | Diseases of the Genitourinary system    |
| Endometriosis                                                                 | Diseases of the Genitourinary system    |
| Enteropathic arthropathy                                                      | Musculoskeletal conditions              |
| Enthesopathies & synovial disorders                                           | Musculoskeletal conditions              |
| Epilepsy                                                                      | Neurological conditions                 |
| Erectile dysfunction                                                          | Diseases of the Genitourinary system    |
| Essential tremor                                                              | Neurological conditions                 |
| Fatty Liver                                                                   | Diseases of the Digestive System        |
| Female infertility                                                            | Diseases of the Genitourinary system    |
| Fibromatoses                                                                  | Musculoskeletal conditions              |
| Folate deficiency anaemia                                                     | Haematological/Immunological conditions |
| Fracture of hip                                                               | Musculoskeletal conditions              |
| Fracture of wrist                                                             | Musculoskeletal conditions              |
| Mycoses                                                                       | Infectious Diseases                     |
| Gastritis and duodenitis                                                      | Diseases of the Digestive System        |
| Gastro-oesophageal reflux disease                                             | Diseases of the Digestive System        |
| Giant Cell arteritis                                                          | Musculoskeletal conditions              |
| Glaucoma                                                                      | Diseases of the Eye                     |
| Glomerulonephritis                                                            | Diseases of the Genitourinary system    |
| Gout                                                                          | Musculoskeletal conditions              |
| Haemangioma, any site                                                         | Benign Neoplasm/CIN                     |
| Heart failure                                                                 | Diseases of the Circulatory System      |
| Hidradenitis suppurativa                                                      | Skin conditions                         |
| High birth weight                                                             | Perinatal conditions                    |
| HIV                                                                           | Infectious Diseases                     |
| Hodgkin Lymphoma                                                              | Cancers                                 |
| Hydrocoele (incl infected)                                                    | Diseases of the Genitourinary system    |
| Hyperkinetic disorders                                                        | Mental Health Disorders                 |
| Hyperparathyroidism                                                           | Diseases of the Endocrine System        |
| Splenomegaly                                                                  | Haematological/Immunological conditions |
| Hypertension                                                                  | Diseases of the Circulatory System      |
| Hypertrophic Cardiomyopathy                                                   | Diseases of the Circulatory System      |
| Hypertrophy of nasal turbinates                                               | Diseases of the Respiratory System      |
| Hyposplenism                                                                  | Haematological/Immunological conditions |
| Intracranial hypertension                                                     | Neurological conditions                 |
| Immunodeficiencies                                                            | Haematological/Immunological conditions |
| Infection of anal and rectal regions                                          | Infectious Diseases                     |
| Infection of bones and joints                                                 | Infectious Diseases                     |
| Infections of the digestive system                                            | Infectious Diseases                     |
| Ear and Upper Respiratory Tract Infections                                    | Infectious Diseases                     |
| Eye infections                                                                | Infectious Diseases                     |
| Infections of the Heart                                                       | Infectious Diseases                     |
| Infection of liver                                                            | Infectious Diseases                     |
| Lower Respiratory Tract Infections                                            | Infectious Diseases                     |
| Infection of male genital system                                              | Infectious Diseases                     |
| Infection of other or unspecified genitourinary system                        | Infectious Diseases                     |
| Other nervous system infections                                               | Infectious Diseases                     |
| Other or unspecified infectious organisms                                     | Infectious Diseases                     |
| Infections of Other or unspecified organs                                     | Infectious Diseases                     |
| Infection of skin and subcutaneous tissues                                    | Infectious Diseases                     |
| Intellectual disability                                                       | Mental Health Disorders                 |
| Intervertebral disc disorders                                                 | Musculoskeletal conditions              |
| Intracerebral haemorrhage                                                     | Diseases of the Circulatory System      |
| Intrauterine hypoxia                                                          | Perinatal conditions                    |
| Iron deficiency anaemia                                                       | Haematological/Immunological conditions |
| Irritable bowel syndrome                                                      | Diseases of the Digestive System        |
| Ischaemic stroke                                                              | Diseases of the Circulatory System      |
| Juvenile arthritis                                                            | Musculoskeletal conditions              |
| Keratitis                                                                     | Diseases of the Eye                     |
| Left bundle branch block                                                      | Diseases of the Circulatory System      |
| Leiomyoma of uterus                                                           | Benign Neoplasm/CIN                     |
| Leukaemia                                                                     | Cancers                                 |
| Lichen planus                                                                 | Skin conditions                         |
| Hepatic failure                                                               | Diseases of the Digestive System        |
| Slow fetal growth or low birth weight                                         | Perinatal conditions                    |
| Low HDL-C                                                                     | Diseases of the Endocrine System        |
| Lupus erythematosus (local and systemic)                                      | Musculoskeletal conditions              |
| Macular degeneration                                                          | Diseases of the Eye                     |
| Male infertility                                                              | Diseases of the Genitourinary system    |
| Meniere disease                                                               | Diseases of the Ear                     |
| Meningitis                                                                    | Infectious Diseases                     |
| Menorrhagia and polymenorrhoea                                                | Diseases of the Genitourinary system    |
| Migraine                                                                      | Neurological conditions                 |
| Monoclonal gammopathy of undetermined significance (MGUS)                     | Cancers                                 |
| Motor neuron disease                                                          | Neurological conditions                 |
| Multiple sclerosis                                                            | Neurological conditions                 |
| Multiple valve dz                                                             | Diseases of the Circulatory System      |
| Myasthenia gravis                                                             | Neurological conditions                 |
| Myelodysplastic syndromes                                                     | Cancers                                 |
| Myocardial infarction                                                         | Diseases of the Circulatory System      |
| Nasal polyp                                                                   | Diseases of the Respiratory System      |
| Neonatal jaundice (excl haemolytic dz of the newborn)                         | Perinatal conditions                    |
| Neuromuscular dysfunction of bladder                                          | Diseases of the Genitourinary system    |
| Non-Hodgkin Lymphoma                                                          | Cancers                                 |
| Nonrheumatic aortic valve disorders                                           | Diseases of the Circulatory System      |
| Nonrheumatic mitral valve disorders                                           | Diseases of the Circulatory System      |
| Obesity                                                                       | Diseases of the Endocrine System        |
| Obsessive-compulsive disorder                                                 | Mental Health Disorders                 |
| Obstructive and reflux uropathy                                               | Diseases of the Genitourinary system    |
| Oesophagitis and oesophageal ulcer                                            | Diseases of the Digestive System        |
| Oesophageal varices                                                           | Diseases of the Digestive System        |
| Osteoarthritis (excl spine)                                                   | Musculoskeletal conditions              |
| Osteoporosis                                                                  | Musculoskeletal conditions              |
| Other haemolytic anaemias                                                     | Haematological/Immunological conditions |
| Pancreatitis                                                                  | Diseases of the Digestive System        |
| Parasitic infections                                                          | Infectious Diseases                     |
| Parkinson's disease                                                           | Neurological conditions                 |
| Patent ductus arteriosus                                                      | Perinatal conditions                    |
| Female pelvic inflammatory disease                                            | Infectious Diseases                     |
| Peptic ulcer disease                                                          | Diseases of the Digestive System        |
| Pericardial effusion (noninflammatory)                                        | Diseases of the Circulatory System      |
| Peripheral arterial disease                                                   | Diseases of the Circulatory System      |
| Peripheral neuropathies (excluding cranial nerve and carpal tunnel syndromes) | Neurological conditions                 |
| Peritonitis                                                                   | Diseases of the Digestive System        |
| Personality disorders                                                         | Mental Health Disorders                 |
| Pilonidal cyst/sinus                                                          | Skin conditions                         |
| Multiple myeloma and malignant plasma cell neoplasms                          | Cancers                                 |
| Pleural effusion                                                              | Diseases of the Respiratory System      |
| Pleural plaque                                                                | Diseases of the Respiratory System      |
| Pneumothorax                                                                  | Diseases of the Respiratory System      |
| Polycystic ovarian syndrome                                                   | Diseases of the Endocrine System        |
| Polycythaemia vera                                                            | Cancers                                 |
| Polymyalgia Rheumatica                                                        | Musculoskeletal conditions              |
| Portal hypertension                                                           | Diseases of the Digestive System        |
| Post-term infant                                                              | Perinatal conditions                    |
| Postcoital and contact bleeding                                               | Diseases of the Genitourinary system    |
| Posterior Uveitis                                                             | Diseases of the Eye                     |
| Postmenopausal bleeding                                                       | Diseases of the Genitourinary system    |
| Prematurity                                                                   | Perinatal conditions                    |
| Primary Malignancy_biliary tract                                              | Cancers                                 |
| Primary Malignancy_Bladder                                                    | Cancers                                 |
| Primary Malignancy_Bone and articular cartilage                               | Cancers                                 |
| Primary Malignancy_colorectal and anus                                        | Cancers                                 |
| Primary Malignancy_Brain, Other CNS and Intracranial                          | Cancers                                 |
| Primary Malignancy_Breast                                                     | Cancers                                 |
| Primary Malignancy_Cervical                                                   | Cancers                                 |
| Primary Malignancy_Kidney and Ureter                                          | Cancers                                 |
| Primary Malignancy_Liver                                                      | Cancers                                 |
| Primary Malignancy_Lung and trachea                                           | Cancers                                 |
| Primary Malignancy_Malignant Melanoma                                         | Cancers                                 |
| Primary Malignancy_Mesothelioma                                               | Cancers                                 |
| Primary Malignancy_Multiple independent sites                                 | Cancers                                 |
| Primary Malignancy_Oesophageal                                                | Cancers                                 |
| Primary Malignancy_Oro-pharyngeal                                             | Cancers                                 |
| Primary Malignancy_Other Organs                                               | Cancers                                 |
| Primary Malignancy_Ovarian                                                    | Cancers                                 |
| Primary Malignancy_Pancreatic                                                 | Cancers                                 |
| Primary Malignancy_Prostate                                                   | Cancers                                 |
| Primary Malignancy_Other Skin and subcutaneous tissue                         | Cancers                                 |
| Primary Malignancy_Stomach                                                    | Cancers                                 |
| Primary Malignancy_Testicular                                                 | Cancers                                 |
| Primary Malignancy_Thyroid                                                    | Cancers                                 |
| Primary Malignancy_Uterine                                                    | Cancers                                 |
| Primary pulmonary hypertension                                                | Diseases of the Circulatory System      |
| Primary or Idiopathic Thrombocytopaenia                                       | Haematological/Immunological conditions |
| Psoriasis                                                                     | Skin conditions                         |
| Psoriatic arthropathy                                                         | Musculoskeletal conditions              |
| Ptosis of eyelid                                                              | Diseases of the Eye                     |
| Pulmonary collapse (excl pneumothorax)                                        | Diseases of the Respiratory System      |
| Pulmonary embolism                                                            | Diseases of the Circulatory System      |
| Other interstitial pulmonary diseases with fibrosis                           | Diseases of the Respiratory System      |
| Raised LDL-C                                                                  | Diseases of the Endocrine System        |
| Raised Total Cholesterol                                                      | Diseases of the Endocrine System        |
| Raised Triglycerides                                                          | Diseases of the Endocrine System        |
| Raynaud's syndrome                                                            | Diseases of the Circulatory System      |
| Postinfective and reactive arthropathies                                      | Musculoskeletal conditions              |
| Respiratory distress of newborn                                               | Perinatal conditions                    |
| Respiratory failure                                                           | Diseases of the Respiratory System      |
| Retinal detachments and breaks                                                | Diseases of the Eye                     |
| Retinal vascular occlusions                                                   | Diseases of the Eye                     |
| Rheumatic fever                                                               | Infectious Diseases                     |
| Rheumatic valve dz                                                            | Diseases of the Circulatory System      |
| Rheumatoid Arthritis                                                          | Musculoskeletal conditions              |
| Right bundle branch block                                                     | Diseases of the Circulatory System      |
| Rosacea                                                                       | Skin conditions                         |
| Sarcoidosis                                                                   | Haematological/Immunological conditions |
| Schizophrenia, schizotypal and delusional disorders                           | Mental Health Disorders                 |
| Scleritis and episcleritis                                                    | Diseases of the Eye                     |
| Systemic sclerosis                                                            | Musculoskeletal conditions              |
| Scoliosis                                                                     | Musculoskeletal conditions              |
| Seborrheic dermatitis                                                         | Skin conditions                         |
| Secondary Malignancy_Adrenal gland                                            | Cancers                                 |
| Secondary Malignancy_Bone                                                     | Cancers                                 |
| Secondary Malignancy_Bowel                                                    | Cancers                                 |
| Secondary Malignancy_Brain, Other CNS and Intracranial                        | Cancers                                 |
| Secondary malignancy_Liver and intrahepatic bile duct                         | Cancers                                 |
| Secondary Malignancy_Lung                                                     | Cancers                                 |
| Secondary Malignancy_Lymph Nodes                                              | Cancers                                 |
| Secondary Malignancy_Other organs                                             | Cancers                                 |
| Secondary Malignancy_retroperitoneum and peritoneum                           | Cancers                                 |
| Secondary Malignancy_Pleura                                                   | Cancers                                 |
| Secondary polycythaemia                                                       | Haematological/Immunological conditions |
| Secondary pulmonary hypertension                                              | Diseases of the Circulatory System      |
| Secondary or other Thrombocytopaenia                                          | Haematological/Immunological conditions |
| Bacterial sepsis of newborn                                                   | Perinatal conditions                    |
| Septicaemia                                                                   | Infectious Diseases                     |
| Sick sinus syndrome                                                           | Diseases of the Circulatory System      |
| Sickle-cell anaemia                                                           | Haematological/Immunological conditions |
| Sickle-cell trait                                                             | Haematological/Immunological conditions |
| Sjogren's disease                                                             | Musculoskeletal conditions              |
| Sleep apnoea                                                                  | Diseases of the Respiratory System      |
| Spina bifida                                                                  | Perinatal conditions                    |
| Spinal stenosis                                                               | Musculoskeletal conditions              |
| Spondylolisthesis                                                             | Musculoskeletal conditions              |
| Spondylosis                                                                   | Musculoskeletal conditions              |
| Stable angina                                                                 | Diseases of the Circulatory System      |
| Stroke NOS                                                                    | Diseases of the Circulatory System      |
| Subarachnoid haemorrhage                                                      | Diseases of the Circulatory System      |
| Subdural haematoma - nontraumatic                                             | Diseases of the Circulatory System      |
| Other psychoactive substance misuse                                           | Mental Health Disorders                 |
| Supraventricular tachycardia                                                  | Diseases of the Circulatory System      |
| Syndrome of inappropriate secretion of antidiuretic hormone                   | Diseases of the Endocrine System        |
| Thalassaemia                                                                  | Haematological/Immunological conditions |
| Thalassaemia trait                                                            | Haematological/Immunological conditions |
| Thrombophilia                                                                 | Haematological/Immunological conditions |
| Hypo or hyperthyroidism                                                       | Diseases of the Endocrine System        |
| Tinnitus                                                                      | Diseases of the Ear                     |
| Transient ischaemic attack                                                    | Diseases of the Circulatory System      |
| Trifascicular block                                                           | Diseases of the Circulatory System      |
| Trigeminal neuralgia                                                          | Neurological conditions                 |
| Tuberculosis                                                                  | Infectious Diseases                     |
| Tubulo-interstitial nephritis                                                 | Diseases of the Genitourinary system    |
| Ulcerative colitis                                                            | Diseases of the Digestive System        |
| Undescended testicle                                                          | Diseases of the Genitourinary system    |
| Unstable Angina                                                               | Diseases of the Circulatory System      |
| Urinary Incontinence                                                          | Diseases of the Genitourinary system    |
| Urinary Tract Infections                                                      | Infectious Diseases                     |
| Urolithiasis                                                                  | Diseases of the Genitourinary system    |
| Urticaria                                                                     | Skin conditions                         |
| Female genital prolapse                                                       | Diseases of the Genitourinary system    |
| Venous thromboembolic disease (Excl PE)                                       | Diseases of the Circulatory System      |
| Ventricular tachycardia                                                       | Diseases of the Circulatory System      |
| Viral diseases (excl chronic hepatitis/HIV)                                   | Infectious Diseases                     |
| Vitamin B12 deficiency anaemia                                                | Haematological/Immunological conditions |
| Vitiligo                                                                      | Skin conditions                         |
| Volvulus                                                                      | Diseases of the Digestive System        |