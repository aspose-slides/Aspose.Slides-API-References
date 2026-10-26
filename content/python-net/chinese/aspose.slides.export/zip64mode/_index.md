---
title: Zip64Mode enumeration
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/zip64mode/
---
## Zip64Mode 枚举

指定何时对 OpenXML 文件使用 ZIP64 格式扩展。

Zip64Mode 类型公开以下成员：

## 字段

| 字段 | 描述 |
| :- | :- |
| NEVER | 不要使用 ZIP64 格式扩展。 |
| IF_NECESSARY | 如有必要，使用 ZIP64 格式扩展。 |
| ALWAYS | 始终使用 ZIP64 格式扩展。 |


### 备注

OpenXML 文件是一个 ZIP 存档，对文件的未压缩大小有 4 GB (2^32 字节) 的限制， 
            压缩大小和存档的总大小也受 4 GB 限制，且存档中最多只能包含 65,535 (2^16-1) 个文件。 
            ZIP64 格式扩展将这些限制提升至 2^64。


### 另请参阅
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)