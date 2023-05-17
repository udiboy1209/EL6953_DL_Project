# Deep Learning Final Project

## Team

 - Sara Ghazanfari (sg7457)
 - Zeng Wang (zw3464)
 - Meet Udeshi (mdu2004)

## Abstract

In recent years there has been great progress in the classification of skin cancers based on their images. Recent methods are trying to tackle this problem using small-sized models having less than one million parameters. The state-of-the-art model for the HAM10000 dataset, FixCaps, implements a fixed capsule network with only 0.5M parameters and achieves 96.49\% accuracy. On the other hand, according to ongoing research in the area of adversarial machine learning, we know that deep neural networks are vulnerable to adversarial attacks, and specifically the less number of parameters and lower levels of expressivity can lead to severe performance decay when the model is exposed to adversarial examples. We propose to evaluate the robustness of the FixCaps model to adversarial samples to fool the classifier in the context of skin cancer detection. We will follow the approach of DARCCC to train a reconstruction model and detect adversarial images using high reconstruction error. Subsequently, we will try to break this detection strategy by performing two of the four adversarial attacks presented in, namely Boundary attack and Universal Adversarial Perturbations (UAP) along with two other extensively used attacks, Fast Gradient Sign Method (FGSM) and Projected Gradient Descent (PGD).

# Code

 - `FixCaps_Adversarial.ipynb`: Contains implementation of UAP and boundary attack.
