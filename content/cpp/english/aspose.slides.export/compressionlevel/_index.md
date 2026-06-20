---
title: CompressionLevel
second_title: Aspose.Slides for C++ API Reference
description: Specifies ZIP compression levels for OpenXML file. Higher levels provide better compression at the cost of slower processing.
type: docs
weight: 846
url: /aspose.slides.export/compressionlevel/
---
## CompressionLevel enum


Specifies ZIP compression levels for OpenXML file. Higher levels provide better compression at the cost of slower processing.

```cpp
enum class CompressionLevel
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | No compression is applied. Files are stored as-is. |
| Level1 | 1 | Fastest compression with the lowest compression ratio. |
| Level2 | 2 | Faster compression with slightly better compression ratio than [CompressionLevel::Level1](./). |
| Level3 | 3 | Provides better compression than [CompressionLevel::Level2](./) with moderate performance impact. |
| Level4 | 4 | Provides better compression than [CompressionLevel::Level3](./). |
| Level5 | 5 | Provides improved compression over [CompressionLevel::Level4](./) with additional processing time. |
| Level6 | 6 | Standard compression, offering a good balance between compression speed and file size. The default compression level. |
| Level7 | 7 | Provides higher compression than [CompressionLevel::Level6](./) with slower processing. |
| Level8 | 8 | Provides higher compression than [CompressionLevel::Level7](./). |
| Level9 | 9 | Maximum compression. Produces the smallest file size with the slowest processing speed. |

## See Also

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)