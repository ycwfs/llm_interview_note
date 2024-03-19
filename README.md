# LLMs Interview 八股文


## 简介

本仓库为大模型面试相关概念，由本人参考网络资源整理，欢迎阅读，如果对你有用，麻烦点一下 `start`，谢谢！

## 在线阅读

本仓库相关文章已放在个人博客中，欢迎阅读：

在线阅读链接：[LLMs Interview Note](http://wdndev.github.io/note/llm/llm_concept/llm%E5%85%AB%E8%82%A1.html)

## 注意：

相关答案为自己撰写，若有不合理地方，请指出修正，谢谢！

欢迎关注微信公众号，会不定期更新LLM内容，以及一些面试经验：

 <img src=https://github.com/wdndev/personal/blob/main/image/llmers_weixin.jpg width = "427" height = "156" alt="weixin" />


## 目录

### [01.大语言模型简介](01.大语言模型简介/README.md)

##### 1.1 大模型发展历程

1. 语言模型

##### 1.2 常见大模型

1. [llama系列模型](01.大语言模型简介/llama系列模型/llama系列模型.md )
2. [chatglm系列模型](01.大语言模型简介/chatglm系列模型/chatglm系列模型.md)

##### 1.3 LLM基础题目

### [02.大语言模型基础](02.大语言模型基础/README.md)

##### 2.1 Transformer模型

1. [attention](02.大语言模型基础/1.attention/1.attention.md)
2. [layer\_normalization](02.大语言模型基础/2.layer_normalization/2.layer_normalization.md)
3. [位置编码](02.大语言模型基础/3.位置编码/3.位置编码.md)
4. [tokenize分词](02.大语言模型基础/4.tokenize分词/4.tokenize分词.md)
5. [token及模型参数](02.大语言模型基础/4.token及模型参数/4.token及模型参数.md)
6. [激活函数](02.大语言模型基础/5.激活函数/5.激活函数.md )

##### 2.2 大语言模型结构

### [03.语言模型训练数据集](03.语言模型训练数据集/03.语言模型训练数据集.md)

### [04.分布式训练](04.分布式训练/README.md)

##### 4.1 基础知识

1. [概述](04.分布式训练/1.概述/1.概述.md)
2. [数据并行](04.分布式训练/2.数据并行/2.数据并行.md)
3. [流水线并行](04.分布式训练/3.流水线并行/3.流水线并行.md)
4. [张量并行](04.分布式训练/4.张量并行/4.张量并行.md)
5. [序列并行](04.分布式训练/5.序列并行/5.序列并行.md)
6. [多维度混合并行](04.分布式训练/6.多维度混合并行/6.多维度混合并行.md)
7. [自动并行](04.分布式训练/7.自动并行/7.自动并行.md)
8. [moe并行](04.分布式训练/8.moe并行/8.moe并行.md )
9. [总结](04.分布式训练/9.总结/9.总结.md )

##### 4.2 DeepSpeed

1. DeepSpeed介绍

##### 4.3 软硬件

1. 显存问题

##### 4.4 分布式相关题目

### [05.有监督微调](05.有监督微调/README.md)

##### 5.1  理论

1. [基本概念](05.有监督微调/1.基本概念/1.基本概念.md)
2. [prompting](05.有监督微调/2.prompting/2.prompting.md)
3. [adapter-tuning](05.有监督微调/3.adapter-tuning/3.adapter-tuning.md)
4. [lora](05.有监督微调/4.lora/4.lora.md)
5. [总结](05.有监督微调/5.总结/5.总结.md)

##### 5.2 微调实战

1. LLaMa2微调

##### 5.3 有监督微调相关题目

1. 微调
2. 预训练

### [06.推理](06.推理/README.md)

##### 6.1 推理框架

1. [llm推理框架简单总结](06.推理/0.llm推理框架简单总结/0.llm推理框架简单总结.md "0.llm推理框架简单总结")
2. [vLLM](06.推理/1.vllm/1.vllm.md "1.vllm")
3. [Text Generation Inference](06.推理/2.text_generation_inference/2.text_generation_inference.md "2.text_generation_inference")
4. [Faster Transformer](06.推理/3.faster_transformer/3.faster_transformer.md "3.faster_transformer")
5.  [TRT LLM](06.推理/4.trt_llm/4.trt_llm.md "4.trt_llm")

##### 6.2 推理优化技术

1. [LLM推理优化技术](06.推理/llm推理优化技术/llm推理优化技术.md "llm推理优化技术")
2. [LLM推理常见参数](06.推理/LLM推理常见参数/LLM推理常见参数.md)


##### 6.3 推理相关题目

1. [推理](06.推理/1.推理/1.推理.md "1.推理")

### [07.强化学习](07.强化学习/README.md)

##### 7.1 强化学习原理

1. [策略梯度（pg）](07.强化学习/策略梯度（pg）/策略梯度（pg）.md "策略梯度（pg）")
2. [近端策略优化(ppo)](07.强化学习/近端策略优化(ppo)/近端策略优化(ppo).md)

##### 7.2 RLHF

1. [大模型RLHF：PPO原理与源码解读](07.强化学习/大模型RLHF：PPO原理与源码解读/大模型RLHF：PPO原理与源码解读.md)
2. [DPO](07.强化学习/DPO/DPO.md)

##### 7.3 一些题目

1. [rlhf相关](07.强化学习/1.rlhf相关/1.rlhf相关.md "1.rlhf相关")
2. [强化学习](07.强化学习/2.强化学习/2.强化学习.md "2.强化学习")

### [08.检索增强rag](08.检索增强rag/README.md)

##### 8.1 RAG

1. [检索增强llm](08.检索增强rag/检索增强llm/检索增强llm.md)

2. [rag（检索增强生成）技术](08.检索增强rag/rag（检索增强生成）技术/rag（检索增强生成）技术.md)

##### 8.2 Agent

1. [大模型agent技术](08.检索增强rag/大模型agent技术/大模型agent技术.md)

### [09.大语言模型评估](09.大语言模型评估/README.md)

##### 9.1 模型评估

1. [评测](09.大语言模型评估/1.评测/1.评测.md)

##### 9.2 LLM幻觉

1. [大模型幻觉](09.大语言模型评估/1.大模型幻觉/1.大模型幻觉.md)
2. [幻觉来源与缓解](09.大语言模型评估/2.幻觉来源与缓解/2.幻觉来源与缓解.md)

### [10.大语言模型应用](10.大语言模型应用/README.md)

##### 10.1 思维链（CoT）

1. [思维链（cot）](10.大语言模型应用/1.思维链（cot）/1.思维链（cot）.md "1.思维链（cot）")




##### 10.2 LangChain 框架

1. [langchain](10.大语言模型应用/1.langchain/1.langchain.md "1.langchain")

### [98.LLMs相关课程](98.LLMs相关课程/README.md)

### [99.参考资料](99.参考资料/README.md )

## 更新记录

- 2024.03.19 : 推理参数
- 2024.03.17 ： 强化学习部分，PG，PPO，RLHF，DPO
- 2024.03.13 ： 强化学习题目
- 2024.03.10 : LLMs相关课程
- 2024.03.08 ： RAG技术
- 2024.03.05 ：大模型评估，幻觉
- 2024.01.26 ：语言模型简介
- 2023.12.15 ： llama，chatglm 架构
- 2023.12.02 ：LLM推理优化技术
- 2023.12.01 ：调整目录
- 2023.11.30 ：18.Layer-Normalization，21.Attention升级
- 2023.11.29 ： 19.激活函数，22.幻觉，23.思维链
- 2023.11.28 ： 17.位置编码
- 2023.11.27 ： 15.token及模型参数， 16.tokenize分词
- 2023.11.25 ： 13.分布式训练
- 2023.11.23 ： 6.推理， 7.预训练， 8.评测，9.强化学习， 11.训练数据集，12.显存问题,14.agent
- 2023.11.22 ： 5.高效微调
- 2023.11.10 ： 4.LangChain
- 2023.11.08 ： 建立仓库；1.基础，2.进阶，3.微调





