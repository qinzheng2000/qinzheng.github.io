---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a fifth-year Ph.D. candidate at the Institute of Artificial Intelligence and Robotics, Xi'an Jiaotong University, where I pursue my doctoral studies under the supervision of Prof.[Le Wang](https://gr.xjtu.edu.cn/web/lewang). I also collaborate closely with Prof.[Sanping Zhou](https://gr.xjtu.edu.cn/web/spzhou), Prof.[Gang Hua](https://www.ganghua.org/) and Prof.[Wei Tang](https://www.cs.uic.edu/~tangw/).

Previously, I received my B.Eng. degree in Robotics Engineering from Harbin Institute of Technology. I am currently a visiting Ph.D. student with the Multimedia and Human Understanding Group (MHUG) at the University of Trento, under the supervision of [Nicu Sebe](https://scholar.google.com/citations?user=stFCYOAAAAAJ&hl=en).




# 🔥 News {#news}
- *2025.10*: &nbsp;🎉🎉 One paper is accepted by AAAI 2026.
- *2025.07*: &nbsp;🎉🎉 One paper is accepted by ACM MM 2025.
- *2025.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2025.
- *2024.12*: &nbsp;🎉🎉 One paper is accepted by TMM.
- *2024.10*: &nbsp;🎉🎉 One paper is accepted by AAAI 2025.
- *2024.09*: &nbsp;🎉🎉 One paper is accepted by NIPS 2025.
- *2024.05*: &nbsp;🎉🎉 Two paper is accepted by TMM.
- *2024.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2024.
- *2023.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2023.

# 📖 Educations {#educations}
- *2025.09 - now*, Visiting Ph.D. student, Artificial Intelligence, University of Trento.
- *2021.09 - now*, Ph.D. student, Control Science and Engineering, Xi'an Jiaotong University. 
- *2017.09 - 2021.06*, B.S., Robotics Engineering, Harbin Institute of Technology


# 💻 Internships {#internships}
- *2025.03 - now*, Ant Group, Multimodal Interaction Team  |  Research Intern in Multimodal Large Models.
- *2024.05 - 2025.02*, Ant Group, Digital Human Algorithm Team  |  Research Intern in Digital Human Algorithms.
- *2022.05 - 2024.03*, University of Illinois Chicago, Prof. Wei Tang’s Research Group ｜ Research Intern in Computer Vision.


# 📝 Selected Publications {#selectedpublications}
<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Milti-model LLM</div>
    <img src='images/humansense.png' alt="SAMPO" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>HumanSense: From Multimodal Perception to Empathetic Context-Aware Responses through Reasoning MLLMs</h3>
    <div class="authors">
      <strong>Zheng Qin</strong>, Ruobing Zheng, Yabing Wang, Tianqi Li, Yi Yuan, Jingdong Chen, Le Wang
    </div>
    <div class="venue">AAAI26</div>
    <div class="links">
      <a href="https://digital-avatar.github.io/ai/HumanSense/" class="btn-accent">Project</a>
      <a href="https://arxiv.org/abs/2508.10576" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/antgroup/HumanSense" class="btn-accent"><i class="fab fa-github"></i> Code</a>
      <a href="https://huggingface.co/antgroup/HumanSense_Omni_Reasoning" class="btn-accent"> Huggingface</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Video Generation</div>
    <img src='images/verse.png' alt="SAMPO" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Versatile Multimodal Controls for Expressive Talking Human Animation</h3>
    <div class="authors">
      <strong>Zheng Qin</strong>, Ruobing Zheng, Yabing Wang, Tianqi Li, Zixin Zhu, Sanping Zhou, Ming Yang, Le Wang
    </div>
    <div class="venue">ACM MM25</div>
    <div class="links">
      <a href="https://digital-avatar.github.io/ai/VersaAnimator/" class="btn-accent">Project</a>
      <a href="https://arxiv.org/abs/2503.08714" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <!-- <a href="https://github.com/antgroup/HumanSense" class="btn-accent"><i class="fab fa-github"></i> Code</a> -->
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Multi-object Tracking</div>
    <img src='images/generaltrack.png' alt="SAMPO" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Towards generalizable multi-object tracking</h3>
    <div class="authors">
      <strong>Zheng Qin</strong>, Le Wang, Sanping Zhou, Panpan Fu, Gang Hua, Wei Tang
    </div>
    <div class="venue">CVPR24</div>
    <div class="links">
      <!-- <a href="https://digital-avatar.github.io/ai/VersaAnimator/" class="btn-accent">Project</a> -->
      <a href="https://arxiv.org/abs/2406.00429" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/qinzheng2000/GeneralTrack" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Multi-object Tracking</div>
    <img src='images/motiontrack.png' alt="SAMPO" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Motiontrack: Learning robust short-term and long-term motions for multi-object tracking</h3>
    <div class="authors">
      <strong>Zheng Qin</strong>, Sanping Zhou, Le Wang, Jinghai Duan, Gang Hua, Wei Tang
    </div>
    <div class="venue">CVPR23</div>
    <div class="links">
      <a href="https://www.youtube.com/watch?v=HaS9cM75J7Y" class="btn-accent">Video</a>
      <a href="https://arxiv.org/abs/2303.10404" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://www.youtube.com/shorts/CFmHsWB_Sus" class="btn-accent"><i class="fab fa-github"></i> Demo</a>
    </div>
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Visual Grounding</div>
    <img src='images/aaai25.png' alt="SAMPO" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>RefDetector: A Simple yet Effective Matching-based Method for Referring Expression Comprehension</h3>
    <div class="authors">
      Yabing Wang, Zhuotao Tian, <strong>Zheng Qin</strong>, Sanping Zhou, Le Wang
    </div>
    <div class="venue">AAAI25</div>
    <div class="links">
      <!-- <a href="https://www.youtube.com/watch?v=HaS9cM75J7Y" class="btn-accent">Video</a> -->
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/32866/35021" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <!-- <a href="https://www.youtube.com/shorts/CFmHsWB_Sus" class="btn-accent"><i class="fab fa-github"></i> Demo</a> -->
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Visual Grounding</div>
    <img src='images/nips24.png' alt="SAMPO" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Referencing Where to Focus: Improving Visual Grounding with Referential Query</h3>
    <div class="authors">
      Yabing Wang, Zhuotao Tian, Qingpei Guo, <strong>Zheng Qin</strong>, Sanping Zhou, Ming Yang, Le Wang
    </div>
    <div class="venue">NIPS24</div>
    <div class="links">
      <!-- <a href="https://www.youtube.com/watch?v=HaS9cM75J7Y" class="btn-accent">Video</a> -->
      <a href="https://arxiv.org/abs/2412.19155" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/LiJiaBei-7/RefFormer" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Embodied AI</div>
    <img src='images/cvpr25.png' alt="SAMPO" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Towards precise embodied dialogue localization via causality guided diffusion</h3>
    <div class="authors">
      Haoyu Wang, Le Wang, Sanping Zhou, Jingyi Tian, <strong>Zheng Qin</strong>, Yabing Wang, Gang Hua, Wei Tang
    </div>
    <div class="venue">CVPR25</div>
    <div class="links">
      <!-- <a href="https://www.youtube.com/watch?v=HaS9cM75J7Y" class="btn-accent">Video</a> -->
      <a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_Towards_Precise_Embodied_Dialogue_Localization_via_Causality_Guided_Diffusion_CVPR_2025_paper.pdf" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <!-- <a href="https://github.com/LiJiaBei-7/RefFormer" class="btn-accent"><i class="fab fa-github"></i> Code</a> -->
    </div>
  </div>
</div>

# Publications  {#publications}
- MotionTrack: Learning Robust Short-term and Long-term Motions for Multi-Object Tracking (CVPR 2023)  
  **Qin Z**, Zhou S, Wang L, Duan J, Hua G, Tang W.

- Towards Generalizable Multi-Object Tracking (CVPR 2024)  
  **Qin Z**, Wang L, Zhou S, Fu P, Hua G, Tang W.

- Referencing Where to Focus: Improving Visual Grounding with Referential Query (NeurIPS 2024)  
  Wang Y, Tian Z, Guo Q, **Qin Z**, Zhou S, Yang M, Wang L.

- RefDetector: A Simple yet Effective Matching-based Method for Referring Expression Comprehension (AAAI 2025)  
  Wang Y, Tian Z, **Qin Z**, Zhou S, Wang L.

- Towards Precise Embodied Dialogue Localization via Causality Guided Diffusion (CVPR 2025)  
  Wang H, Wang L, **Qin Z**, Wang Y, Hua G, Tang W.

- Versatile Multimodal Controls for Whole-Body Talking Human Animation (ACM MM 2025)  
  **Qin Z**, Zheng R, Wang Y, Li T, Zhu Z, Yang M, Yang M, Wang L.

- HumanSense: From Multimodal Perception to Empathetic Context-Aware Responses through Reasoning MLLMs (AAAI 2026)  
  **Qin Z**, Zheng R, Wang Y, Li T, Yuan Y, Chen J, Wang L.

- Single-Shot and Multi-Shot Feature Learning for Multi-Object Tracking (TMM 2024)  
  Li Y, Zhou S, **Qin Z**, Wang L, Wang J, Zheng N.

- Robust Noisy Label Learning via Two-Stream Sample Distillation (TMM 2025)  
  Bai S, Zhou S, **Qin Z**, Wang L, Zheng N.

- Semantic and Kinematics Guidance for RMOT (TMM 2025)  
  Li Y, Zhou S, **Qin Z**, Wang L.

- Injecting Position and Relation Prior for Dense Video Captioning (Submitted to TIP)  
  Li Y, Zhou S, **Qin Z**, Lin J, Sun X, Wu K, Wang L.

- From Mapping to Composing: A Two-Stage Framework for Zero-shot Composed Image Retrieval (Submitted to TCSVT)  
  Wang Y, Tian Z, Guo Q, **Qin Z**, Zhou S, Yang M, Wang L.

- Embracing Aleatoric Uncertainty: Generating Diverse 3D Human Motion (Submitted to TCSVT)  
  **Qin Z**, Wang L, Wang Y, Yang M, Rong C, Yang M, Zheng N.

- RSRNav: Reasoning Spatial Relationship for Image-Goal Navigation (Submitted to TCSVT)  
  **Qin Z**, Wang L, Wang Y, Zhou S, Hua G, Tang W.

- Spatial Matters: Position-Guided 3D Referring Expression Segmentation (Submitted to CVPR 2026)  
  Wang Y, Tian Z, Wang L, **Qin Z**, Zhou S.



# 🎖 Honors and Scholarships {#honors-and-scholarships}
- **National Scholarship (PhD)**, 2025  
- **Weichai Power Scholarship (PhD)**, 2025  
- **Outstanding Graduate Student (PhD)**, 2023, 2024  
- **First-Class Freshman Scholarship**, 2021  
- **Outstanding Graduate, Harbin Institute of Technology**, 2021  
- **First-Class Academic Scholarship**, 2018, 2019, 2020

# 💬 Invited Talks {#invited-talks}
- *2024.07*, Invited to present the paper GeneralTrack at the “Summer of the Institute of Human–Computer Interaction, XJTU”
- *2023.07*, Invited to present the paper MotionTrack at the “Summer of the Institute of Human–Computer Interaction, XJTU”
- *2023.06*, Invited to present the paper MotionTrack at the CVPR 2023 paper-sharing session hosted by Microsoft Research Asia (MSRA Asia).

# Services {#services}
Reviewer for CVPR, ICCV, ICML, ECCV, ICLR, NIPS, ACM MM, AAAI, TIP, TMM, PR, etc.


