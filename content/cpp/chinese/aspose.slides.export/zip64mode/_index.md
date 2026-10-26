---
title: Zip64Mode
second_title: Aspose.Slides for C++ API 参考
description: 指定何时对 OpenXML 文件使用 ZIP64 格式扩展。
type: docs
weight: 1119
url: /zh/aspose.slides.export/zip64mode/
---
## Zip64Mode 枚举

指定何时对 OpenXML 文件使用 ZIP64 格式扩展。

```cpp
enum class Zip64Mode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Never | 0 | 不使用 ZIP64 格式扩展。 |
| IfNecessary | 1 | 如有必要使用 ZIP64 格式扩展。 |
| Always | 2 | 始终使用 ZIP64 格式扩展。 |

## 备注

OpenXML 文件是一个 ZIP 存档，对文件的未压缩大小、压缩大小以及存档的总体大小都有 4 GB (2^32 字节) 的限制，且存档中的文件数量限制为 65,535 (2^16-1) 个。ZIP64 格式扩展将这些限制提升至 2^64。

## 另见

* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)