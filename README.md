<div align="center">

# RAI Studio · Xiaohongshu AI Infrastructure

**From compute and model production to reliable AI services and agents.**

[Explore our projects](https://github.com/orgs/redai-studio/repositories) · [Research & Open Source](#research--open-source) · [Get Involved](#get-involved)

</div>

## Who We Are

We are the **Large Model Infrastructure Team at Xiaohongshu (Rednote)**, responsible for the company's end-to-end infrastructure for large models.

We build across three layers — **compute, frameworks, and platforms** — to support model training, compression, deployment, online and offline serving, and agent development and publishing. Our work helps teams turn model capabilities into production applications with greater efficiency, lower cost, reliable operation, and repeatable delivery at scale.

Our infrastructure supports AI applications across community experiences, commercial services, international operations, content moderation, and enterprise intelligence.

## Our Mission

> Build Xiaohongshu's foundation for productivity in the AI era — making AI as reliable, efficient, and accessible as water and electricity for every business scenario.

We believe better models need infrastructure that consistently turns their capabilities into real-world value. We focus on:

- **Faster experimentation and delivery** — Help teams validate ideas, produce models, and deploy AI applications through a unified toolchain.
- **Efficient compute and execution** — Improve resource utilization through unified GPU scheduling, heterogeneous hardware support, and training and inference optimization.
- **Reliable services at scale** — Build dependable model services and observable agent applications that can grow with demand.
- **Open collaboration and research** — Share reusable systems and research with the community, and advance AI infrastructure together.

## Our Infrastructure Stack

RAI Studio connects the compute foundation, model frameworks, and developer platforms through five complementary layers:

| Layer | Products & Capabilities | What It Enables |
|---|---|---|
| **Agent applications** | **ALL-IN** platform and SDK: agent orchestration, workflows and tools, knowledge and memory, application publishing, and observability | Build, publish, and operate AI applications |
| **Model services** | **Red Token Hub**: online and offline model services, model onboarding, routing and scheduling, KV cache reuse, high availability, and elastic scaling | Reliable and efficient Model-as-a-Service (MaaS) |
| **Model production** | **QuickSilver**: data management, training, compression, deployment, and evaluation | A unified toolchain across the model lifecycle |
| **Frameworks & runtimes** | **RedAccel**, **Relax**, **RedSlim**, **rLLM**, and **DirectLLM**: our framework portfolio spanning model training, compression, and inference | Accelerate model production and execution across heterogeneous hardware |
| **Compute infrastructure** | Unified management and scheduling across accelerator types and regions, elastic resource allocation, and cluster efficiency optimization | Scalable compute capacity and better resource utilization |

This matrix describes our broader infrastructure portfolio. Public repositories and research are listed below; see each repository for available code, documentation, and licensing.

## Research & Open Source

Our open-source work spans reinforcement learning, model compression, efficient inference, reasoning, and computer-use agents.

| Project | Focus | Links |
|---|---|---|
| **Relax** | Asynchronous reinforcement learning for omni-modal post-training at scale | [Code](https://github.com/redai-studio/Relax) · [Paper](https://arxiv.org/abs/2604.11554) |
| **HiSVD** | Hierarchical low-rank model compression guided by information capacity and spectral structure | [Code](https://github.com/redai-studio/HiSVD) · [Paper](https://openreview.net/forum?id=oR0gL0HGnf) |
| **PIPO — Pair-In, Pair-Out** | Latent multi-token prediction for efficient large language models | [Code](https://github.com/redai-studio/PIPO) · [Paper](https://arxiv.org/abs/2605.27255) |
| **Hint Tuning** | Improving reasoning with less training data | [Code](https://github.com/redai-studio/hint-tuning) · [Paper](https://arxiv.org/abs/2605.08665) |
| **HYPIC** | Position-independent caching for faster hybrid-attention model serving | [Code](https://github.com/redai-studio/HYPIC) · [Paper](https://arxiv.org/abs/2607.01299) |
| **Hybrid Routing Agent** | Tool use and multimodal context management for hybrid GUI–MCP computer-use agents | [Code](https://github.com/redai-studio/hybrid-routing-agent) · [Paper](https://arxiv.org/abs/2608.03327) |

## Get Involved

We welcome developers and researchers working on efficient, reliable AI infrastructure.

- **Try a project:** Start with its README for setup, examples, and supported configurations.
- **Report a problem or share an idea:** Open an issue in the relevant repository with reproduction steps or a concrete proposal.
- **Contribute:** Submit code, documentation, examples, or reproducible benchmarks, following the repository's contribution guidance where available.
- **Build on our research:** Read the linked papers and use each project's citation instructions when referencing the work.

Browse [all RAI Studio repositories](https://github.com/orgs/redai-studio/repositories) to find a project that matches your interests.

---

<div align="center">

**Built by the Xiaohongshu Large Model Infrastructure Team · Open to collaboration.**

</div>
