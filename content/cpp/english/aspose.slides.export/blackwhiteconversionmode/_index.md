---
title: BlackWhiteConversionMode
second_title: Aspose.Slides for C++ API Reference
description: Provides options that control how slides' images will be converted to bitonal images.
type: docs
weight: 846
url: /aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum


Provides options that control how slides' images will be converted to bitonal images.

```cpp
enum class BlackWhiteConversionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | Specifies no conversion algorithm. The algorithm implemented in the TIFF codec will be used. (Default) |
| Dithering | 1 | Specifies the dithering algorithm (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Specifies the Floyd-Steinberg dithering algorithm. |
| Auto | 3 | Specifies the automatically calculated threshold algorithm (Otsu). |
| AutoOtsu | 4 | Specifies the automatically calculated Otsu's threshold algorithm. |
| Threshold25 | 5 | Specifies the static threshold algorithm (25%). |
| Threshold50 | 6 | Specifies the static threshold algorithm (50%). |
| Threshold75 | 7 | Specifies the static threshold algorithm (75%). |

## See Also

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)