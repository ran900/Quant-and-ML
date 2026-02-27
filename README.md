# Quant-and-ML
Quant and ML Papers Code
```mermaid
graph TD
    %% 定义节点
    A[传统资产定价模型<br>（Fama-French, 线性因子）]
    B[Gu, Kelly & Xiu (2020)<br>《Empirical Asset Pricing via ML》]
    C[Chen, Pelger & Zhu (2019)<br>《Deep Learning in Asset Pricing》]
    D[传统新闻情感分析<br>（Tetlock 等，词典法）]
    E[Lopez-Lira & Tang (2023)<br>《Can ChatGPT Forecast...》]

    %% 连接关系
    A -->|高维变量、非线性<br>传统方法局限| B
    B -->|从预测收益到估计SDF<br>引入无套利约束| C
    D -->|词袋模型→深度学习<br>BERT→GPT| E
    B -.->|结构化数据预测<br>为文本分支提供对比基准| E
    C -.->|结构化数据中的SDF<br>与文本数据的互补| E

    %% 样式
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#bbf,stroke:#333,stroke-width:2px
    style C fill:#bfb,stroke:#333,stroke-width:2px
    style D fill:#ffd,stroke:#333,stroke-width:2px
    style E fill:#feb,stroke:#333,stroke-width:2px
```
