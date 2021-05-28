

## 简介
PaddleOCR旨在打造一套丰富、领先、且实用的OCR工具库，助力使用者训练出更好的模型，并应用落地。
## 注意
PaddleOCR同时支持动态图与静态图两种编程范式
- 动态图版本：dygraph分支（默认），需将paddle版本升级至2.0.0（[快速安装](./doc/doc_ch/installation.md)）
- 静态图版本：develop分支




## 文档教程
- [快速安装](./doc/doc_ch/installation.md)
- [中文OCR模型快速使用](./doc/doc_ch/quickstart.md)
- [代码组织结构](./doc/doc_ch/tree.md)
- 算法介绍
    - [文本检测](./doc/doc_ch/algorithm_overview.md)
    - [文本识别](./doc/doc_ch/algorithm_overview.md)
    - [PP-OCR Pipline](#PP-OCR)
- 模型训练/评估
    - [文本检测](./doc/doc_ch/detection.md)
    - [文本识别](./doc/doc_ch/recognition.md)
    - [方向分类器](./doc/doc_ch/angle_class.md)
    - [yml参数配置文件介绍](./doc/doc_ch/config.md)
- 预测部署
    - [基于pip安装whl包快速推理](./doc/doc_ch/whl.md)
    - [基于Python脚本预测引擎推理](./doc/doc_ch/inference.md)
    - [基于C++预测引擎推理](./deploy/cpp_infer/readme.md)
    - [服务化部署](./deploy/hubserving/readme.md)
    - [端侧部署](https://github.com/PaddlePaddle/PaddleOCR/blob/develop/deploy/lite/readme.md)
    - [Benchmark](./doc/doc_ch/benchmark.md)
- 数据集
    - [通用中英文OCR数据集](./doc/doc_ch/datasets.md)
    - [手写中文OCR数据集](./doc/doc_ch/handwritten_datasets.md)
    - [垂类多语言OCR数据集](./doc/doc_ch/vertical_and_multilingual_datasets.md)
- 数据标注与合成
    - [半自动标注工具PPOCRLabel](./PPOCRLabel/README_ch.md)
    - [数据合成工具Style-Text](./StyleText/README_ch.md)
    - [其它数据标注工具](./doc/doc_ch/data_annotation.md)
    - [其它数据合成工具](./doc/doc_ch/data_synthesis.md)
- [效果展示](#效果展示)
- FAQ
    - [【精选】OCR精选10个问题](./doc/doc_ch/FAQ.md)
    - [【理论篇】OCR通用37个问题](./doc/doc_ch/FAQ.md)
    - [【实战篇】PaddleOCR实战141个问题](./doc/doc_ch/FAQ.md)



