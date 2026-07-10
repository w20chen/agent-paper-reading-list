# Paper Reading List for LLM Agent Scheduling

## LLM Serving ⭐️

1. Orca: A Distributed Serving System for Transformer-Based Generative Models (OSDI 2022)
2. Fast Distributed Inference Serving for Large Language Models (2024)
3. Efficient LLM Scheduling by Learning to Rank (NeurIPS 2024)
4. Llumnix: Dynamic Scheduling for Large Language Model Serving (OSDI 2024)
5. Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving (2024)
6. Blendserve: Optimizing Offline Inference for Auto-Regressive Large Models with Resource-Aware Batching (2024)
7. Optimal Scheduling Algorithms for LLM Inference: Theory and Practice (2025)
8. Aladdin: Joint Placement and Scaling for SLO-Aware LLM Serving (2024)
9. Jenga: Effective Memory Management for Serving LLM with Heterogeneity (2025)
10. WindServe: Efficient Phase-Disaggregated LLM Serving via Stream-based Scheduling (2025)
11. ThunderServe: High-performance and Cost-efficient LLM Serving in Cloud Environments (2025)
12. ServerlessLLM: Low-Latency Serverless Inference for Large Language Models (2024)
13. PowerInfer: Fast Large Language Model Serving with a Consumer-grade GPU (2024)
14. dLoRA: Dynamically Orchestrating Requests and Adapters for LoRA LLM Serving
15. STAGGERED BATCH SCHEDULING: CO-OPTIMIZING TIME-TO-FIRST-TOKEN AND THROUGHPUT FOR HIGH-EFFICIENCY LLM INFERENCE
16. FlashInfer: Efficient and Customizable Attention Engine for LLM Inference Serving
1. Efficient Memory Management for Large Language Model Serving with PagedAttention (SOSP 2023)
2. SARATHI: Efficient LLM Inference by Piggybacking Decodes with Chunked Prefills (2023)
3. DistServe: disaggregating prefill and decoding for goodput-optimized large language model serving (OSDI 2024)
1. Agent.xpu: Efficient Scheduling of Agentic LLM Workloads on Heterogeneous SoC
6. PrefillOnly: An Inference Engine for Prefill-only Workloads in Large Language Model Applications

## Scheduling for LLM Agents ⭐️

1. ⭐️Parrot: Efficient Serving of LLM-based Applications with Semantic Variable (OSDI 2024)
2. ⭐️Autellix: An Efficient Serving Engine for LLM Agents as General Programs (2025)
3. ⭐️Continuum: Efficient and Robust Multi-turn LLM Agent Scheduling with KV Cache Time-to-Live (2025)
4. ⭐️Towards End-to-End Optimization of LLM-based Applications with Ayo (as known as Teola) (ASPLOS 2025)
5. Alto: An Efficient Network Orchestrator for Compound AI Systems (EuroMLSys 2024)
6. Batch Query Processing and Optimization for Agentic Workflows (2025)
7. ⭐️LLMSched: Uncertainty-Aware Workload Scheduling for Compound LLM Applications (ICDCS 2025)
8. ⭐️NALAR: A Serving Framework for Agent Workflows
9. Transcending Cost-Quality Tradeoff in Agent Serving via Session-Aware KV Cache Management (NeurIPS 2025)
10. Software-Defined Agentic Serving (2026)
11. Gradientsys: A Multi-Agent LLM Scheduler with ReAct Orchestration (2025)
12. ⭐️KVFlow: Efficient Prefix Caching for Accelerating LLM-Based Multi-Agent Workflows (2025)
13. ⭐️Tokencake: A KV-Cache-centric Serving Framework for LLM-based Multi-Agent Applications (2025)
14. DualPath: Breaking the Storage Bandwidth Bottleneck in Agentic LLM Inference (Feb 2025)
15. ⭐️ThunderAgent: A Simple, Fast and Program-Aware Agentic Inference System (Feb 2026) and Autellix: An Efficient Serving Engine for LLM Agents as General Programs (Feb 2025)
16. Astraea: A State-Aware Scheduling Engine for LLM-Powered Agents (Dec 2025)
17. Kairos: Low-latency Multi-Agent Serving with Shared LLMs and Excessive Loads in the Public Cloud (Aug 2025)
18. Towards Efficient Agents: A Co-Design of Inference Architecture and System
19. CONCUR: Proactive Agent-Level Admission Control for Efficient Agentic Batch Inference
20. AgentServe: Algorithm-System Co-Design for Efficient Agentic AI Serving on a Consumer-Grade GPU
21. Justitia: Fair and Efficient Scheduling for LLM Applications
22. Throughput-Optimal Scheduling Algorithms for LLM Inference and AI Agents
23. Murakkab: Resource-Efficient Agentic Workflow Orchestration in Cloud Platforms
24. Optimas: Optimizing Compound AI Systems with Globally Aligned Local Rewards
25. Compound AI Systems Optimization: A Survey of Methods, Challenges, and Future Directions
26. Twill: Scheduling Compound AI Systems on Heterogeneous Mobile
27. ⭐️MARS: Efficient, Adaptive Co-Scheduling for Heterogeneous Agentic Systems
28. ⭐️SAGA: Workflow-Atomic Scheduling for AI Agent Inference on GPU Clusters
29. ⭐️Hive: A Multi-Agent Infrastructure for Algorithm- and Task-Level Scaling
30. ⭐️Idleness is Relative: Exploiting Tool-Call Idle Windows for Offloading in Agentic Systems with MORI
31. ⭐️Efficient LLM Serving for Agentic Workflows: A Data Systems Perspective
32. Efficient Serving for Dynamic Agent Workflows with Prediction-based KV Cache Management
33. Serving Agentic Workloads at Scale with vLLM x Mooncake (https://vllm.ai/blog/2026-05-06-mooncake-store)
34. Fast State Restoration in LLM Serving with HCache
35. Online Scheduling for LLM Inference with KV Cache Constraints
36. ⭐️SwarmX: Agentic Scheduling for Low-Latency Agentic Systems
37. ⭐️Act While Thinking: Accelerating LLM Agents via Pattern-Aware Speculative Tool Execution
38. ⭐️TokenSpeed: A Speed-of-Light LLM Inference Engine for Agentic Workloads (https://lightseek.org/blog/lightseek-tokenspeed.html)
39. ⭐️MLCOMMONS CHAKRA: ADVANCING PERFORMANCE BENCHMARKING AND CO-DESIGN USING STANDARDIZED EXECUTION TRACES
40. ⭐️AGENTSERVESIM: A Hardware-aware Simulator for Multi-Turn LLM Agent Serving
41. ⭐️Don't Let AI Agents YOLO Your Files: Shifting Information and Control to Filesystems for Agent Safety and Autonomy
42. ⭐️DeltaBox: Scaling Stateful AI Agents with Millisecond-Level Sandbox Checkpoint/Rollback
43. PARTIES: QoS-Aware Resource Partitioning for Multiple Interactive Services (https://www.csl.cornell.edu/~delimitrou/papers/2019.asplos.parties.pdf)
44. Orchard: An Open-Source Agentic Modeling Framework
45. ⭐️Crab: A Semantics-Aware Checkpoint/Restore Runtime for Agent Sandboxes
46. ⭐️A CPU-CENTRIC PERSPECTIVE ON AGENTIC AI (https://arxiv.org/pdf/2511.00739v2)
47. ⭐️AgentCgroup: Understanding and Controlling OS Resources of AI Agents
48. the-cpu-bottleneck-in-agentic-ai (https://www.viksnewsletter.com/p/the-cpu-bottleneck-in-agentic-ai)


## LLM Agent Workflow ⬜️

1. Large Language Model Agent: A Survey on Methodology, Applications and Challenges (2025)
2. Alloy: Generating Reusable Agent Workflows from User Demonstrations (2025)
3. Self-Organizing Agent Network for LLM-based Workflow Automation (2025)
4. Agent-S: LLM Agentic workflow to automate Standard Operating Procedures (2025)
5. Difficulty-Aware Agent Orchestration in LLM-Powered Workflows (2025)
6. AdaptFlow: Adaptive Workflow Optimization via Meta-Learning (2025)
7. Accelerating Language Model Workflows with Prompt Choreography (2025)
8. AutoSynth: Automated Workflow Optimization for High-Quality Synthetic Dataset Generation via Monte Carlo Tree Search (2025)
9. Opus: A Large Work Model for Complex Workflow Generation (2024)
10. Advancing Agentic Systems: Dynamic Task Decomposition, Tool Integration and Evaluation using Novel Metrics and Dataset (2024)
11. DEEP RESEARCH AGENTS: A SYSTEMATIC EXAMINATION AND ROADMAP (2025)
12. Tongyi Deep Research Technical Report (2025)
13. Fundamentals of Building Autonomous LLM Agents (2025)
14. DeepAnalyze: Agentic Large Language Models for Autonomous Data Science (2025)
7. A Survey on Agent Workflow -- Status and Future (2025)
2. AIOS: LLM Agent Operating System
3. Cortex AISQL: A Production SQL Engine for Unstructured Data
4. Interactional Fairness in LLM Multi-Agent Systems


## Multi-Agent Collaboration ⬜️

1. AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors (2023)
2. Multi-Agent Collaboration via Evolving Orchestration (2025)
3. AgentOrchestra: Orchestrating Multi-Agent Intelligence with the Tool-Environment-Agent(TEA) Protocol (2025)
4. MAO-ARAG: Multi-Agent Orchestration for Adaptive Retrieval-Augmented Generation (2025)
5. MOSAIC: Multi-agent Orchestration for Task-Intelligent Scientific Coding (2025)
6. Multi-Agent Collaboration Mechanisms: A Survey of LLMs (2025)
8. When Should We Orchestrate Multiple Agents? (2025)
9. More Agents Is All You Need (2024)
10. Fundamentals of Building Autonomous LLM Agents (2025)

## KV Cache Sparsity ⬛

1. Chen, Yaoqi, Jinkai Zhang, Baotong Lu, Qianxi Zhang, Chengruidong Zhang, Jingjia Luo, Di Liu et al. "RetroInfer: A Vector-Storage Approach for Scalable Long-Context LLM Inference." arXiv preprint arXiv:2505.02922 (2025).
2. Liu, Di, Meng Chen, Baotong Lu, Huiqiang Jiang, Zhenhua Han, Qianxi Zhang, Qi Chen et al. "Retrievalattention: Accelerating long-context llm inference via vector retrieval." arXiv preprint arXiv:2409.10516 (2024).
3. Tang, Jiaming, Yilong Zhao, Kan Zhu, Guangxuan Xiao, Baris Kasikci, and Song Han. "Quest: Query-aware sparsity for efficient long-context llm inference." arXiv preprint arXiv:2406.10774 (2024).
4. Zhang, Zhenyu, Ying Sheng, Tianyi Zhou, Tianlong Chen, Lianmin Zheng, Ruisi Cai, Zhao Song et al. "H2o: Heavy-hitter oracle for efficient generative inference of large language models." Advances in Neural Information Processing Systems 36 (2023): 34661-34710.
5. Ge, Suyu, Yunan Zhang, Liyuan Liu, Minjia Zhang, Jiawei Han, and Jianfeng Gao. "Model tells you what to discard: Adaptive kv cache compression for llms." arXiv preprint arXiv:2310.01801 (2023).
6. Oren, Matanel, Michael Hassid, Nir Yarden, Yossi Adi, and Roy Schwartz. "Transformers are multi-state rnns." arXiv preprint arXiv:2401.06104 (2024).
7. Chen, Zhuoming, Ranajoy Sadhukhan, Zihao Ye, Yang Zhou, Jianyu Zhang, Niklas Nolte, Yuandong Tian et al. "Magicpig: Lsh sampling for efficient llm generation." arXiv preprint arXiv:2410.16179 (2024).
8. Lee, Wonbeom, Jungi Lee, Junghwan Seo, and Jaewoong Sim. "{InfiniGen}: Efficient generative inference of large language models with dynamic {KV} cache management." In 18th USENIX Symposium on Operating Systems Design and Implementation (OSDI 24), pp. 155-172. 2024.
9. Li, Yuhong, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, and Deming Chen. "Snapkv: Llm knows what you are looking for before generation." Advances in Neural Information Processing Systems 37 (2024): 22947-22970.
10. Xiao, Chaojun, Pengle Zhang, Xu Han, Guangxuan Xiao, Yankai Lin, Zhengyan Zhang, Zhiyuan Liu, and Maosong Sun. "Infllm: Training-free long-context extrapolation for llms with an efficient context memory." Advances in Neural Information Processing Systems 37 (2024): 119638-119661.
11. Xiao, Guangxuan, Yuandong Tian, Beidi Chen, Song Han, and Mike Lewis. "Efficient streaming language models with attention sinks." arXiv preprint arXiv:2309.17453 (2023).
12. Ribar, Luka, Ivan Chelombiev, Luke Hudlass-Galley, Charlie Blake, Carlo Luschi, and Douglas Orr. "Sparq attention: Bandwidth-efficient llm inference." arXiv preprint arXiv:2312.04985 (2023).
13. Deng, Yangshen, Zhengxin You, Long Xiang, Qilong Li, Peiqi Yuan, Zhaoyang Hong, Yitao Zheng et al. "AlayaDB: The Data Foundation for Efficient and Effective Long-context LLM Inference." In Companion of the 2025 International Conference on Management of Data, pp. 364-377. 2025.
14. G. Liu, C. Li, J. Zhao, C. Zhang and M. Guo, "ClusterKV: Manipulating LLM KV Cache in Semantic Space for Recallable Compression," 2025 62nd ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, USA, 2025, pp. 1-7, doi: 10.1109/DAC63849.2025.11132479.


## KV Cache Reuse ⬛

1. Yao, Jiayi, Hanchen Li, Yuhan Liu, Siddhant Ray, Yihua Cheng, Qizheng Zhang, Kuntai Du, Shan Lu, and Junchen Jiang. "CacheBlend: Fast large language model serving for RAG with cached knowledge fusion." In Proceedings of the Twentieth European Conference on Computer Systems, pp. 94-109. 2025.
2. LMCache: An Efficient KV Cache Layer for Enterprise-Scale LLM Inference
2. Jin, Chao, Zili Zhang, Xuanlin Jiang, Fangyue Liu, Xin Liu, Xuanzhe Liu, and Xin Jin. "Ragcache: Efficient knowledge caching for retrieval-augmented generation." arXiv preprint arXiv:2404.12457 (2024).
3. Kwon, Woosuk, Zhuohan Li, Siyuan Zhuang, Ying Sheng, Lianmin Zheng, Cody Hao Yu, Joseph Gonzalez, Hao Zhang, and Ion Stoica. "Efficient memory management for large language model serving with pagedattention." In Proceedings of the 29th symposium on operating systems principles, pp. 611-626. 2023.
4. Liu, Yuhan, Hanchen Li, Kuntai Du, Jiayi Yao, Yihua Cheng, Yuyang Huang, Shan Lu et al. "Cachegen: Fast context loading for language model applications." CoRR (2023).
5. Zheng, Lianmin, Liangsheng Yin, Zhiqiang Xie, Chuyue Livia Sun, Jeff Huang, Cody Hao Yu, Shiyi Cao et al. "Sglang: Efficient execution of structured language model programs." Advances in neural information processing systems 37 (2024): 62557-62583.
6. Gim, In, Guojun Chen, Seung-seob Lee, Nikhil Sarda, Anurag Khandelwal, and Lin Zhong. "Prompt cache: Modular attention reuse for low-latency inference." Proceedings of Machine Learning and Systems 6 (2024): 325-338.
7. Pan, Rui, Zhuang Wang, Zhen Jia, Can Karakus, Luca Zancato, Tri Dao, Yida Wang, and Ravi Netravali. "Marconi: Prefix caching for the era of hybrid LLMs." arXiv preprint arXiv:2411.19379 (2024).
8. Liu, Yuhan, Yuyang Huang, Jiayi Yao, Shaoting Feng, Zhuohan Gu, Kuntai Du, Hanchen Li et al. "DroidSpeak: KV Cache Sharing for Cross-LLM Communication and Multi-LLM Serving." arXiv preprint arXiv:2411.02820 (2024).
9. Liu, Shu, Asim Biswal, Audrey Cheng, Xiangxi Mo, Shiyi Cao, Joseph E. Gonzalez, Ion Stoica, and Matei Zaharia. "Optimizing llm queries in relational workloads." CoRR (2024).
10. Gao, Bin, Zhuomin He, Puru Sharma, Qingxuan Kang, Djordje Jevdjic, Junbo Deng, Xingkun Yang, Zhou Yu, and Pengfei Zuo. "{Cost-Efficient} large language model serving for multi-turn conversations with {CachedAttention}." In 2024 USENIX Annual Technical Conference (USENIX ATC 24), pp. 111-126. 2024.
11. Srivatsa, Vikranth, Zijian He, Reyna Abhyankar, Dongming Li, and Yiying Zhang. "Preble: Efficient distributed prompt scheduling for llm serving." arXiv preprint arXiv:2407.00023 (2024).
12. Abhyankar, Reyna, Zijian He, Vikranth Srivatsa, Hao Zhang, and Yiying Zhang. "Infercept: Efficient intercept support for augmented large language model inference." arXiv preprint arXiv:2402.01869 (2024).
13. Qin, Ruoyu, Zheming Li, Weiran He, Mingxing Zhang, Yongwei Wu, Weimin Zheng, and Xinran Xu. "Mooncake: A kvcache-centric disaggregated architecture for llm serving." arXiv preprint arXiv:2407.00079 (2024).
14. EVICPRESS: Joint KV-Cache Compression and Eviction for Efficient LLM Serving (2025)


## Miscellaneous Papers ⬜️
1. A Survey on Large Language Model Acceleration based on KV Cache Management
2. METIS: Fast Quality-Aware RAG Systems with Configuration Adaptation
3. WLB-LLM: Workload-Balanced 4D Parallelism for Large Language Model Training
4. ⭐️Kunpeng 920: The First 7-nm Chiplet-Based 64-Core ARM SoC for Cloud Services (https://ieeexplore.ieee.org/document/9444893 https://chipsandcheese.com/p/huaweis-kunpeng-920-and-taishan-v110)
5. ⭐️Intel VTune Profiler Performance Analysis Cookbook (https://www.intel.com/content/www/us/en/docs/vtune-profiler/cookbook/2023-1/top-down-microarchitecture-analysis-method.html)