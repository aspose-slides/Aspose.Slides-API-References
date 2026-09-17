---
title: CompressionLevel enumeration
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/compressionlevel/
---
## CompressionLevel 枚举

指定 OpenXML 文件的 ZIP 压缩级别。  
更高的级别提供更好的压缩，但处理速度会更慢。

The CompressionLevel type exposes the following members:

## 字段

| 字段 | 描述 |
| :- | :- |
| NONE | 不应用压缩。文件保持原样存储。 |
| LEVEL1 | 以最低的压缩率实现最快的压缩。 |
| LEVEL2 | 较快的压缩，压缩率比 [`CompressionLevel.LEVEL1`](/slides/python-net/zh/aspose.slides.export/compressionlevel/LEVEL1) 略好。 |
| LEVEL3 | 提供比 [`CompressionLevel.LEVEL2`](/slides/python-net/zh/aspose.slides.export/compressionlevel/LEVEL2) 更好的压缩，性能影响适中。 |
| LEVEL4 | 提供比 [`CompressionLevel.LEVEL3`](/slides/python-net/zh/aspose.slides.export/compressionlevel/LEVEL3) 更好的压缩。 |
| LEVEL5 | 在 [`CompressionLevel.LEVEL4`](/slides/python-net/zh/aspose.slides.export/compressionlevel/LEVEL4) 的基础上进一步提升压缩率，但需要额外的处理时间。 |
| LEVEL6 | 标准压缩，在压缩速度和文件大小之间提供良好的平衡。<br/> 默认压缩级别。 |
| LEVEL7 | 提供比 [`CompressionLevel.LEVEL6`](/slides/python-net/zh/aspose.slides.export/compressionlevel/LEVEL6) 更高的压缩率，但处理速度更慢。 |
| LEVEL8 | 提供比 [`CompressionLevel.LEVEL7`](/slides/python-net/zh/aspose.slides.export/compressionlevel/LEVEL7) 更高的压缩率。 |
| LEVEL9 | 最大压缩。生成最小的文件大小，但处理速度最慢。 |

### 另请参见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)