# Radar Signal Identification: GCPS: A CNN Performance Evaluation Criterion for Intra-Pulse Modulation Identification of Radar Signals [with MATLAB Code]

Introduction: Internal modulation recognition of radar signals is one of the key technologies in electronic warfare for electronic intelligence. This technology can help us identify unknown radar signals and respond quickly. However, with the development of low-probability intercept (LPI) radars, the reliability of traditional identification methods relying on radar signal parameters has significantly decreased [2]. In recent years, due to the rapid development of deep learning, converting radar signals into images and using convolutional neural networks (CNN) for recognition has become a mainstream method [3].
With the continuous evolution of CNN structures, the recognition rate of internal modulation recognition of radar signals has also been continuously improved. Although increasing the number of layers can improve the recognition rate of CNNs, it is not easy to interpret and evaluate such a large CNN structure [4]. Currently, researchers mainly study the interpretation problem of CNNs from the perspective of feature visualization. Zhang Quanshi proposed a knowledge graph method to find the CNN's feature extraction areas by splitting the convolutional layer features. Through class activation maps (CAM) and gradient weighted CAM (Grad-CAM), users can understand how CNNs make recognition decisions more clearly. However, the performance evaluation of CNNs remains qualitative and intuitive, and precise quantitative mathematical tools have not yet been developed.
Therefore, the quantitative performance evaluation method of CNN performance in traditional optical image recognition (i.e., images containing items, people, handwriting, etc.) is a challenge [4]. The current strategy for radar signal internal modulation recognition is to only use existing CNN structures to recognize time-frequency images (TFI) of radar signals [3], without analyzing the reasons for changes in recognition rates. Therefore, it is necessary to evaluate the performance of CNNs in radar signal internal modulation recognition.
Although CNNs are difficult to describe directly through mathematical formulas, indirect quantitative assessment of CNN performance can be achieved by measuring the performance differences of different samples. Compared to conventional images, radar signal TFI features are shallower with complete and smooth boundaries, with distinct signals and no-signal areas. Considering these specific attributes, we can quickly obtain the position of radar signals and evaluate the performance of CNNs and quantify the impact of noise.
To achieve these goals, we propose Grad-CAM Positional Score (GCPS), which includes GCPS-Internal Benchmark (GCPS-IB) and GCPS-External Benchmark (GCPS-EB). This benchmark is based on uncorrupted Grad-CAM radar signal TFI. GCPS-IB and GCPS-EB respectively quantitatively assess the performance of CNNs in radar signal pulse modulation recognition and the impact of noise on CNN feature extraction. In addition, we use these metrics to evaluate existing GoogLeNet and ResNet-18 models, and the experimental results verify the effectiveness of our proposed standard.
Conclusion: In this letter, we propose GCPS, which includes GCPS-IB and GCPS-EB to evaluate CNN performance. We validate the performance of GCPS using five different modulation types of radar signals and two widely used CNNs. The results show that GCPS-IB does not saturate quickly, and its acquisition does not require a large test set. GCPS-EB can reveal the reasons why SNR affects recognition performance, rather than simply showing the relationship between SNR and CNN performance. Therefore, compared to recognition rate, GCPS can more comprehensively and accurately evaluate CNN performance.

## Images

![(Radar Signal Identification)GCPS: A CNN Performance Evaluation Criterion for Intra-Pulse Modulation Identification of Radar Signals [with MATLAB Code]](01.jpg)
![(Radar Signal Identification)GCPS: A CNN Performance Evaluation Criterion for Intra-Pulse Modulation Identification of Radar Signals [with MATLAB Code]](02.jpg)
![(Radar Signal Identification)GCPS: A CNN Performance Evaluation Criterion for Intra-Pulse Modulation Identification of Radar Signals [with MATLAB Code]](03.jpg)
![(Radar Signal Identification)GCPS: A CNN Performance Evaluation Criterion for Intra-Pulse Modulation Identification of Radar Signals [with MATLAB Code]](04.jpg)
![(Radar Signal Identification)GCPS: A CNN Performance Evaluation Criterion for Intra-Pulse Modulation Identification of Radar Signals [with MATLAB Code]](05.jpg)
![(Radar Signal Identification)GCPS: A CNN Performance Evaluation Criterion for Intra-Pulse Modulation Identification of Radar Signals [with MATLAB Code]](06.jpg)
![(Radar Signal Identification)GCPS: A CNN Performance Evaluation Criterion for Intra-Pulse Modulation Identification of Radar Signals [with MATLAB Code]](07.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
