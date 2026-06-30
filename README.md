# One Style Fits All? Cultural Values Embedded in Conversational AI via a People-Pleasing Lens

**ACL 2026 · C3NLP Workshop**

[![Website](https://img.shields.io/badge/Introduction-Website-blue)](https://osfa2026.netlify.app)
[![GitHub](https://img.shields.io/badge/Repository-GitHub-black)](https://github.com/yjchen0722/OSFA)
[![Paper](https://img.shields.io/badge/Paper-C3NLP%202026-red)](https://c3nlp.github.io/#accept_papers)

---

## Overview

This repository contains the experimental materials and analysis code for a cross-cultural study examining how chatbot interaction styles (supportive vs. challenging) are perceived differently across Taiwan and Korean.

---

## Repo Structure

```
├── materials/
│   ├── bot_prompts.py          # System prompts for supportive and challenging chatbot conditions
│   ├── task_prompts.py         # Three-stage tourism planning task prompts (Taiwan Mandarin & Korean)
│   ├── questionnaire_config.py # Pre- and post-interaction survey items (People-Pleasing Scale, Perceived Threat, Satisfaction, Trust, Continuance Intention, and Open-ended questions)
│   └── statistics.ipynb        # Statistical analysis: OLS regression, interaction effects
└── README.md
```

---

## Study Design

Participants completed a three-stage collaborative tourism planning task with a chatbot assigned to either a **supportive** or **challenging** interaction style. Pre-task measures included demographics and people-pleasing tendency (PPT); post-task measures included perceived threat, satisfaction, trust, and continuance intention.

- **Samples:** Taiwan (N=49) and Korea (N=52)
- **Chatbot styles:** Supportive (Style B) vs. Challenging (Style A)
- **AI-collaborative Task:** Three-stage tourism planning task (destination recall → itinerary planning → promotional copy)

---

## Data

Participant data is not included in this repository to protect participant privacy.

---

## License

[![License](https://img.shields.io/badge/License-CC%20BY%204.0-E8A33D)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the materials for any purpose, provided appropriate credit is given to the original authors.


## Citation

If you use our materials in your work, please cite the following:

```bibtex
@inproceedings{chen2026osfa,
  title     = {One Style Fits All? Cultural Values Embedded in Conversational AI via a People-Pleasing Lens},
  author    = {Chen, Yi-Jun and Hsieh, I-Tsen and Chang, Li-Wun},
  booktitle = {Proceedings of the 4th Workshop on Cross-Cultural Considerations in NLP (C3NLP 2026)},
  year      = {2026}
}
```
