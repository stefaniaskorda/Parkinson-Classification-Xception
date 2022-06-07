# Parkinson Detection Project

## Subject: Modelling Parkinson Disease Detection for PD patients with Machine Learning/Deep Learning using Xception.
## AI & Healthcare topics: diagnosis prediction/accuracy, precision
### Symptoms and Diagnosis


# 0. Context: Parkinson symptoms are different for different people. Common symptoms of Parkinson Disease include:

* tremor – shaking, which usually begins in the hand or arm and is more likely to occur when the limb is relaxed and resting
* slowness of movement (bradykinesia) – physical movements are much slower than normal, which can make everyday tasks difficult and result in a distinctive slow, shuffling walk with very small steps
* muscle stiffness (rigidity) – stiffness and tension in the muscles, which can make it difficult to move around and make facial expressions, and can result in painful muscle cramps (dystonia)
*balance problems – these can make someone with the condition more likely to have a fall and injure themselves
*problems sleeping (insomnia) – this can result in excessive sleepiness during the day

<img src="https://www.vanraam.com/getmedia/3078b293-12dd-4a5b-8bdf-028ee835bdcc/Cycling-with-Parkinson-s-disease-with-Van-Raam-special-needs-bicycles.png?width=500" width="800px">

# 2. Description of DataBase

#### OpenNeuro Dataset ds000245

This data was obtained from the OpenfMRI database. Its accession number is ds000245.

Images were nii and we converted them to png to fit the model.
Data contains 2 folders: healthy and Parkinson Patients.
Data folder is the main folder that contain all the step folders
inside Data folder are test , train , valid

test represent testing set

train represent training set

valid represent validation set

training set is 70%

testing set is 20%

validation set is 10%


* Hyposmia

Severe hyposmia is a risk factor of dementia in Parkinson’s disease (PD), while the underlying functional connectivity (FC) and brain volume alterations in PD patients with severe
hyposmia (PD-SH) are unclear.


#### Dataset link :

[Here](https://openneuro.org/datasets/ds000245/versions/00001)

# 3. Xception
# Xception is a deep convolutional neural network architecture that involves Depthwise Separable Convolutions.

https://iq.opengenus.org/xception-model/#:~:text=Xception%20is%20a%20deep%20convolutional,version%20of%20an%20Inception%20module.

* Xception is also known as “extreme” version of an Inception module. <br>
<img src = 'https://ars.els-cdn.com/content/image/1-s2.0-S2666285X21000583-gr6.jpg' width = 800px >
