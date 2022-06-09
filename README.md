# Awesome Hierarchical Vision Transformers

[WIP] This repo provides paper list of hierarchical vision transformers.

## Overview

Hierarchical Vision Transformer consists of the following components:
**Patch embedding**, **Position encoding**, **Patch merging**, **Transformer block**.
In this list, attention types in transformer block and position encoding types are focused.


## List

| Model Name              |Paper Titile| |Attention|Position Encoding|
|:------------------------|:----|:----|:----|:----|
| ViT                     |An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale|ICLR'21|global|sinusoidal|
| HaloNet                 |Scaling Local Self-Attention for Parameter Efficient Visual Backbones|CVPR'21|overlapped window| |
| Swin Transformer        |Swin Transformer: Hierarchical Vision Transformer using Shifted Windows|ICCV'21|window + shifted window|rel pos|
| PVT                     |Pyramid Vision Transformer: A Versatile Backbone for Dense Prediction without Convolutions|ICCV'21|spatial reduction|abs pos|
| MViT                    |Multiscale Vision Transformers|ICCV'21|spatial reduction|abs pos|
| CvT                     |CvT: Introducing Convolutions to Vision Transformers|ICCV'21|spatial reduction|Conv in attention|
| Vision Longformer       |Multi-Scale Vision Longformer: A New Vision Transformer for High-Resolution Image Encoding|ICCV'21|window + global token|rel pos|
| CrossViT                |CrossViT: Cross-Attention Multi-Scale Vision Transformer for Image Classification|ICCV'21|global|abs pos|
| CeiT                    |Incorporating Convolution Designs into Visual Transformers|ICCV'21|global|abs pos|
| CoaT                    |Co-Scale Conv-Attentional Image Transformers|ICCV'21|factorized|CPE|
| ResT                    |ResT: An Efficient Transformer for Visual Recognition|NeurIPS'21|spatial reduction|CPE|
| Twins                   |Twins: Revisiting the Design of Spatial Attention in Vision Transformers|NeurIPS'21|window + spatial reduction|CPE|
| Focal Transformer       |Focal Self-attention for Local-Global Interactions in Vision Transformers|NeurIPS'21|window + spatial reduction|2D rel pos|
| CoAtNet                 |CoAtNet: Marrying Convolution and Attention for All Data Sizes|NeurIPS'21|global|2D rel pos|
| SegFormer               |SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers|NeurIPS'21|spatial reduction|Conv in FFN|
| TNT                     |Transformer in Transformer|NeurIPS'21|window + spatial reduction| |
| Shuffle Transformer     |Shuffle Transformer: Rethinking Spatial Shuffle for Vision Transformer|arXiv'21|window + shuffle| |
| CMT                     |CMT: Convolutional Neural Networks Meet Vision Transformers|arXiv'21|spatial reduction|CPE|
| NesT                    |Nested Hierarchical Transformer: Towards Accurate, Data-Efficient and Interpretable Visual Understanding|AAAI'22|window|abs pos|
| CrossFormer             |CrossFormer: A Versatile Vision Transformer Hinging on Cross-scale Attention|ICLR'22|window + shuffle| |
| RegionViT               |RegionViT: Regional-to-Local Attention for Vision Transformers|ICLR'22|window + regional token| |
| PoolFormer / MetaFormer |MetaFormer is Actually What You Need for Vision|CVPR’22|pool| |
| CSWin Transformer       |A General Vision Transformer Backbone with Cross-Shaped Windows|CVPR’22|cross-shaped window| |
| Swin Transformer V2     |Swin Transformer V2: Scaling Up Capacity and Resolution|CVPR’22|window + shifted window| |
| MViTv2                  | MViTv2: Improved Multiscale Vision Transformers for Classification and Detection |CVPR'22|spatial reduction| |
| Shunted Transformer     | Shunted Self-Attention via Multi-Scale Token Aggregation                          |CVPR'22|spatial reduction| |
| Mobile-Former           |Mobile-Former: Bridging MobileNet and Transformer|CVPR'22|global token| |
| Lite Vision Transformer |Lite Vision Transformer with Enhanced Self-Attention|CVPR'22|conv attention| |
| PVTv2                   |Improved Baselines with Pyramid Vision Transformer|CVMJ'22|spatial reduction| |
