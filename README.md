# Architectures of Trust: A Critical Evaluation of AI Alignment Paradigms and Constitutional AI

**Author:** Ayushkumar Manvar  
**Date:** June 2026  

---

## 📄 Abstract
The rapid advancement of large language models (LLMs) and the pursuit of artificial general intelligence (AGI) have intensified the AI alignment problem: ensuring that increasingly capable systems
reliably pursue objectives that correspond with human values. This paper provides a comprehensive
technical analysis of contemporary AI safety paradigms, examining the theoretical foundations of
the alignment problem, the evolution of preference optimization techniques, and the operational mechanics of Constitutional AI (CAI). We decompose both outer alignment failures including reward
hacking, specification gaming, and objective compression and inner alignment failures, focusing on
the mathematical formalization of mesa-optimization and deceptive alignment. Through a critical
evaluation of Reinforcement Learning from Human Feedback (RLHF), Reinforcement Learning from
AI Feedback (RLAIF), and Direct Preference Optimization (DPO), we identify persistent scalability bottlenecks, objective instabilities, and behavioral tensions inherent in human-reliant oversight.
Constitutional AI is presented as a transformative framework that leverages formal constraint sets
and self-critique pipelines to align models with minimal human labeling. We further critically assess
persistent socio-technical vulnerabilities, including gradient-based adversarial attacks such as the
Greedy Coordinate Gradient (GCG), the exploitation of latent refusal directions via representation
engineering, and the cultural biases embedded in constitutional framing. Through an examination
of scalable oversight mechanisms including AI Safety via Debate and Weak-to-Strong Generalization we outline the theoretical limits and structural requirements for robustly aligning future frontier models. This paper contributes a unified framework for understanding alignment paradigms, a
critical synthesis of their limitations, and a research agenda for developing verifiably safe AI systems.

## 📥 Download Full Paper
You can read the full formatted research paper here: **[Download PDF](./MAIN.pdf)**

## 🔑 Key Topics Covered
* Outer Alignment (Reward Hacking & Specification Gaming)
* Inner Alignment (Mesa-Optimization & Deceptive Alignment)
* Constitutional AI (CAI) & RLAIF
* Direct Preference Optimization (DPO)
* Technical Vulnerabilities (GCG Attacks, Representation Engineering)

## 📑 Citation
If you find this research useful, please cite it as:
```bibtex
@article{manvar2026architectures,
  title={Architectures of Trust: A Critical Evaluation of AI Alignment Paradigms and Constitutional AI},
  author={Manvar, Ayushkumar},
  year={2026}
}
