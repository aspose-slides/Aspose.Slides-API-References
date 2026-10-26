---
title: BlackWhiteConversionMode
second_title: Aspose.Slides for C++ API 参考
description: 提供控制幻灯片图像如何转换为二值图像的选项。
type: docs
weight: 820
url: /zh/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode 枚举

Provides options that control how slides' images will be converted to bitonal images.

```cpp
enum class BlackWhiteConversionMode
```

### Values

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | 0 | Specifies no conversion algorithm. The algorithm implemented in the TIFF codec will be used. (Default) |
| Dithering | 1 | Specifies the dithering algorithm (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Specifies the Floyd-Steinberg dithering algorithm. |
| Auto | 3 | Specifies the automatically calculated threshold algorithm (Otsu). |
| AutoOtsu | 4 | Specifies the automatically calculated Otsu's threshold algorithm. |
| Threshold25 | 5 | Specifies the static threshold algorithm (25%). |
| Threshold50 | 6 | Specifies the static threshold algorithm (50%). |
| Threshold75 | 7 | Specifies the static threshold algorithm (75%). |

## 参见

* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)