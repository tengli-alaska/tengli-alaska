# Alaska Tengli

**Systems × AI - from silicon validation to ML infrastructure.**

I come from hardware/post-silicon validation, PCIe interconnects, secure boot firmware - and I've been building toward AI infrastructure and performance engineering. I think about inference bottlenecks in terms of cache coherence, memory hierarchies, and what's actually happening on the silicon.

MS in ECE @ Northeastern University · Previously @ Altera (Intel) · Aptiv

---

### Currently

- Contributing performance fixes to **[ONNX Runtime](https://github.com/tengli-alaska/onnxruntime)** - diagnosed and resolved a 17–28% AveragePool regression by identifying a compiler auto-vectorization blocker in the CPU execution provider
- Research with **MIT Sea Grant** - performance analysis of CV-based ML models
- Building **MLOps pipelines** and **distributed systems** coursework at Northeastern

---

### Selected Work

**AI for Hardware Validation** · *Altera (Intel FPGA)*
Built an LLM-driven test plan generator with RAG pipelines and an unsupervised validation engine that improved test coverage by 94%. Designed PCIe/CXL link testing frameworks at the hardware-software interface. Presented at Altera Innovation Day 2025.

**GPU & HPC Optimization** · *Northeastern*
Heterogeneous CPU–GPU graph workloads (PageRank, Graph Coloring) using MPI + CUDA on NVIDIA A100 clusters. Profiled with Nsight Systems, scheduled with SLURM across multi-node clusters.

**Memory Architecture Research** · *Northeastern*
Evaluated CXL 2.0 cache coherence protocols (MESI, MOESI, Directory-Based) using QEMU emulation. Presented poster at Future of Memory & Storage 2025.

**Embedded Firmware** · *Aptiv*
Secure Boot with AES-128 MAC cryptography and HSM integration for automotive ECUs. Debugged FlexRay/SPI paths via Lauterbach TRACE32 and JTAG.

---

### Projects

| Project | What it does |
|---|---|
| [Workload Clustering Pipeline](https://github.com/tengli-alaska/workload-clustering-airflow) | Airflow DAG for K-Means clustering of server workload telemetry — identifies CPU-bound, memory-bound, GPU-intensive, and idle profiles |
| [ML Inference Latency Predictor](https://github.com/tengli-alaska/Flask-GCP-Lab-ML-Inference-Latency-Predictor) | Estimates inference time and throughput (FPS) across cloud GPUs, edge devices, and CPUs — deployed on GCP Cloud Run |
| [BlueForecast MLOps Pipeline](https://github.com/tengli-alaska/BlueForecast--Predictive-Operations-Platform-for-Bluebikes) | End-to-end demand prediction with XGBoost, Airflow, DVC, and GCP across 8M+ rows |
| [ONNX Runtime (fork)](https://github.com/tengli-alaska/onnxruntime/tree/fix/averagepool-regression) | Fix for AveragePool performance regression — guarded bounds clamping behind ceil_mode check to restore auto-vectorization |
| [Distributed Systems](https://github.com/tengli-alaska/Distributed-Systems) | Cloud-native services in Go — MapReduce, containerized APIs on AWS ECS Fargate, Terraform IaC |

---

### Tech

```
Systems       C · C++ · Verilog · PCIe/CXL · RISC-V · ARM · FreeRTOS · QEMU · JTAG · GDB · Valgrind
AI/ML         Python · PyTorch · TensorFlow · ONNX Runtime · CUDA · Nsight Systems · Hugging Face · LangChain
Infra         Go · Docker · Terraform · AWS · GCP · Jenkins · Airflow · DVC · gRPC
HPC           MPI · OpenMP · SLURM · CUDA Profiling · Latency/Bandwidth Analysis
```

---

### Publications & Talks

- **Future of Memory & Storage 2025** - Poster: Cache Coherence Protocols on CXL 2.0
- **Altera Innovation Day 2025** - AI-based Unsupervised Validation Engine
- **CSITSS 2024** - [Secure Boot Implementation in Automotive ECU](https://ieeexplore.ieee.org/document/10816980)
- **Bentham Science 2024** - [Book Chapter: Cyber-Physical Systems for UAVs](https://www.benthamdirect.com/content/books/9789815223286.chapter-4)

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-alaska--tengli-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alaska-tengli-8505671b0/)
[![Email](https://img.shields.io/badge/Email-tengli.a@northeastern.edu-D14836?style=flat&logo=gmail&logoColor=white)](mailto:tengli.a@northeastern.edu)
