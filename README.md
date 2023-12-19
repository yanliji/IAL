# Independency Adversarial Learning (IAL)
The sound mixture separation is still challenging due to heavy sound overlapping and disturbance from noise. As sound overlapping always hinders accurate sound separation, we propose an Independency Adversarial Learning Cross-Modal Sound Separation (IAL) approach, where IAL employs adversarial learning to minimize the correlation of separated sound elements, exploring high sound independence. Cross-modal sound separation incorporates audio-visual consistent feature learning and interactive cross-attention learning to emphasize the semantic consistency among cross-modal features. Both audio-visual consistency and audio consistency are kept to guarantee accurate separation. The proposed approach is evaluated on MUSIC, VGGSound, and AudioSet. Extensive experiments certify that our approach outperforms existing ones in both supervised and unsupervised scenarios.

##  Summary of proposed approach
<div > 
<img src="https://github.com/yanliji/IAL/blob/main/Image/Framework1.png")
</div>
  
The proposed approach is majorly composed of two major parts, (a) the Cross-Modal Separation (CMS), and (b) Independency Adversarial Learning (IAL). 

##  Code explanation and training


##  Result Visualization
Separation results of audio spectrums in the AVE dataset. Visualization of separation results on AVE dataset. 
<div align=center> 
<img src="https://github.com/yanliji/IAL/blob/main/Image/AVESeparationResults.png" width="380" height="200" />
</div>


Visualization of separation results on MUSIC dataset. It exhibits the separation results of our approach under supervised and
unsupervised settings, and the results of Co-Separation (Gao et al. 2019).

![Mixture separation results.](https://github.com/yanliji/IAL/blob/main/Image/Supervised%20Separation%20Results%20(1).png)



## Citation

@inproceedings{lin2023IAL,
  title={Independence Adversarial Learning for Cross-Modal Sound Separation},  
  author={Zhenkai Lin and Yanli Ji and Yang Yang},
  booktitle={Proceedings of the 38th AAAI Conference on Artificial Intelligence},
  pages={1--1},
  year={2024}
}
