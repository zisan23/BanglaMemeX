# BanglaMemeX: Advancing Cultural Metaphoric Image Interpretation in Bangla with a Multimodal Explainable Dataset

[![Paper](https://img.shields.io/badge/Paper-ACL%20Anthology-red)](https://aclanthology.org/2026.findings-emnlp.827/)
[![PDF](https://img.shields.io/badge/PDF-download-blue)](https://aclanthology.org/2026.findings-emnlp.827.pdf)
[![Venue](https://img.shields.io/badge/Findings%20of%20EMNLP-2026-green)](https://aclanthology.org/2026.findings-emnlp.827/)

Official repository for the paper **"BanglaMemeX: Advancing Cultural Metaphoric Image Interpretation in Bangla with a Multimodal Explainable Dataset"**, published in *Findings of the Association for Computational Linguistics: EMNLP 2026*, pages 17525-17561.

- Paper page: https://aclanthology.org/2026.findings-emnlp.827/
- PDF (ACL Anthology): https://aclanthology.org/2026.findings-emnlp.827.pdf
- PDF (this repo): [BanglaMemeX_Findings-EMNLP-2026.pdf](BanglaMemeX_Findings-EMNLP-2026.pdf)

## Authors

| Author | Affiliation |
|---|---|
| Md. Sadman Sakib* | University of Dhaka |
| Zisan Mahmud* | University of Dhaka |
| Md. Fahim Arefin | University of Dhaka |
| Md Fahim | University of Texas at Dallas |

\*Equal contribution.

## Abstract

Vision Language Models have achieved strong performance on multimodal benchmarks, yet their ability to reason about culturally grounded and metaphor-rich content remains insufficiently studied. Internet memes present a challenging setting where meaning emerges from implicit interactions between image, overlaid text, sarcasm, and shared socio-cultural knowledge rather than literal visual recognition. This challenge is amplified in low-resource languages such as Bangla, where code-mixing, stylized scripts, and culturally specific symbolism introduce substantial distribution shift.

In this work, we introduce **BanglaMemeX**, a culturally grounded multimodal benchmark comprising **3,000 Bangla memes** annotated with multi-dimensional labels (humor, sarcasm, offensiveness, motivational intent, and overall sentiment) and human-written explanations that explicitly describe textual and visual metaphors. We systematically evaluate modern VLMs on both classification and explanation generation, revealing that current models struggle to interpret implicit cultural cues despite reasonable surface-level accuracy. Our results highlight the need for culturally-aware multimodal systems capable of grounded reasoning under linguistic and cultural distribution shift.

## Highlights

- **3,000 Bangla memes** with labels for humor, sarcasm, offensiveness, motivational intent, and overall sentiment.
- **Human-written explanations** describing the textual and visual metaphors in each meme, enabling evaluation beyond classification accuracy.
- **Systematic VLM evaluation**: zero-shot prompting, chain-of-thought reasoning, LoRA-based parameter-efficient fine-tuning, and a structured LLM Council prompting setup for explanation generation.
- **Explanation quality** measured with BERTScore and an LLM-as-a-judge evaluation.

## Citation

If you use this work, please cite it:

```bibtex
@inproceedings{sakib-etal-2026-banglamemex,
    title = "{B}angla{M}eme{X}: Advancing Cultural Metaphoric Image Interpretation in {B}angla with a Multimodal Explainable Dataset",
    author = "Sakib, Md. Sadman and Mahmud, Zisan and Arefin, Md. Fahim and Fahim, Md",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2026",
    month = oct,
    year = "2026",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.findings-emnlp.827/",
    pages = "17525--17561",
}
```

The official BibTeX is also available on the [ACL Anthology page](https://aclanthology.org/2026.findings-emnlp.827/); prefer it if it differs from the above. A [`CITATION.cff`](CITATION.cff) file is included so GitHub shows a "Cite this repository" button.

## Keywords

Bangla memes, multimodal dataset, vision-language models, VLM, metaphor interpretation, cultural understanding, explainable AI, sarcasm detection, humor detection, offensive content, sentiment analysis, low-resource languages, Bengali NLP, EMNLP 2026.

## Contact

- Correspondence (as listed in the paper): ssadman887[at]gmail.com
- Zisan Mahmud, University of Dhaka: zisan23.github.io

For questions about the paper, the dataset, or collaboration, please email us or open a GitHub issue.

## Copyright and license

The paper is © 2026 Association for Computational Linguistics. ACL Anthology papers are generally made available under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/); please check the [Anthology page](https://aclanthology.org/2026.findings-emnlp.827/) for the terms that apply to this paper.
