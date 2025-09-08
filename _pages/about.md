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

I'm now a final year Ph.D student at [ARISE Lab](http://ariselab.cse.cuhk.edu.hk/) in The Chinese University of Hong Kong, advised by [Prof.Michael R. Lyu](https://www.cse.cuhk.edu.hk/lyu/home). 

My research interests are mainly in quality assurance in software maintainance. Specifically, it's quality assurance for logging statements and code comments.



# 📝 Publications 
## Peer-reviewed
- 8.**[C05]** <span style="color:#337AB7">[**DSN'25**]</span> Cordial: Cross-row Failure Prediction Method Based on Bank-level Error Locality for HBMs

  Wenwei Gu, Jiazhen Gu, **Renyi Zhong**, Wenyu Zhang, Ming Li, and Michael R. Lyu

  The 55th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN) (<span style="color:#FC4E2A">CCF-B</span>), Industry track, Naples, Italy, June 2025

- 7.**[J03]** <span style="color:#337AB7">[**TOSEM'25**]</span> LogUpdater: Automated Detection and Repair of Specific Defects in Logging Statements

  **Renyi Zhong**, Yichen Li, Jinxi Kuang, Wenwei Gu, Yintong Huo, Michael R. Lyu
  
  ACM Transactions on Software Engineering and Methodology (TOSEM) (<span style="color:#FC4E2A">CCF-A</span>), Just Accepted [[PDF]](https://dl.acm.org/doi/10.1145/3731754)
- 6.**[C04]** <span style="color:#337AB7">[**FSE'25**]</span> L4: Diagnosing Large-scale LLM Training Failures via Automated Log Analysis

  Zhihan Jiang, Junjie Huang, Guangba Yu, Zhuangbin Chen, Yichen Li, **Renyi Zhong**, Cong Feng, Yongqiang Yang, Zengyin Yang, Michael R. Lyu

  The ACM International Conference on the Foundations of Software Engineering (FSE) (<span style="color:#FC4E2A">CCF-A</span>), Trondheim, Norway, June 2025
- 5.**[C03]** <span style="color:#337AB7">[**ICSE'25**]</span> Towards Quality Assurance of Natural Language in Code

  **Renyi Zhong**

  Doctoral Symposium in 47th International Conference on Software Engineering (ICSE-DS) (<span style="color:#FC4E2A">CCF-A</span>), Ottawa, Ontario, Canada, 2025
- 4.**[J02]** <span style="color:#337AB7">[**TSE'24**]</span> Exploring the Effectiveness of LLMs in Automated Logging Statement Generation: An Empirical Study

  Yichen Li, Yintong Huo, Zhihan Jiang, **Renyi Zhong**, Pinjia He, Yuxin Su, Lionel C. Briand and Michael R. Lyu

  IEEE Transactions on Software Engineering (TSE) (<span style="color:#FC4E2A">CCF-A</span>), 2024 [[PDF]](https://ieeexplore.ieee.org/document/10707668)
- 3.**[C02]** <span style="color:#337AB7">[**FSE'24**]</span> Go Static: Contextualized Logging Statement Generation

  Yichen Li, Yintong Huo, **Renyi Zhong**, Zhihan Jiang, Jinyang Liu, Junjie Huang, Jiazhen Gu, Pinjia He and Michael R. Lyu

  The ACM International Conference on the Foundations of Software Engineering (FSE) (<span style="color:#FC4E2A">CCF-A</span>), Porto de Galinhas, Brazil, July 2024 [[PDF]](https://dl.acm.org/doi/10.1145/3643754)
- 2.**[C01]** <span style="color:#337AB7">[**ICSE'24**]</span> Knowledge-aware Alert Aggregation in Large-scale Cloud Systems: a Hybrid Approach

  Jinxi Kuang, Jinyang Liu, Junjie Huang, **Renyi Zhong**, Jiazhen Gu, Lan Yu, Rui Tan, Zengyin Yang, Michael R Lyu

  International Conference on Software Engineering: Software Engineering in Practice (ICSE-SEIP) (<span style="color:#FC4E2A">CCF-A</span>), 2024 [[PDF]](https://dl.acm.org/doi/10.1145/3639477.3639745)
- 1.**[J01]** Automatic Trend Analysis of Mobile App Updates Based on App Changelogs

  **Renyi Zhong**, Chong Wang, Peng Liang, Zhong Luo

  Journal of Computer Research and Development (<span style="color:#FC4E2A">CCF-A</span>), 2021, 58(4) [[PDF]](https://crad.ict.ac.cn/en/article/doi/10.7544/issn1000-1239.2021.20200756)

## Preprint
- 4.**[P04]** CCISolver: End-to-End Detection and Repair of Method-Level Code-Comment Inconsistency

  **Renyi Zhong**, Yintong Huo, Wenwei Gu, Jinxi Kuang, Zhihan Jiang, Guangba Yu, Yichen Li, David Lo, Michael R Lyu

  Under review at IEEE Transactions on Software Engineering (TSE)

- 3.**[P03]** Larger Is Not Always Better: Exploring Small Open-source Language Models in Logging Statement Generation

  **Renyi Zhong**, Yichen Li, Guangba Yu, Wenwei Gu, Jinxi Kuang, Yintong Huo, Michael R Lyu

  Under review at ACM Transactions on Software Engineering and Methodology (TOSEM)
  
- 2.**[P02]** KPIRoot+: An Efficient Integrated Framework for Anomaly Detection and Root Cause Analysis in Large-Scale Cloud Systems

  Wenwei Gu, **Renyi Zhong**, Guangba Yu, Xinying Sun, Jinyang Liu, Yintong Huo, Zhuangbin Chen, Jianping Zhang, Jiazhen Gu, Yongqiang Yang, Michael R Lyu

  Under review at Empirical Software Engineering (EMSE)

- 1.**[P01]** Towards Imperceptible Adversarial Attacks for Time Series Classification with Local Perturbations and Frequency Analysis

  Wenwei Gu, **Renyi Zhong**, Jianping Zhang, Michael R Lyu

# 🎖 Honors and Awards
<!-- - *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- Hong Kong PhD Fellowship Scheme, University Grants Committee of Hong Kong. 2022
- Outstanding Graduates of Wuhan University. 2022
- National Scholarship, Ministry of Education of the P.R. China. 2020
- National Scholarship, Ministry of Education of the P.R. China. 2019

# Services
- Reviewers: ICSE'26@Shadow, ISSRE'25@ReSAISE
- Subreviewers: ICSE'25, ASE'25, ISSTA'25, ISSTA'24, FSE'24

# 📖 Educations
- 2022.08~now  Ph.D student, The Chinese University of Hong Kong
- 2018.09~2022.06 Bachelor degree, Wuhan University

# Teaching Assisstant

- 2022 Fall: CSCI1130A Introduction to Computing Using Java
- 2023 Spring: ENGG1110D Problem Solving By Programming
- 2023 Fall: CSCI3180 Principles of Programming Language
<!-- # 💻 Internships -->
