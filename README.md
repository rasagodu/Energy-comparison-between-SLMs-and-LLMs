# Energy-Aware AI Inference for Data Centre Energy Management

A study of small and large language models, focusing on inference accuracy, latency, energy consumption, and efficient data centre operation.

## Overview

This project investigates how the choice of language model affects the computational efficiency and energy consumption of AI inference. It evaluates Natural Language Inference (NLI) using the Stanford Natural Language Inference (SNLI) dataset, comparing compact task-specific models with larger general-purpose language models.

The broader objective is to explore how energy-aware model selection and intelligent workload management can reduce the energy requirements of AI data centres.

## Topics Covered

- Natural Language Inference (NLI) and the SNLI dataset
- Small and large language models
- Model accuracy and inference latency
- Direct GPU power measurement and energy estimation
- Energy consumption per inference
- Confidence-based model routing
- Data centre energy management
- Battery dispatch and renewable energy integration

## Methodology

The initial stage evaluates language models on the same NLI task and measures their performance and energy consumption on real hardware.

The evaluation considers model quality, inference time, and GPU energy consumption across repeated trials.

## Project Roadmap

- **Stage 1:** Evaluate small and large language models and measure inference energy.
- **Stage 2:** Develop a confidence-based routing system that directs requests between small and large models.
- **Stage 3:** Model the data centre's grid connection, battery storage, electricity prices, and carbon signals.
- **Stage 4:** Explore joint optimization of model routing and battery dispatch.
- **Stage 5:** Evaluate the integrated system through data centre-scale simulation.

## Repository Contents

- `code/` — Model evaluation and experimental implementation
- `results/` — Accuracy, latency, and energy measurements
- `report/` — Project reports
- `presentation/` — Project presentations

## Tools and Technologies

Python, PyTorch, Hugging Face Transformers, Google Colab, and GPU energy measurement tools.

## Project Information

- **Course:** INSTR F376 — Design Project
- **Institution:** BITS Pilani, Hyderabad Campus
- **Supervisor:** Professor Pratyush Chakraborty

