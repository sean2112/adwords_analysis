# Adwords Data Analysis

本项目为个人数据分析学习项目，围绕 Google Adwords 数据展开完整的数据分析流程实践，涵盖数据清洗、建模、查询分析与可视化展示。

---

## 目录

- [项目简介](#项目简介)
- [数据来源](#数据来源)
- [项目结构](#项目结构)
- [阶段内容](#阶段内容)
- [能力体现](#能力体现)

---

## 项目简介

本项目完成了一个完整的数据分析闭环：

Excel → Python → MySQL → Power BI

主要内容包括：

- 数据清洗与标准化
- ETL 处理流程
- 数据库建模（星型模型）
- SQL 查询分析
- Power BI 数据建模与可视化
- 转化率与 RFM 分析

---

## 数据来源

本项目原始数据来源于以下公开仓库：

https://github.com/AdityakumarDA/Adword-Data-Analysis

本仓库仅用于个人学习与技术实践展示。

---

## 项目结构

```
adwords_analysis
│
├── 总结笔记
│   ├── Excel.md
│   ├── python.md
│   ├── MySQL.md
│   └── Power BI.md
│
├── 项目文件
│   ├── Raw_data.xlsx
│   ├── Raw_data_work.xlsx
│   ├── adwords_etl.ipynb
│   ├── adwords_analysis.sql
│   ├── adwords_analysis_dashboard.pbix
│   ├── website_traffic_data.csv
│   ├── keyword.csv
│   ├── keyword_difficulty.csv
│   └── search_volume.csv
```

---

## 阶段内容

### Excel 阶段

- 数据理解
- 字段分类
- 指标口径统一
- 数据质量检查

对应文件：

- `Excel.md`
- `Raw_data_work.xlsx`

---

### Python 阶段

- Pandas 数据清洗
- 类型转换
- 缺失值处理
- 去重与规则清洗
- 构建事实表与维表
- 生成代理主键

对应文件：

- `python.md`
- `adwords_etl.ipynb`

---

### MySQL 阶段

- 数据库建模
- 字段类型设计
- 主键 / 外键关系
- 索引优化
- 视图构建
- SQL 分析

对应文件：

- `MySQL.md`
- `adwords_analysis.sql`

---

### Power BI 阶段

- 数据模型关系设计
- 度量值（Measure）构建
- DAX 基础应用
- KPI 设计
- 时间趋势分析
- RFM 分析
- TopN 分析

对应文件：

- `Power BI.md`
- `adwords_analysis_dashboard.pbix`

---

## 能力体现

本项目体现的核心能力包括：

- 数据清洗与标准化能力
- 数据建模能力（星型模型）
- SQL 查询与性能意识
- DAX 度量构建能力
- 可视化逻辑设计能力
- 从原始数据到决策展示的完整分析流程

---

> 本项目为个人学习记录与能力展示。
