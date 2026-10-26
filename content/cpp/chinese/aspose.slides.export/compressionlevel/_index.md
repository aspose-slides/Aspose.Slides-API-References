---
title: CompressionLevel
second_title: 适用于 C++ 的 Aspose.Slides API 参考
description: 指定 OpenXML 文件的 ZIP 压缩级别。更高的级别在提供更好压缩的同时，会导致处理速度变慢。
type: docs
weight: 846
url: /zh/aspose.slides.export/compressionlevel/
---
## CompressionLevel 枚举

指定 OpenXML 文件的 ZIP 压缩级别。更高的级别在提供更好压缩的同时，会导致处理速度变慢。

```cpp
enum class CompressionLevel
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 未应用压缩。文件保持原样存储。 |
| Level1 | 1 | 最快的压缩，压缩比最低。 |
| Level2 | 2 | 比 [CompressionLevel::Level1](./) 稍快的压缩，压缩比略好。 |
| Level3 | 3 | 相较于 [CompressionLevel::Level2](./) 提供更好的压缩，性能影响适中。 |
| Level4 | 4 | 相较于 [CompressionLevel::Level3](./) 提供更好的压缩。 |
| Level5 | 5 | 相较于 [CompressionLevel::Level4](./) 提供更好的压缩，但需要额外的处理时间。 |
| Level6 | 6 | 标准压缩，在压缩速度和文件大小之间取得良好平衡。默认压缩级别。 |
| Level7 | 7 | 相较于 [CompressionLevel::Level6](./) 提供更高的压缩，但处理速度较慢。 |
| Level8 | 8 | 相较于 [CompressionLevel::Level7](./) 提供更高的压缩。 |
| Level9 | 9 | 最大压缩率。产生最小的文件尺寸，但处理速度最慢。 |

## 另请参见

* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)