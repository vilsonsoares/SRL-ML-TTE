#Paper: Machine Learning applied to support medical decision in Transthoracic echocardiogram exams: A Systematic Review

# Complementary material

##Lista de Siglas:

ECHO - echocardiogram <br/>
DHC  - diagnose heart diseases <br/> 
SLR  - Systematic Literature Review  <br/>
AI   - artificial intelligence  <br/>
TTE  - Transthoracic Echocardiogram  <br/>
ML   - Machine learning <br/>
DL   - Deep Learning  <br/>
RF   - Random Forest <br/>
DFCN - Deep Fully Convolutional Network <br/>
CNN  - Convolutional Neural Network <br/>
GAN  - General adversarial Network <br/>
RNN  - Recurrent Neural Network <br/>
LSTM - long-term memory, bidirectional LSTM <br/>
GRU  - Gated recurring unit <br/>
SRF  - Structured Random Forest <br/>
RFC  - Random Forest Classifier <br/>
DTC  - Decision Tree Classifier <br/>
ROI  - Region of interest <br/>
ACM  - Association for Computing Machinery <br/>
IEEE - Institute of Electrical and Electronics Engineers <br/>
I    - Inclusion <br/>
E    - Exclusion <br/>
ASE  - American Society of Echocardiography <br/>
Ref  - Reference  <br/>
Dim  - Dimension <br/>
TL   - Type learning <br/>
2D   - two-dimensional  <br/>
3D   - three-dimensional <br/>
SP   - Supervised <br/>
SSP  - Semi-Supervised <br/>
LV   - Left Ventricular <br/>
C    - Classification Task <br/>
NMF  - non-negative matrix factorization <br/>
LVEF - Left Ventricular Ejection Fraction <br/>
GLD  - Global Longitudinal Deformation <br/>
EF   - Ejection Fraction <br/>
Acc  - Accuracy <br/>
HF   - Hough Forest <br/>
ES   - End Systolic  <br/>
ED   - End Diastolic  <br/>
MWM  - myocardial wall motion <br/>
CWM  - cardiac wall motion <br/>
ESV  - End Systolic volumes  <br/>
EDV  - End Diastolic volumes <br/>
SVM  - Suport Vector Machine <br/>
CVC  - Cardiac view classification <br/>
CRP  - Chinese restaurant process <br/>
CMR  - Cardiac magnetic resonance <br/>
BPNN - Back Propagation Neural Network <br/>
DPMM - Dirichlet process mixture model <br/>
BoVW - Bag-of-visual-words  <br/>
LVH  - Left Ventricular hypertrophy <br/>
HCM  - hypertrophic cardiomyopathy <br/>
PAH  - pulmonary arterial hypertension <br/>
CAD  - cardiac amyloidosis <br/>
CHF  - congestive heart failure <br/>
DCM  - dilated cardiomyopathy <br/>
PSO  - particle swarm optimization <br/>
LDA  - Linear Discriminant Analysis <br/>
TM   - Template Matching <br/>
MR   - Mitral Regurgitation <br/>
CSM  - Contextual shape models <br/>
CoA  - Aortic Coarctation <br/>
CT   - Computed Tomography <br/>
TAS  - trans-catheter aortic surgery <br/>
DAS  - defect atrial septal <br/>
EUAC - Echocardiography Appropriate Use Criteria <br/>
NLP  - Natural Language Processor <br/>
CRT  - Cardiac Resynchronization Therapy <br/>
LBBB - bundle of His bundle <br/>
ECG  - Electrocardiogram <br/>
RWT  - Relative wall Thickness <br/>
KNN  - K-Nearest Neighbors <br/>
BCS  - Bayesian Compressive Sensing  <br/>
OMP  - Bregman and Orthogonal Matching Pursuit <br/>
QRSd - Regularization Duration on QRS ECG  <br/>
TF-IDF   - Term Frequency – Inverse Document Frequency <br/>
MAPSE    - Mitral Annular Plane Systolic Excursion <br/>
EVLBP    - Extensive Volume Local Binary Pattern <br/>
ELBPU    - Extensive Uniform Local Binary Pattern <br/>
POCUS    - point-of-care ultrasound <br/>
PV-LVNet - Paired-Views LV Network <br/>
LC-KSVD  - supervised dictionary learning <br/> 
SR-DCL   - Sparse Representation and Dictionary Learning <br/>
MSCDL    - Multi-scale Convolutional Deep Learning <br/>
A2C  - Apical Two-Chamber <br/>
A3C  - Apical Three-Chamber <br/>
A4C  - Apical Four-Chamber <br/>
A5C  - Apical Five-Chamber <br/>
ALA  - Apical Long-Axis <br/>
PLA  - Parasternal Long Axis <br/>
PSA  - Parasternal Short Axis <br/>
PSAA - PSA of Aorta <br/>
PSAP - PSA of Papillary <br/>
PSAM - PSA of Mitral <br/>
PSA-AoV - PSA of Aortic Valve <br/>
RV-inflow - Right Ventricular Inflow <br/>
SAX-basal - Basal Short Axis <br/>
SAX-mid   - short axis at mid or mitral level <br/>
SUB4C     - subcostal four-chamber <br/>
SCVC      - subcostal inferior vena cava <br/>
SUBAO     - Subcostal/Abdominal Aorta <br/>
SUPAO     - Suprasternal Aorta/Aortic Arch <br/>
PW        - Pulsed-Wave Doppler <br/>
CW        - Continuous-Wave Doppler <br/>
mmode     - M-mode <br/>
PSA-APEX  - Parasternal Short-Axis apex <br/>
SC4C      - Subcostal Four-Chamber <br/>
SCVC      - Vena Cava Inferior <br/>

##Table I -  CARDIAC VISION IMAGE ACQUISITION  PLAN
Id   | Ref.                  |  dim.  | Patients | Vision                    |  TL     | Task | Techniques   | Metrics   | Precision 
:---: | --------------------  |  :----: | :--------: | ------------------------- |:-------: |:----: | ----------   | ----------| ---------- 
1    | Balaji et. al (2015)  |  2D    | 200      | A2C, A4C, PSA, PLA        | Sup     | C    | BPNN, SVM    | Acc       | 0.875 
2    | Khamis et. al (2017)  |  2D    | 309      | A2C, A4C, ALA             | Sup     | C    | LC-KSVD      | Acc       | 0.950
3    | Penatti et. al (2015) |  2D    | 52       | A2C, A4C, PLA, PSA-MID    | Sup     | C    | BoVW         | Acc       | 0.900
4    | Gao et. al (2017)     |  2D    | 93       | A2C, A3C, A4C, A5C, PLA, PSAA, PSAM, PSAP | Sup     | C    | CNN          | Acc       | 0.921
5    | Madani et. al (2018a) |  2D    | -        | PSLA, SAX-MID, SAX-BASAL, A4C, A5C, A2C, A3C, SUB4C, SCVC, SUBAO, SUPAO, PW, CW, MMODE, RV-INFLOW      | Sup     | C    | CNN          | Acc       | 0.917 
6    | Madani et. al (2018b) |  2D    | -        | =Id 5                     | Sup     | C    | CNN <br/> GAN| Acc       | 0.912 <br/>0.923     
7   | Zhang et. al (2018)   |  2D    | 460      | PLA.remote, PLA.zoom of LA, PLA, PLA.centered on LA, RV-INFLOW, PSA-APEX, PSAP, PSAM, PSA-AoV, PSAX-AoV zoom, A2C.no occlusions, A2C.ocluded LA, A2C.ocluded LV, A3C.no occlusions, A3C.ocluded LA, A3C.ocluded LV, A4c.no occlusions, A4C.ocluded LA, A4C.ocluded LV, A5C, Subcostal, Supraesternal, other.     |Sup/Semi| C    | CNN          | Acc       | 0.84
8    | Ostvik et. al (2019)  |  2D/3D | 470      | A2C, A4C, ALA, PLA, PSA, SC4C, SCVC | Sup     | C    | CNN          | Acc       | 0.983
9    | Zhu et. al (2018)     |  3D    | -        | A4C, A2C, A3C,PSAM, PSAP, PSA-APEX  | Sup     | C    | Hough Forest | Acc       | 0.804 

##Table II - ANALYSIS OFCARDIACFUNCTIONS

Id    | Ref.                       | Disease    | dim. | Patients | Vision  |  TL      | Task | Techniques  | metrics | Precision 
:---: | ----                       | -------    | ---- | -------- | ------  |  --      | ---- | ----------  | -------|--------- 
10    |Yuan et. al (2017)          | EDV,ESV    | 2D   | 99   | A2C, A4C, PLA, PSA | - | S | NMF          | r |  0.9196
11    | Jafari et. al (2019)       | LVEF       | 2D   | 427      | A2C, A4C| Sup      | S    | DFCN           | Acc  | 0.92
12    | Veni et. al (2018)         | LVEF       | 2D   | -        | A4C     | Sup      | S    | DFCN      | DICE | 0.90 
13    | Raynaud et. al (2017)      | LVEF       | 2D   | 114      | A2C, A3C, A4C| Sup | S/C  | CNN            | <p>&micro;</p> | 0.95
14    | Leclerc et. alt (2018)     | LVEF, GLD  | 2D   | 500      |A2C, A4C | Sup      | S    | CNN U-Net      | DICE| <p>EF:(-13.7&plusmn;8.6)<br/> MAPSE:(-0.9&plusmn;4.6)</p> 
15    |Leclerc et. al (2019)       | LVEF       | 2D   | 500      | A2C, A4C| Sup.     | C    | CNN U-Net      | r    |<p> EDV:0.954<br/> ESV:0.964<br/> LVFE:0.823</p> 
16    | Zyuzin et. al (2018)       | LVEF       | 2D   | 94       | A4C     | Sup      | S    | CNN U-Net      | Acc  | 0.923 
17    |Dezaki et. al (2018)        | LVEF       | 2D   | 3469     | A4C, PLA| Sup.     | R | CNN, RNN | <p>&micro;</p> | <p>ED:(0.20&plusmn;0.67) <br/> ES:(1.43&plusmn;1.30)</p> 
18    |Ge et. al (2019)            | LV-V       | 2D   | 50  | A2C, A4C, A2C+A4C | Sup | S    | PV-LVNet | <p>Cronbach &alpha;</p> | 0.974 
19    |Bobkova et. al (2016)       | LVEF       | 2D   | 26       | A4C     | Sup      | S    | RFC e DTC       | AUC  | 0.930
20    |Bobkov et. al (2016)        | LVEF       | 2D   | 26       | A4C     | Sup      | S     | RFC e DTC       | AUC  | 0.930
21    |Leclerc et. al (2017)       | LVEF       | 2D   | 200      | A4C     | Sup      | S    |SRF              | DICE | <p>(0.92&plusmn;0.03)<br/> (0.93&plusmn;0.04)</p>
22    |Ouzir et. al (2017)         | LVEF       | 2D   | -        | A4C, PSA| Sup      |      | SR-DL           | CD²<br/> MI<br/> SSD | <p>(0.147&plusmn;0.088)<br/> (0.157&plusmn;0.091) <br/> (0.173&plusmn;0.105)</p>
23    |Zyuzin et. al (2016)        | LVEF       | 2D   | 26       | A4C     | Sup      | S    | Bag-10          | Acc  | 0.984
24    |Belous et. al (2016)        | LVEF       | 2D   | -        | A4C     | Sup      | S,C  |  CSM,CRP        | Acc  | 0.917
25    |Bernier et. al (2017)       | LVEF       | 3D   | 75       |ALA      | Sup      | S    | Graph cut | r     | EDV:0.99<br/> ESV:0.99 <br/> FE:0.96
26    |Narang et. al (2018)        |LVEF-V e AE | 3D   | 20       | A2C, A4C| -        | S    | Philips TomTec |  B–Altman |EDV:0.95<br/> ESV:0.97<br/> EF: 0.91 
27    |Dong et. al (2018)          | LVEF       | 3D   | -        | -       | Sup      | S    | DFCN           | R²   |<p>EDV:0.982<br/> ESV:0.979<br/> EF:0.792</p>
28    | Dong et. al (2016a)        | LVEF       | 3D   | -        | -       | Sup      | S    | CNN, GVF-Snake | R²  | 0.8184 
29    | Dong et. al (2016b)        | LVEF       | 3D   | 90       | -       | Not Sup  | R    | MSCDL e RF     | r   | EDV:0.850 <br/> ESV:0.871 <br/> EF:0.863
30    |Volpato et. al (2019)       | LVEF       | 3D   | 23       | A4C     | Sup      | S | ML-Algoritms      | r, B–Altman</p> | <p>(126&plusmn;39)g </p>
31    |Genovese et. al (2019)      | RVEF-V     | 3D   | 55       | A4C     | Sup      | S | ML-Algoritms     | r | EDV:0.91<br/> ESV:0.92<br/> EF:0.87
32    |Kusunose et. al (2019)      | CWM        | 2D   | 400      | -       | Sup.     | C  | DCNN            |  Acc   | 0.917
33    |Omar et. al (2018)          | MWM        | 2D+T | -        | A4C     | Sup.     | C  | CNN             |  Acc<br/> Esp<br/>Sens | 0.854 <br/> 0.776 <br/> 0.928
 
##Table III - DETECTION  OF CARDIAC DISEASE

Id    | Ref.                       | Disease    | dim. | Patients | Vision  |  TL      | Task | Techniques  | metrics | Precision 
:---: | ----                       | -------    | ---- | -------- | ------  |  --      | ---- | ----------  | -------|--------- 
34    |Zhang et. al (2018)         |HCM, PAH, CAD| 2D  | 460      | =id-43  | Sup      | C | CNN | Acc | HCM:0.93<br/>PAH:0.85 <br/> CAD:0.87
35    |Madani et. al (2018b)       | LVH        | 2D   | -        | A4C     | Sup/ Semi| C  | CNN <br/> GAN  |  Acc | 0.912 <br/> 0.923
36    |Silva et. al (2018)         | LVEF       | 3D   | 30       | A4C     | Sup.     | C  | 3D-CNN          |  Acc <br/> F1 | 0.780 <br/> 0.713
37    |Raghavendra et. al (2017)   | DCM         | 2D  | 100      | A4C     | Sup      | C | PSO e SVM | Acc <br/> Sens<br/>Espec | 0.9933<br/> 0.9866 <br/> 1.00
38    |Moghaddasi et. al (2016)    | MR          | 2D  | 139      |A2C, A4C | Sup      | C | SVM,LDA | Espec <br/> Sens | 0.9938<br/>  0.9963
39    |Smistad et. al (2018)       | LVEF e MAPSE| 2D  | 75       |A2C, A4C | Sup.     | S | DCNN     | B-Altmann | <p>FE:(-13.7&plusmn; 8.6) <br/> MAPSE:(-0.9&plusmn;4.6)$</p> 
40    |Bin et. al (2018)           | Aortic Valve| 2D  | 30       | PSA     | Sup      | D  | Faster R-CNN   |  Acc | 0.949
41    |Pereira et. al (2017)       | CoA         | 2D  | 64     |A4C, PSA, SSNA | Sup  | C  | SVM Ensemble  | r | 0.129     
42    |Khalil et. al (20172)       | TAS         |2D/3D| 10       | PLA, PSA| Sup      | - | Framework | Acc, DICE | PSA:0.81 <br/>PLA:0.79
43    |Otani et. al (2016)         | AF          | 3D  | 88     | A2C, A3C e A4C| Sup  | S | Philips HeartModel | r | P1:0.88–0.98<br/>P2:0.94–0.99       
44    |Borkar et. al (2018)        | DCM e DAS   | 2D  | -        | -             | Sup. | S,C  | SVM  |  Acc | 0.983
45    |Lu et. al (2018)            | LVEF        | 2D  | -        | A2C, A4C, PLA | Sup. | R    | CNN U-Net  | AUC | 0.84 
46    |Eisman et. al (2017)        | -           | 2D  | 30,120   | -             | Sup | C     | TF-IDF  |  C. Kappa | <p>(0.89 &plusmn;0.6)
47    |Lei et. al (2019)           | CRT         | 2D  | 184      | A2C, A4C, PLA | Sup. | R    | SVM  | AUC | 0.8481
