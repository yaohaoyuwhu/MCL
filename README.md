# Unsupervised Visible-Infrared Person Re-identification under Unpaired Settings
The official repository for Unsupervised Visible-Infrared Person Re-identification under Unpaired Settings (ICCV 2025).
## Our framework
<p align="center">
  <img src="https://github.com/user-attachments/assets/e61632e4-6c8d-489f-98e3-f023181daa77" width="600"/>
</p>

## Highlight
- We formally characterize the prevalent unpaired settings encountered in real-world scenarios and introduce the first public visible-infrared pedestrian benchmarks under such conditions. To our knowledge, this work marks the inaugural exploration of unsupervised scenarios featuring cross-modal identity mismatches.

- We propose a novel Mapping and Collaborative Learning (MCL) framework to address the problem of lacking cross-modality paired and labeled data under unpaired settings, establishing a kind of implicit cross-modality associations without paired supervision for learning modality-invariant representations. 

- We introduce a straightforward yet effective Cross-modality Feature Mapping (CFM) module that synthesizes positive feature pairs across modalities to achieve robust alignment. Building upon these synthesized pairs, a novel Static-Dynamic Collaborative (SDC) learning strategy is designed to mitigate cross-modality discrepancies at both the cluster and instance levels by leveraging complementary static and dynamic optimization.

- Extensive experiments on two benchmark datasets demonstrate that the proposed framework surpasses existing state-of-the-art USL-VI-ReID methods in unpaired settings, while maintaining competitive performance under paired scenarios.
