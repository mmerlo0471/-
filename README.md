graph LR
%% 总流程
A[问题提出] --> B[理论研究与政策分析]
B --> C[文化资源筛选与转化]
C --> D[课程体系构建]
D --> E[教学实践与迭代]
E --> F[评价机制开发]
F --> G[成果推广与应用]

%% ---------- 阶段1：问题提出 ----------
subgraph A_Stage[问题提出]
  A1[输入] -->|地方文化传承困境| A2[方法]
  A2[方法] -->|文献分析+实地调研| A3[输出]
  
  A1:::input --> A2:::method
  A2 --> A3:::output
  
  classDef input fill:#e6f3ff,stroke:#4d90fe;
  classDef method fill:#fff2cc,stroke:#f6b26b;
  classDef output fill:#d9ead3,stroke:#6aa84f;
  
  A1("输入：
  - 地方文化传承困境
  （碎片化、形式单一）
  - 课程实施痛点
  （缺乏系统性）")
  
  A2("方法：
  - 文献分析（CNKI/万方）
  - 实验校实地调研")
  
  A3("输出：
  - 《现状调研报告》
  - 核心问题清单")
end

%% ---------- 阶段2：理论研究 ----------
subgraph B_Stage[理论研究与政策分析]
  B1[输入] --> B2[方法]
  B2[方法] --> B3[输出]
  
  B1("输入：
  - 政策文件
  （指导纲要/文化指南）
  - 理论框架
  （杜威/施瓦布）")
  
  B2("方法：
  - 文献计量分析
  （CiteSpace）
  - 专家访谈")
  
  B3("输出：
  - 《政策理论手册》
  - 研究假设模型")
end

%% ---------- 阶段3：资源筛选 ----------
subgraph C_Stage[文化资源筛选与转化]
  C1[输入] --> C2[方法]
  C2[方法] --> C3[输出]
  
  C1("输入：
  - 地方文化资源库
  （皮雕/剪纸/香囊）")
  
  C2("方法：
  - 德尔菲法（专家评审）
  - 行动研究（试点验证）")
  
  C3("输出：
  - 《资源分级目录》
  - 转化标准")
end

%% ---------- 阶段4：课程构建 ----------
subgraph D_Stage[课程体系构建]
  D1[输入] --> D2[方法]
  D2[方法] --> D3[输出]
  
  D1("输入：
  - 分学段目标
  （低/中/高年级）")
  
  D2("方法：
  - 跨学科整合（STEAM）
  - 模块化设计")
  
  D3("输出：
  - 《分学段课程框架》
  - 校本课程包")
end

%% ---------- 阶段5：教学实践 ----------
subgraph E_Stage[教学实践与迭代]
  E1[输入] --> E2[方法]
  E2[方法] --> E3[输出]
  
  E1("输入：
  - 实验校试点
  （满族小学等）")
  
  E2("方法：
  - 行动研究循环
  - 课例研究")
  
  E3("输出：
  - 《典型课例集》
  - 优化策略集")
end

%% ---------- 阶段6：评价开发 ----------
subgraph F_Stage[评价机制开发]
  F1[输入] --> F2[方法]
  F2[方法] --> F3[输出]
  
  F1("输入：
  - 学生素养目标
  （文化认同/实践能力）")
  
  F2("方法：
  - 混合评价
  （档案袋+量表）
  - 德尔菲法")
  
  F3("输出：
  - 《评价标准》
  - 学生作品库")
end

%% ---------- 阶段7：成果推广 ----------
subgraph G_Stage[成果推广与应用]
  G1[输入] --> G2[方法]
  G2[方法] --> G3[输出]
  
  G1("输入：
  - 已验证课程模式")
  
  G2("方法：
  - 区域辐射（教研/培训）
  - 数字化共享")
  
  G3("输出：
  - 出版教材
  - 跨区域合作网络")
end

%% 样式定义
classDef input fill:#e6f3ff,stroke:#4d90fe;
classDef method fill:#fff2cc,stroke:#f6b26b;
classDef output fill:#d9ead3,stroke:#6aa84f;
linkStyle 0,1,2,3,4,5,6 stroke:#999,stroke-width:2px;
