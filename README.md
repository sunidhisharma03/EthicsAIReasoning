# AI Ethical Reasoning Project

## Abstract

This project introduces a novel swarm intelligence system designed to navigate complex ethical dilemmas by leveraging tiny Large Language Models (LLMs). We utilize TinyLlama-1.1B as a base model and implement Low-Rank Adaptation (LoRA) to fine-tune three independent, specialized agents grounded in distinct ethical frameworks: Deontology, Utilitarianism, and Virtue Ethics.

To facilitate this, we created a synthetic dataset of 1,000 ethical scenarios, each with tailored questions, binary answers (Yes/No), and corresponding explanations for each of the three ethical theories. The system processes a dilemma through each specialist agent, and a swarm-based voting mechanism aggregates their outputs to produce a final, synthesized decision.

This multi-agent approach demonstrates a robust and interpretable method for AI-driven ethical reasoning, highlighting the potential of small, efficient models in creating nuanced and ethically-aware systems.

**Keywords:** Swarm Intelligence, Tiny LLMs, TinyLlama-1.1B, Ethical AI, Deontology, Utilitarianism, Virtue Ethics, LoRA, Synthetic Data Generation

---

## Project Overview

The goal of this project is to build an AI system capable of reasoning about ethical dilemmas by combining insights from three classical ethical theories. Each ethical agent is fine-tuned to specialize in one framework, allowing the system to provide balanced and explainable decisions through swarm intelligence aggregation.

---

## Features

- Fine-tuned TinyLlama-1.1B models specialized for Deontology, Utilitarianism, and Virtue Ethics
- Synthetic dataset of 1,000 curated ethical dilemmas with annotated explanations
- Swarm voting mechanism to aggregate multiple ethical perspectives into a final decision
- Memory-efficient design suitable for limited hardware environments
- Explainable AI approach with detailed rationales for decisions

---

## Technologies Used

- Python 3.x
- TinyLlama-1.1B model
- Low-Rank Adaptation (LoRA)
- Transformers library (Hugging Face)
- Swarm Intelligence algorithms

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

For any questions or contributions, please reach out to the project maintainer.

---

