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

I am an Associate Researcher and Master Supervisor at the [School of Computer Science and Technology](http://www.cs.ecnu.edu.cn/), [East China Normal University](https://english.ecnu.edu.cn/). 
I was selected for the Shanghai Youth Science and Technology Rising Star Program (上海市青年科技启明星扬帆专项) in 2023.
My research interests primarily focus on foundational issues in NLP and AI for medicine and education, such as Large Language Models, clinical NLP, and AI-assisted education. 
I completed my Ph.D. at the [Research Center for Social Computing and Information Retrieval (SCIR)](https://ir.hit.edu.cn/) in 2022, under the supervision of Professor [Wanxiang Che](http://ir.hit.edu.cn/~car/). 
Also, I had worked as a algorithm engineer intern at [Tencent Jarvis Lab](https://jarvislab.tencent.com/) during my Ph.D, under the supervision of [Yefeng Zheng](https://scholar.google.com/citations?user=vAIECxgAAAAJ&hl=en&oi=ao).
From 2022 to 2024, I was an associate researcher at [Shanghai AI Lab](https://www.shlab.org.cn/), working on the large language model for the medical domain.

# 💻 Work Experience
- *2024.05 - Present*, Associate Researcher, East China Normal University.
- *2022.10 - 2024.04*, Associate Researcher, Shanghai AI Lab.
- *2020.05 - 2021.05*, Algorithm Engineer Intern, Tencent.
- *2019.04 - 2019.09*, Algorithm Engineer Intern, Tencent.

# 📖 Educations
- *2016.09 - 2022.09*, Ph.D of Computer Science, Harbin Institute of Technology. 
- *2012.09 - 2016.06*, Bachelor of Mathematics, Harbin Institute of Technology. 

# 🎖 Honors and Awards
- *2023* Shanghai Youth Science and Technology Rising Star Program (上海市青年科技启明星扬帆专项), 2023.

# 💬 Invited Talks
- *2024.09*: 中国数字经济创新发展大会, ''AI时代算力的影响及智能教育的应用''.
- *2024.04*: The Hong Kong Polytechnic University, ''A Brief Introduction of Medical Dialogue System''. 

# 🔥 News
- *2024.05*: &nbsp;🎉🎉 One paper ''Medical Dialogue System: A Survey of Categories, Methods, Evaluation and Challenges'' is accepted by ACL 2024 findings.

# 📝 Publications 
1. **Medical Dialogue System: A Survey of Categories, Methods, Evaluation and Challenges.**    
   *Xiaoming Shi*, Zeming Liu, Li Du, Yuxuan Wang, Hongru Wang, Yuhang Guo, Tong Ruan, Jie Xu, and Shaoting Zhang.  
   In Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (ACL 2024) Findings. (CCF A)
   [[Paper](https://aclanthology.org/2024.findings-acl.167/)]
3. **MidMed: Towards Mixed-Type Dialogues for Medical Consultation.**  
   *Xiaoming Shi*, Zeming Liu, Chuan Wang, Haitao Leng, Kui Xue, Xiaofan Zhang, and Shaoting Zhang.
   In Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (ACL 2023). (CCF A) 
   [[Paper](https://aclanthology.org/2023.acl-long.453.pdf)]
   [[Resource](https://github.com/xmshi-trio/MidMed)]
4. **Understanding Medical Conversations with Scattered Keyword Attention and Weak Supervision from Responses.**  
   *Xiaoming Shi*, Haifeng Hu, Wanxiang Che, Zhongqian Sun, Ting Liu and Junzhou Huang.  
   In Proceedings of the Thirty-Fourth AAAI Conference on Artificial Intelligence (AAAI 2020). (CCF A) 
   [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/6412)]
   [[Code](https://github.com/xmshi-trio/MSL)]
5. **Understanding Patient Query with Weak Supervision from Doctor Response.**    
   *Xiaoming Shi*, Sendong Zhao, Wanxiang Che, Yefeng Zheng.  
   IEEE Journal of Biomedical and Health Informatics 26, no. 6 (2021): 2770-2777.  ()
   [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9645193)]
   [[Code](https://github.com/xmshi-trio/MSL)]
6. **Learning Semantic Alignment with Global Modality Reconstruction for VideoLanguage Pre-training towards Retrieval.**  
   Mingchao Li, *Xiaoming Shi*, Haitao Leng, Wei Zhou, Haitao Zheng, and Kuncai Zhang. (Co-first author) 
   In Proceedings of the Thirty-Seventh AAAI Conference on Artificial Intelligence (AAAI 2023).  
   [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25222)]
7. **Combating with Extremely Noisy Samples in Weakly Supervised Slot Filling for Automatic Diagnosis.**  
   *Xiaoming Shi*, and Wanxiang Che.  
   Frontiers of Computer Science 17, no. 5 (2023): 175333.  
   [[Paper](https://link.springer.com/article/10.1007/s11704-022-2134-1)]
8. **AF Adapter: Continual Pretraining for Building Chinese Biomedical Language Model.**  
   Yongyu Yan, Kui Xue, *Xiaoming Shi*, Qi Ye, Jingping Liu, and Tong Ruan.  
   In Proceedings of the IEEE International Conference on Bioinformatics and Biomedicine (BIBM 2023).  
   [[Paper](https://www.computer.org/csdl/proceedings-article/bibm/2023/10385733/1TObTklefWo)]
   [[Code](https://github.com/yanyongyu/AF-Adapter)]
9. **Online Action Detection with Learning Future Representations by Contrastive Learning**  
   Haitao Leng, *Xiaoming Shi*, Wei Zhou, Kuncai Zhang, Qiankun Shi, and Pengcheng Zhu.  
   In Proceedings of the IEEE International Conference on Multimedia and Expo 2023.  
   [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10220027)]
10. **MedBench: A Comprehensive, Standardized, and Reliable Benchmarking System for Evaluating Chinese Medical Large Language Models**  
   Mianxin Liu, Jinru Ding, Jie Xu, Weiguo Hu, Xiaoyang Li, Lifeng Zhu, Zhian Bai, *Xiaoming Shi*, Benyou Wang, Haitao Song, Pengfei Liu, Xiaofan Zhang, Shanshan Wang, Kang Li, Haofen Wang, Tong Ruan, Xuanjing Huang, Xin Sun, and Shaoting Zhang  
   Big Data Mining and Analytics, 2024.  
   [[Paper](https://www.sciopen.com/article/10.26599/BDMA.2024.9020044)]
11. **大语言模型安全性:分类、评估、归因、缓解、展望**
    李思霖, 兰天伟, 邱昱力, 单赢宇, *施晓明*, 柳泽明, 姚嘉树, 曾理, 郭宇航, 黄河燕
    计算机学报, 2024. (CCF A类中文科技期刊)
   
# 🧱 Patents
1. **一种语义识别方法、装置、计算机设备和存储介质**, CN112052318A.
2. **用于自动问答系统的分类模型训练、自动答答方法及装置**, CN112287089B.
3. **医学词语标注方法、医学词语映射方法、装置及设备**, CN112989767B.
4. **医学词语映射方法、装置、计算机设备及存储介质**, CN113761116A.
