# Facial-Emotion-Rank-Intensity
Assigning Ranks to Facial Emotions
Facial Emotion Recognition is very promising domain. Wide range of application of Facial Emotion Recognition (FER) gives scope for the researchers to continue research in this domain.  FER in wild is a challenging task rather than detecting emotion under lab controlled environment.  

AffectNet dataset is large dataset whose sample are very close to real-world scenerios.  
We have designed a model, trained the sample of CKPlus, JAFFE, KDEF and AffectNet datasets. 
The code provided in the above .py is complete code for model design, training testing on AffectNet dataset. Apart from classifying label intensity ranks like Minimal, Average and Strong are assinged to the correclty classified images using relevance scores.   
Relevance score are generated by using Layer-wise Relevance propogation (LRP) of eXplainble Artifical Intelligence (XAI).
