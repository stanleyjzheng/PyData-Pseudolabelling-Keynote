# A Guide to Pseudolabelling: How to get a Kaggle medal with only one model
## PyData Boston-Cambridge Dec. 2020

Talk now on YouTube: https://youtu.be/c8uWUOSGYUI

Notebook on Kaggle: https://www.kaggle.com/stanleyjzheng/exploring-pseudolabelling-schemes-pydata

### Me
[![](https://img.shields.io/badge/-Kaggle-20beff?style=flat-square&logo=Kaggle&logoColor=fff)](https://www.kaggle.com/stanleyjzheng)
[![](https://img.shields.io/badge/-Devpost-003e54?style=flat-square&logo=Devpost&logoColor=fff)](https://devpost.com/StanleyjZheng)

### References
\[1\] Babakhin, Y., Sanakoyeu, A., & Kitamura, H. (2019). Semi-supervised segmentation of salt bodies in seismic images using an ensemble of convolutional neural networks. ArXiv:1904.04445. [http://arxiv.org/abs/1904.04445](http://arxiv.org/abs/1904.04445)
- Paper describing the winning solution to the [Kaggle TGS Salt Identification Challenge](https://www.kaggle.com/c/tgs-salt-identification-challenge/leaderboard) including pseudolabelling
- Also see Yauhen Babakhin's at Kaggle Days titled [How to cook pseudo-labels](https://www.youtube.com/watch?v=SsnWM1xWDu4)

\[2\] Internet.org and Facebook (2013). A Focus on Efficiency. \[White paper\]. [Archived on webarchive.org](https://web.archive.org/web/20130920150247/https://fbcdn-dragon-a.akamaihd.net/hphotos-ak-ash3/851560_196423357203561_929747697_n.pdf)

\[3\] Li, Z., Ko, B., & Choi, H.-J. (2019). Naive semi-supervised deep learning using pseudo-label. Peer-to-Peer Networking and Applications, 12(5), 1358–1368. [https://doi.org/10.1007/s12083-018-0702-9](https://doi.org/10.1007/s12083-018-0702-9)
- Paper describing pretrain method for pseudolabelling as well as results from LSTM, CIFAR, MNIST. 

\[4\] Xie, Q., Luong, M.-T., Hovy, E., & Le, Q. V. (2020). Self-training with Noisy Student improves ImageNet classification. ArXiv:1911.04252 [Cs, Stat]. [http://arxiv.org/abs/1911.04252](http://arxiv.org/abs/1911.04252)

\[5\] Global Wheat competition: [https://www.kaggle.com/c/global-wheat-detection](https://www.kaggle.com/c/global-wheat-detection)
- GitHub repo with all code for performance presented in the talk: [https://github.com/stanleyjzheng/Global-Wheat](https://github.com/stanleyjzheng/Global-Wheat)

\[6\] The following are solutions from the mentioned competitions: [OpenVaccine 1st](https://www.kaggle.com/c/stanford-covid-vaccine/discussion/189620), [OpenVaccine 2nd](https://www.kaggle.com/c/stanford-covid-vaccine/discussion/189709), [OpenVaccine 3rd](https://www.kaggle.com/c/stanford-covid-vaccine/discussion/189574), [Tweet sentiment extraction 1st](https://www.kaggle.com/c/tweet-sentiment-extraction/discussion/159477), [TReNDS Neuroimaging 1st](https://www.kaggle.com/c/trends-assessment-prediction/discussion/163017), [Global Wheat 1st](https://www.kaggle.com/c/global-wheat-detection/discussion/172418), [LISH-MOA 2nd public](https://www.kaggle.com/c/lish-moa/discussion/200338), [LISH-MOA 5th](https://www.kaggle.com/c/lish-moa/discussion/200533), [TGS Salt Identification 1st](https://www.kaggle.com/c/tgs-salt-identification-challenge/discussion/69291)

\[7\] My notebook on pseudolabelling MNIST [https://www.kaggle.com/stanleyjzheng/exploring-pseudolabelling-schemes-pydata](https://www.kaggle.com/stanleyjzheng/exploring-pseudolabelling-schemes-pydata)
### Further reading
* [How to cook pseudo-labels (Kaggle Days)](https://www.youtube.com/watch?v=SsnWM1xWDu4)
* [Pseudo-Labeling and Confirmation Bias in Deep Semi-Supervised Learning](https://arxiv.org/pdf/1908.02983.pdf)
* [State of the art Pascal VOC using pseudolabels](https://arxiv.org/pdf/2006.06882v1.pdf)
* [Amazon uses pseudolabels to increase Alexa's performance](https://www.amazon.science/blog/pseudo-labels-negative-examples-help-alexa-match-skills-to-customer-requests)
* [Booking.com uses pseudolabels to enhance review translations](https://booking.ai/semi-supervised-learning-to-improve-translation-of-guest-reviews-a51ca0a0d6b3)
