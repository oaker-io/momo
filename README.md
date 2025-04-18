# 咪蒙公众号文章数据集

这个仓库包含了咪蒙公众号的全部历史文章数据，包括文章内容、阅读量等相关数据。

## 项目背景

本项目收集并整理了咪蒙公众号的所有历史文章，为了便于数据分析和研究，我们对原始PDF文件进行了处理，提取了纯文本内容。

## 数据结构

项目包含以下主要数据目录和文件：

### `/source_pdf`
- 包含原始PDF格式的文章文件
- 保留了完整的排版、图片等原始元素

### `/txt_output`
- 从PDF转换后的纯文本文件
- 去除了图片等多媒体元素，以减小文件体积
- 保留了文章的完整文字内容

### `merged.txt`
- 整合了所有文章的文本内容
- 经过清洗和格式化处理
- 适用于直接导入向量知识库
- 便于进行文本分析和数据挖掘

## 数据说明

- 文章总数：[待补充]
- 时间跨度：[待补充]
- 数据格式：纯文本（UTF-8编码）

## 使用说明

1. 如需查看原始文章格式，请参考 `/source_pdf` 目录
2. 如需进行文本分析，建议直接使用 `merged.txt`
3. 单篇文章的纯文本版本可在 `/txt_output` 目录中找到

## 注意事项

- 本数据集仅用于学习研究目的
- 请遵守相关法律法规，合理使用数据
- 原始内容的版权归原作者所有 