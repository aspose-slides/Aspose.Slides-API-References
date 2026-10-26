---
title: Zip64Mode
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/zip64mode/
---
## Zip64Mode 类

指定何时在 OpenXML 文件中使用 ZIP64 格式扩展。

OpenXML 文件是一个 ZIP 存档，对文件的未压缩大小、压缩大小以及存档的总大小都有 4 GB（2^32 字节）的限制，并且对存档中的文件数量限制为 65,535（2^16-1）个。

ZIP64 格式扩展将这些限制提升至 2^64。

## Constants

| 名称 | 值 | 描述 |
| --- | --- | --- |
[Never](#Never) | 0 | 不使用 ZIP64 格式扩展。 |
[IfNecessary](#IfNecessary) | 1 | 如有必要，使用 ZIP64 格式扩展。 |
[Always](#Always) | 2 | 始终使用 ZIP64 格式扩展。 |

---

### Never {#Never}
不使用 ZIP64 格式扩展。

---

### IfNecessary {#IfNecessary}
如有必要，使用 ZIP64 格式扩展。

---

### Always {#Always}
始终使用 ZIP64 格式扩展。

---