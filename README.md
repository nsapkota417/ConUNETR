# ConUNETR
A Conditional Transformer Network for 3D Micro-CT Embryonic Cartilage Segmentation

------

Abstract:
Studying the morphological development of cartilaginous and osseous structures is critical to the early detection of life-threatening skeletal dysmorphology. Embryonic cartilage undergoes rapid structural changes within hours, introducing biological variations and morphological shifts that limit the generalization of deep learning-based segmentation models that infer across multiple embryonic age groups. Obtaining individual models for each age group is expensive and less effective, while direct transfer (predicting an age unseen during training) suffers a potential performance drop due to morphological shifts. We propose a novel Transformer-based segmentation model with improved biological priors that better distills morphologically diverse information through conditional mechanisms. This enables a single model to accurately predict cartilage across multiple age groups. Experiments on the mice cartilage dataset show the superiority of our new model compared to other competitive segmentation models. Additional studies on a separate mice cartilage dataset with a distinct mutation show that our model generalizes well and effectively captures age-based cartilage morphology patterns

Full paper:
https://arxiv.org/pdf/2402.03695.pdf

** The code for the paper published in ISBI2024 will be published soon. E-mail the author (nsapkota@nd.edu), if you want access to the codebase for your immediate project. 

