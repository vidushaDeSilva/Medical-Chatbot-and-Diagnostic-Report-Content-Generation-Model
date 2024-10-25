# Medical Chatbot and Diagnostic Report Content Generation Model
Created two LLMs (Large Language Models) for a medical diagnosis assistant web application.
One LLM was trained to be a medical chatbot to answer questions from the user.
Other LLM was trained to genreate content diagnostic report to inform the user about the probable condtions.
Used Google AI Studio to fine tune Gemini 1.0 Pro 001.

Datasets about the following 14 condtions,
1. Atelectasis
2. Cardiomegaly
3. Effusion
4. Infiltration
5. Lung Mass
6. Lung Nodule
7. Pneumonia
8. Pneumothorax
9. Consolidation
10. Edema
11. Emphysema
12. Fibrosis
13. Pleural Thickening
14. Hernia
was created from scratch.

Loss curve for medical chatbot model

<img width="930" alt="image" src="https://github.com/user-attachments/assets/660b342a-b95c-48d9-84d4-07180d27c79d">


Loss curve for report content generating model
<img width="930" alt="image" src="https://github.com/user-attachments/assets/33fddfbb-83df-440f-9e71-26874888a9a3">


**Tools Used:**

Google AI Studio for model training and fine-tuning.
Gemini 1.0 Pro 001 as the model architecture.
 
**references:**

Atelectasis:

https://www.mayoclinic.org/diseases-conditions/atelectasis/symptoms-causes/syc-20369684

Cardiomegaly (Enlarged Heart):

https://www.mayoclinic.org/diseases-conditions/enlarged-heart/symptoms-causes/syc-20355436

Consolidation:

https://www.healthline.com/health/lung-consolidation#symptoms
https://radiopaedia.org/articles/pulmonary-infiltrates-1?lang=gb

Edema (Pulmonary Edema):

https://www.mayoclinic.org/diseases-conditions/pulmonary-edema/symptoms-causes/syc-20377009
 
Effusion (Pleural Effusion):

https://www.webmd.com/lung/pleural-effusion-symptoms-causes-treatments

Infiltration (Pulmonary Infiltrate):

https://www.sciencedirect.com/topics/medicine-and-dentistry/pulmonary-infiltrate

Mass:

https://www.mayoclinic.org/diseases-conditions/lung-cancer/symptoms-causes/syc-20374620
https://www.cancer.org/cancer/types/lung-cancer/detection-diagnosis-staging/signs-symptoms.html

Pulmonary Nodules:

https://www.lung.org/lung-health-diseases/warning-signs-of-lung-disease/nodules
https://my.clevelandclinic.org/health/diseases/14799-pulmonary-nodules

Pneumonia:

https://www.mayoclinic.org/diseases-conditions/pneumonia/symptoms-causes/syc-20354204
https://www.lung.org/lung-health-diseases/lung-disease-lookup/pneumonia/symptoms-and-diagnosis
https://www.who.int/news-room/fact-sheets/detail/pneumonia
https://www.cdc.gov/pneumonia/index.html

Pneumothorax:

https://www.mayoclinic.org/diseases-conditions/pneumothorax/symptoms-causes/syc-20350367
https://www.lung.org/lung-health-diseases/lung-disease-lookup/pneumothorax/symptoms-diagnosis-treatment

Emphysema:

https://www.physio-pedia.com/Emphysema
https://www.mayoclinic.org/diseases-conditions/emphysema/symptoms-causes/syc-20355555
https://www.lung.org/lung-health-diseases/lung-disease-lookup/emphysema

Fibrosis (Pulmonary Fibrosis):

https://www.mayoclinic.org/diseases-conditions/pulmonary-fibrosis/symptoms-causes/syc-20353690

Pleural Thickening:

https://www.mesothelioma.com/asbestos-cancer/pleural-thickening/

Hernia (Lung Hernia):

https://www.urmc.rochester.edu/encyclopedia/content.aspx?ContentTypeID=22&ContentID=lungHernia
