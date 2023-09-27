<h1 align="center">DADA++: Dual Alignment Domain Adaptation for Unsupervised Video-Text Retrieval</h1>
<p align="center">
<a href=""><img  src="https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg" ></a>
<h4 align="center">This is the official repository of the paper <a href="">DADA++: Dual Alignment Domain Adaptation for Unsupervised Video-Text Retrieval</a>.</h4>
<h5 align="center"><em>Xiaoshuai Hao, Haimei Zhao, Hui Zhang, Wanqian Zhang, and Jing Zhang</em></h5>
<p align="center">
  <a href="#news">News</a> |
  <a href="#abstract">Abstract</a> |
  <a href="#method">Method</a> |
  <a href="#results">Results</a> |
  <a href="#preparation">Preparation</a> |
  <a href="#code">Code</a> |
  <a href="#statement">Statement</a>
</p>

## News

- **(2023/9/27)** DADA++ is coming.

## Abstract

Video-text retrieval aims at returning the most semantically relevant videos given a textual query, which is a thriving topic in both computer vision and natural language processing communities. This paper focuses on a more challenging task, i.e., Unsupervised Domain Adaptation Video-text Retrieval (UDAVR), wherein training and testing data come from different distributions. Previous approaches are mostly derived from classification-based domain adaptation methods, which are neither multi-modal nor suitable for retrieval tasks. They merely alleviate the domain shift while overlooking the _pairwise misalignment_ issue in the target domain, i.e., there exist no semantic relationships between target videos and texts. To tackle this, we propose a novel method named **D**ual **A**lignment **D**omain **A**daptation (**DADA++**). Specifically, we first introduce cross-modal semantic embedding to generate discriminative source features in a joint embedding space. Besides, we utilize the cross-modal domain adaptations to balance the minimization of domain shift in a smooth manner. Furthermore, we empirically identify the pairwise misalignment in the target domain, and thus propose the **i**ntegrated **D**ual **A**lignment **C**onsistency (**iDAC**). The proposed iDAC adaptively aligns the video-text pairs, which are more likely to be relevant in the target domain, by verifying their cross-modal semantic proximity reciprocally in both hard and soft manners. This enables that positive pairs are increasing progressively and the noisy ones will potentially be aligned in the whole training procedure. We also provide insights into the function of DADA++ through the lens of domain adaptation, explaining its superiority in a theoretical way. Compared with state-of-the-art methods, DADA++ achieves 9.4% and 8.5% relative improvements on R@1 under the setting of TGIF→MSR-VTT and TGIF→MSVD respectively, demonstrating its superior performance.

## Method

![the framework figure](./figs/framework.jpg "framework")
## Results
![the result figure](./figs/result.jpg "results")
### Quantitative results on Nuscenes validation set
![quantitative figure](./figs/quantitative.jpg "quantitative-results")

## Preparation

### Prerequisites

### Data Preparation

## Code
### Codes coming soon...

## Statement

