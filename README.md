# WordSpace Explorer 🌐📊

**词向量空间可视化工具** | ​**Word Vector Space Visualization Tool**

## 📖 简介 / Introduction

一个跨平台的交互式词向量可视化工具，使用 PCA 降维技术将词语投影到二维空间，支持中英文双语切换。  
An interactive cross-platform tool for visualizing word vectors in 2D space using PCA, with bilingual (ZH/EN) support.

---

## ✨ 功能特色 / Features

- ​**双语支持**  
  - 自动切换中文/英文词向量模型  
  - 界面语言自适应  
  - *Bilingual UI with auto-switching language models*

- ​**智能可视化**  
  - 基于 PCA 的二维投影  
  - 动态标注词语位置  
  - *PCA-based 2D projection with dynamic labels*

- ​**跨平台**  
  - 支持 macOS (.app)、Windows (.exe) 和 Linux  
  - *Cross-platform support for macOS, Windows & Linux*

---

## 🛠️ 安装指南 / Installation

### 前提条件 / Prerequisites
- Python 3.8+
- [Spacy 语言模型](https://spacy.io/usage/models)


# 下载语言模型 / Download language models
python -m spacy download zh_core_web_md  # 中文
python -m spacy download en_core_web_md  # English
