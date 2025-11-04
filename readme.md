


<p align="center">
  
  <h3 align="center"><strong>Open-Vocabulary 3D Affordance Understanding via Functional Text Enhancement and Multilevel Representation Alignment</strong></h3>

  <p align="center">
      <a href="https://wulin97.github.io/" target='_blank'>Lin Wu</a>&nbsp;&nbsp;&nbsp;
      <a href="" target='_blank'>Wei Wei</a>&nbsp;&nbsp;&nbsp;
      <a href="" target='_blank'>Peizhuo Yu</a>&nbsp;&nbsp;&nbsp;
      <a href="https://scholar.google.co.uk/citations?user=Z7kvat4AAAAJ&hl=en">Jianglin Lan*</a>&nbsp;&nbsp;&nbsp;
    </br>
  James Watt School of Engineering, University of Glasgow&nbsp;&nbsp;&nbsp;
  </p>

</p>


<p align="center">
  <a href="https://dl.acm.org/doi/10.1145/3746027.3755239" target='_blank'>
    <img src="https://img.shields.io/badge/Paper-%F0%9F%93%83-lightblue">
  </a>
  <a href="https://wulin97.github.io/aff3dfunc/" target='_blank'>
    <img src="https://img.shields.io/badge/Project-%F0%9F%94%97-blue">
  </a>
  <a href="https://github.com/wulin97/Awesome-Affordance-Dataset" target='_blank'>
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
  </a>
  <!-- <a href="" target="_blank">
    <img src="https://img.shields.io/badge/Dataset-%20Hugging%20Face-yellow">
  </a> -->
</p>

## 🛠️ About

Understanding 3D affordance is essential for agents to interact effectively with real-world environments. We propose Aff3DFunc, a framework that enhances the alignment between 3D geometry and affordance semantics. It integrates an Information Bottleneck–based text enhancement module to refine functional descriptions and a multilevel alignment strategy to bridge language–geometry representations. Extensive experiments and real-world robot tests demonstrate that Aff3DFunc achieves superior generalization and fine-grained affordance understanding.

<div style="text-align: center;">
    <img src="imgs/framework.png" alt="framework" style="max-width: 100%; height: auto; width: 1000px;">
</div>



## 🎞️ Visualization

We conduct zero-shot experiments on existing datasets under two textual query forms: *Label-as-Query* ([OpenAD](https://openad2023.github.io/)) and *Question-as-Query* ([LASO](https://github.com/yl3800/laso)). The corresponding visualization results for both settings are shown below.

<div style="text-align: center;">
    <img src="imgs/vis.gif" alt="vis" style="max-width: 100%; height: auto; width: 1000px;">
</div>

## 📚Citation
If you find this work helpful, please kindly consider citing our paper:
```bibtex
@InProceedings{Wu_2025_ACMMM,
    author    = {Lin Wu, Wei Wei, Peizhuo Yu, Jianglin Lan},
    title     = {Open-Vocabulary 3D Affordance Understanding via Functional Text Enhancement and Multilevel Representation Alignment},
    booktitle = {Proceedings of the 33nd ACM International Conference on Multimedia},
    month     = {October},
    year      = {2025},
    pages     = {7988-7997}
}
```