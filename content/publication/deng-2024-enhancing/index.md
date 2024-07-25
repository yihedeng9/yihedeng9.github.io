---
title: Enhancing Large Vision Language Models with Self-Training on Image Comprehension
authors:
- admin_eq 
- Pan Lu* 
- Fan Yin
- Ziniu Hu
- Sheng Shen
- James Zou
- Kai-Wei Chang
- Wei Wang
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: '2024-05-30'
publishDate: '2024-05-30'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2405.19716*'

abstract: Large vision language models (LVLMs) integrate large language models (LLMs) with pre-trained vision encoders, thereby activating the perception capability of the model to understand image inputs for different queries and conduct subsequent reasoning. Improving this capability requires high-quality vision-language data, which is costly and labor-intensive to acquire. Self-training approaches have been effective in single-modal settings to alleviate the need for labeled data by leveraging model's own generation. However, effective self-training remains a challenge regarding the unique visual perception and reasoning capability of LVLMs. To address this, we introduce Self-Training on Image Comprehension (STIC), which emphasizes a self-training approach specifically for image comprehension. First, the model self-constructs a preference dataset for image descriptions using unlabeled images. Preferred responses are generated through a step-by-step prompt, while dis-preferred responses are generated from either corrupted images or misleading prompts. To further self-improve reasoning on the extracted visual information, we let the model reuse a small portion of existing instruction-tuning data and append its self-generated image descriptions to the prompts. We validate the effectiveness of STIC across seven different benchmarks, demonstrating substantial performance gains of 4.0% on average while using 70% less supervised fine-tuning data than the current method. Further studies investigate various components of STIC and highlight its potential to leverage vast quantities of unlabeled images for self-training. Code and data are made publicly available.

# Summary. An optional shortened abstract.
summary: We introduce STIC (Self-Training on Image Comprehension) that enhances the understanding and reasoning capabilities of LVLMs through self-generated data. Our experiments across seven benchmarks, including ScienceQA, TextVQA, ChartQA, LLaVA-Bench, MMBench, MM-Vet, and MathVista, demonstrate a notable average accuracy gain of 4.0% by self-training.   

tags:
- Large Language Models
- Self-training
- Multi-modal learning

links:
url_pdf: 'arxiv.org/abs/2405.19716'
url_code: 'https://github.com/yihedeng9/STIC'
url_dataset: 'https://huggingface.co/collections/STIC-LVLM/stic-data-6658e7f93aa5d4bb34ef140b'
url_project: 'https://stic-lvlm.github.io/'

# Display this page in the Featured widget?
featured: true


---
