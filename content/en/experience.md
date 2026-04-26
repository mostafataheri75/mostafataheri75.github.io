---
title: "Experience"
type: "homepage"
intro: >-
  From structural engineering to AI development, building practical tools that bridge traditional engineering with modern technology.

resume_downloads:
  - lang: en
    label: English
  

positions:

  - company: "Inria / ENS de Lyon"
    company_url: "https://www.inria.fr/en" 
    role: "Lead Researcher (AI for Mathematical Reasoning)"
    period: "2025 - Present"
    industry: "Neuro-symbolic AI & Quantum Optimization"
    location: "Lyon - France"
    company_description: "Pioneering the use of Large Language Models and Graph Neural Networks to automate complex mathematical proofs."
    bullet_points:
      - "Designed and trained Graph Neural Networks (GCN, GAT, GraphSAGE) using PyTorch Geometric to identify hidden cancellation structures in polynomial graphs, significantly reducing the search space for Sum-of-Squares certificates."
      - "Implemented 'FunSearch' (Function Search), an evolutionary algorithm powered by Large Language Models (LLMs), to autonomously write and refine Python code for generating optimization ansatzes."
      - "Deployed high-throughput LLM inference pipelines using vLLM on NVIDIA A100 GPUs, integrating models like Qwen and Mistral into the ShinkaEvolve framework for real-time code evolution."
      - "Engineered a high-performance verification pipeline using the MOSEK solver to benchmark generated proofs, achieving up to 1000x speedups in solving Semidefinite Programs (SDP) for quantum separability problems."
      - "Demonstrated that AI-discovered heuristics could outperform human-designed decompositions for Entanglement Witness problems, successfully scaling certification to regimes previously intractable for standard solvers."
      - "Architected the supporting platform as eight containerized services (Python + Julia) on Docker Swarm, with RabbitMQ messaging, PostgreSQL deduplication via SHA-256 content addressing, and a LiteLLM proxy unifying self-hosted vLLM and external APIs."
  - company: "Quantum Information Theory Group (ENS de Lyon)"
    company_url: "https://github.com/mostafataheri75/structure-of-the-peripheral-subspace"
    role: "Lead Researcher & Algorithm Developer"
    period: "2023 - 2025"
    industry: "Quantum Computing & Information Theory"
    location: "Lyon, France"
    company_description: "Research on the fundamental limits of information storage in quantum systems, presented at QIP 2025."
    bullet_points:
      - "Proved that for arbitrarily large times, classical and quantum capacities of Markovian noise are determined by efficiently computable properties of the channel's peripheral spectrum."
      - "Demonstrated that these infinite-time capacities are additive under tensor product, establishing that one-shot and asymptotic i.i.d. capacities are identical in this limit."
      - "Designed and implemented a polynomial-time algorithm in Julia to compute the peripheral subspace structure, achieving up to a 10x speedup over previous methods in benchmarks."
      - "Established that infinite-time capacity characterization avoids the computational hardness (e.g., NP-hard problems) associated with fixed-time Shannon theory capacities."
      - "Extended the theoretical framework to infinite-dimensional Hilbert spaces, enabling the modeling of continuous variable systems and engineered setups like cat qubits."

  - company: "Quantum Information Group (SUT / UESTC)"
    company_url: "http://vahidkarimipour.com/"
    role: "Quantum Research Assistant"
    period: "[Start Date] – [End Date]"
    industry: "Quantum Computing & Information Theory"
    location: "Tehran - Iran / Chengdu - China"
    company_description: "Focused on developing hybrid quantum-classical algorithms for Noisy Intermediate-Scale Quantum (NISQ) devices."
    bullet_points:
      - "Designed and implemented a Variational Quantum Eigensolver (VQE) framework using Qiskit and PennyLane to simulate the 2D Heisenberg Hamiltonian on NISQ-era hardware."
      - "Developed hybrid quantum-classical workflows to optimize parameterized quantum circuits (ansatz), significantly reducing the computational overhead of state preparation."
      - "Collaborated with Prof. Vahid Karimipour and Prof. Abolfazl Bayat to investigate quantum supremacy candidates in many-body physics through variational methods."
      - "Evaluated the performance of different circuit architectures and classical optimizers to mitigate noise and improve the fidelity of ground-state energy estimations."
      - "Benchmarked variational eigenstates against classical exact diagonalization to quantify the accuracy and scalability of the quantum simulation in a 2-dimensional lattice."
  - company: "University of Tehran / TU Eindhoven"
    company_url: "https://www.tue.nl/en/"
    role: "Research Assistant (Deep Learning & Physics)"
    period: "[2017] – [2018]"
    industry: "AI & Computational Physics"
    location: "Remote / Tehran - Iran"
    company_description: "Research focused on the intersection of fluid dynamics and machine learning to predict complex material behaviors."
    bullet_points:
      - "Developed and trained Deep Learning models using Keras and TensorFlow to predict the non-linear dynamics and wetness levels of granular materials within a rotating sphere."
      - "Engineered data processing pipelines to translate raw dynamical observations and physical behaviors into feature sets suitable for neural network training."
      - "Implemented regression and classification architectures to identify phase transitions and saturation states based on real-time system observations."
      - "Collaborated with Dr. Seyed Mehdi Vaez Allaei and Dr. Alessandro Corbetta to validate AI-driven predictions against empirical physical models and experimental data."
      - "Explored the use of computer vision and time-series analysis to capture and forecast the evolution of granular flow patterns in constrained environments."
  - company: "University of Tehran"
    company_url: "https://link.springer.com/article/10.1007/s10035-021-01115-4"
    role: "Bachelor Research Assistant (Computational Physics)"
    period: "[2015] – [2017]"
    industry: "Computational Science & Data Analysis"
    location: "[Tehran, Iran]"
    company_description: "Focused on Discrete Element Method (DEM) simulations and the statistical mechanics of dense granular materials."
    bullet_points:
      - "Executed 100+ large-scale Discrete Element Method (DEM) simulations using LAMMPS on an HPC cluster, managing approximately 288,000 total core hours (40-core parallel processing per run)."
      - "Architected a high-performance data pipeline using Python (Pandas, NumPy) to process and analyze massive datasets from systems of 70,000+ particles."
      - "Developed custom analytical scripts to calculate Radial Distribution Functions (RDF) and implemented Adaptive Common Neighbor Analysis (a-CNA) to quantify structural phase transitions."
      - "Identified and visualized the formation of 'frozen' polycrystalline structures within shear bands using OVITO, comparing velocity profiles and granular temperatures between dry and wet systems."
      - "Modeled complex capillary bridge cohesive forces to successfully replicate and analyze low-dissipation, high-dissipation, and oscillatory flow regimes in monodisperse granular flows."

---
