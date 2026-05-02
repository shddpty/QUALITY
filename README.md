# QUALITY
Code for paper: [Quality-aware and Soft Consistency Driven Representation Fusion for Incomplete Multi-view Multi-label Classification](https://ojs.aaai.org/index.php/AAAI/article/view/39564)
Pascal07 data is prepared for a demo, you can download data from [here](https://drive.google.com/drive/folders/1cixudQjQ1I1pvRFy0Srsl2UTgvzv-o2k?usp=drive_link).
You can run 'python main.py' for a demo!

## Abstract
Multi-view multi-label classification aims to utilize the rich information contained in multiple views for accurate classification. However, in real-world applications, its performance is often severely constrained by the concurrent missingness of both views and labels. To address this problem, this paper first targets the drawback of representation degradation in traditional feature disentanglement methods caused by strong consistency constraints and proposes a soft consistency constraint. This constraint not only effectively aligns the shared information and maximally avoids the compression of information beneficial to the classification task, but it also enhances the aggregation effect of high-quality representations on other representations. Furthermore, to address the coarse-grained problem of traditional fusion strategies, we designed a quality assessment network that achieves instance-level dynamic weighted fusion in a data-driven manner. Extensive experiments on multiple benchmark datasets demonstrate that our method achieves state-of-the-art performance in both incomplete and complete data scenarios, showcasing its robustness and generality.

## Overview of QUALITY
<img width="3120" height="1452" alt="architecture" src="https://github.com/user-attachments/assets/5270152f-6a16-4c5c-a1ff-ad8f740c96ca" />


## Environment
Please run the following command in the shell, as specified in `requirements.txt`:
```bash
conda create -n COME
conda activate COME
pip install -r requirements.txt
```
## Citation
If you find this work useful, please consider citing it:
```
@inproceedings{wen2025learning,
  title={Learning Compact Semantic Information for Incomplete Multi-View Missing Multi-Label Classification},
  author={Wen, Jie and Liu, Yadong and Tang, Zhanyan and He, Yuting and Chen, Yulong and Li, Mu and Liu, Chengliang},
  booktitle={International Conference on Machine Learning},
  pages={66467--66480},
  year={2025},
  organization={PMLR}
}
```
