# Implementing Grad-Cam in Clip-ViL for VQA.

Heatmaps generated are essentially attention maps highlighting the important features that the CLIP-ViL model is taking into consideration for the given question.

For the question - What is next to the bottle? This is the generated image with the heatmap - [Heatmap](sample_all.pdf)

# Related Links

* [CLIP-ViL](https://github.com/clip-vil/CLIP-ViL)
* [CLIP](https://github.com/openai/clip)

# References
```
@article{shen2021much,
  title={How Much Can CLIP Benefit Vision-and-Language Tasks?},
  author={Shen, Sheng and Li, Liunian Harold and Tan, Hao and Bansal, Mohit and Rohrbach, Anna and Chang, Kai-Wei and Yao, Zhewei and Keutzer, Kurt},
  journal={arXiv preprint arXiv:2107.06383},
  year={2021}
}
```
