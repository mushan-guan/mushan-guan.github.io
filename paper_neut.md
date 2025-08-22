---
layout: page
permalink: /paper_neut/index.html
title: Neutrophil
---



<br>

## Neutrophil

<br>

2025 Adv Sci. 王伊龙. Single-Cell Transcriptomes of Immune Cells from Multiple Compartments Redefine the Ontology of Myeloid Subtypes Post-Stroke

<img src="https://mushan-guan.github.io/paper_pic/Neutrophil/img9.png" style="zoom:60%;" >

这篇文章使用了永久性MCAO小鼠模型，测了造模后day1的脑、颅骨骨髓、股骨骨髓、外周血，除颅骨是对照一个样实验两个样之外，其他组织都是对照和实验各一个样，颅骨两个样的细胞数量不一致，其中一个样极有可能是后面补测的。

这篇文章一共7个主要发现，前两部分是总体细胞类型分析，内容包括[所有细胞类型UMAP，Marker基因气泡图，细胞比例（柱状图、饼图、雷达图），质控图，差异基因分析（颅骨vs股骨，MCAO vs Sham）]，其中发现中性粒细胞和单核巨噬细胞变化较大所以接下来重点研究。中间三部分是分析中性粒细胞，包括整合三个外部中性粒细胞数据（CCA整合UMAP，相关性分析，Marker基因气泡图，通路网络图）、中性粒细胞亚群分析（相关性分析、富集分析）、拟时序分析monocle2、palantir、scVelo，确定研究重点是Neut_Cd14亚群，接下来对Neut_Cd14进行流式统计和qPCR表达定量，整合测了脑膜的外部数据，pySENIC转录因子网络分析（转录因子表达热图、转录因子调控基因网络）。最后两部分分析小胶和单核巨噬，内容包括小胶、单核巨噬细胞亚群分析（UMAP，气泡图，细胞比例柱状图，富集分析），小胶、单核巨噬细胞拟时序分析（scVelo，PAGA），两个外部空转数据集验证细胞的时空分布，主要细胞类型间通讯分析

主要新发现是**Cd14阳性中性粒细胞**，重点说明这群细胞主要来源于颅骨骨髓，可能路径是颅骨-骨膜-脑组织（方法是拟时分析和整合外部数据、流式和qPCR验证，没有染色验证），详细说明这群细胞及其上游细胞的分化轨迹以及该亚群调控网络，大致阐明了这群细胞的时空分布。这个发现弥补了2024年那篇Nat Immunol卒中后中性粒细胞源源不断从外周血入脑的观点。

这篇文章做了颅骨，但没选TB作为分析对象，正文没有一个字提到TB只在最后讨论部分提及TB主要在卒中后期发挥作用所以不去研究，但不难看出其实是因为对照组组织内也存在很多TB甚至对照组颅骨的TB超过实验组。

<br>

------

2023 ***Nat Immunol***. *Marco Bacigaluppi*. Age-induced alterations of granulopoiesis  generate atypical neutrophils that aggravate  stroke pathology

在本研究中，我们探讨了**衰老相关免疫系统变化对卒中的影响**。在实验性脑卒中模型中，与年轻小鼠相比，老年小鼠在**缺血脑微循环中出现了更多中性粒细胞阻塞**，导致 **“无再灌注”（no-reflow）现象加剧和卒中结局更差**。

老年小鼠在卒中后展现出更显著的**粒细胞生成反应**，使血液中积累了以下几类**成熟和非典型不成熟中性粒细胞**：

- **CD101⁺CD62L^lo 成熟中性粒细胞**，
- **CD177^hiCD101^loCD62L^lo 不成熟中性粒细胞**，
- **CD177^loCD101^loCD62L^hi 不成熟中性粒细胞**。

这些中性粒细胞具有**更强的氧化应激、吞噬能力以及促凝特性**。

在老年小鼠中，由 **CD62L^lo 中性粒细胞产生的趋化因子CXCL3** 被发现是推动上述老化相关中性粒细胞发育及其致病性的关键因素。

此外，对**造血干细胞进行年轻化处理**可逆转老年相关的中性粒细胞生成异常，从而 **改善卒中预后**。

在老年缺血性脑卒中患者中，血液白细胞的**单细胞蛋白组谱分析**也识别出了与 **再灌注不良及功能结局不良相关的CD62L^lo中性粒细胞亚群**。

<img src="https://mushan-guan.github.io/paper_pic/Neutrophil/img5.png" style="zoom:60%;" >
