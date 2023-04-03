# Graduation-project
Melanoma Skin Cancer Detection using Digital Image Processing and Artificial Neural Networks

---------------------------------------------------------------------------------------

Abstract:


Skin cancer is the uncontrolled growth of strange skin cells. It occurs when unrepaired DNA damages to skin cells triggers mutations, 
or genetic defects, that lead the skin cells to multiply readily and form malignant tumors. Image processing is a commonly used method for 
skin cancer detection from the appearance of affected area on the skin. Artificial Neural Network (ANN) is one of the important branches of 
Artificial Intelligence, which has been accepted as a brand new technology in computer science for image processing. Neural Networks are currently 
the area of interest in medicine, particularly in the fields of radiology, urology, cardiology, oncology, etc. 
Neural Network plays a vital role in an exceedingly call network. In this paper, a computerised method has been developed to make use of Neural 
Networks in the field of  medical image processing. The ultimate aim of this paper is to implement cost-effective emergency support systems, 
to process the medical images. It has been used to analyse Melanoma parameters Like Asymmetry, Border, Colour, Diameter, (ABCD), etc. 
which are calculated using MATLAB from skin cancer images intending to developing diagnostic algorithms that might improve triage practices 
in the emergency department. 
Using the ABCD rules for the melanoma skin cancer, we use ANN in classification stage with Back Propagation Algorithm. 
Initially, we train the network with known target values. The network is well trained with 96.9% accuracy, and then the unknown values 
are tested for the cancer classification. This classification method proves to be more efficient for the skin cancer classification.


 Prerequisites:
 
 MATLAB installed in the laptop
 
 Introduction :
 ------------------
 In skin health, diagnosis or diagnostics is the process of identifying a skin texture or problem by its signs, symptoms and the result of various diagnosis 
 procedures. 

The conclusion reached through this process is called a diagnosis. The diagnosis system is a system that can be used to analyze any problem by 
answering some questions that lead to a solution to the problem.
 
Skin cancer is a malignant tumor that grows in the skin cells and accounts for more than 50 percent of all cancers. 
In the US alone, more than 1 million Americans will be diagnosed in 2007 with non-melanoma skin cancer, and 59, 940 will be 
diagnosed with melanoma, according to the American Cancer Society. 

Fortunately, skin cancers (basal cell and squalors cell carcinoma, and malignant melanoma) are rare in children. 

Existing methodology:
-----------------------
Image Acquisition :
               Image acquisition Dermoscopic images are basically digital photographs/images of magnified skin lesion, taken with conventional camera equipped with special lens extension. The lens attached to the dermatoscope acts like a microscope magnifier with its own light source that illuminates the skin surface evenly.
    
       Image Preprocessing 
           Image pre-processing before analysis of any image set can take place, preprocessing should be performed on all the images. This process is applied in order to make sure that all the images are consistent in desired characteristic.

Segmentation Techniques: 
         Threshold Based Segmentation
         Clustering Techniques
         Edge Detection Based
Feature Extraction :

             Asymmetry Index :
                    Asymmetry Index is computed with the following equation:  AI=(A1+A2)/2Ar

            Border Irregularity :
               In order to calculate border irregularity, there are different measures such as:
             compactness index, fractal index, edge abruptness.

            Color Index :
              Color index is calculated by converting the input image to hsv image value by checking the
             presence of the following colors.

            Diameter :
               The diameter value is said to be 5 if the diameter of lesion is greater than 6mm.


TDS Calculation :

                Following formula is used 
                             TDS = 1.3A + 0.1B + 0.5C + 0.5D 
           If the TDS Index is less than 4.75, it is benign (noncancerous) skin lesion. If TDS Index is 
          greater than 4.75 and less than 5.45, it is suspicious case of skin lesion.
 
 
 
 Advantage: 
 
  Skin Cancer Detection System is the system to identify and recognize skin cancer symptoms and diagnose melanoma in early stages.The user can take early 
  prevention of their healthy. Skin Cancer Detection System will help save lots of doctor’s time and could help to diagnose more accurate.It also can 
  easily assess the future development of skin via dialysis today’s age of the skin and put forward the best characteristic skin cancer project to client.
  








 
