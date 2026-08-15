---
title: ImageFlags
second_title: Aspose.Slides for C++ API 參考文件
description: 代表由 Image 物件所表示的像素資料的屬性。
type: docs
weight: 274
url: /zh-hant/system.drawing.imaging/imageflags/
---
## ImageFlags 列舉

表示由 [Image](../../system.drawing/image/) 物件所表示的像素資料的屬性。

```cpp
enum class ImageFlags
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | 可擴展。 |
| HasAlpha | 2 | 包含 alpha 資訊。 |
| HasTranslucent | 4 | 有大於 0 且小於 255 的 alpha 值。 |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | 像素資料以 RGB 色彩空間表示。 |
| ColorSpaceCmyk | 32 | 像素資料以 CMYK 色彩空間表示。 |
| ColorSpaceGray | 64 | 像素資料為灰階。 |
| ColorSpaceYcbcr | 128 | 像素資料以 YCBCR 色彩空間表示。 |
| ColorSpaceYcck | 256 | 像素資料以 YCCK 色彩空間表示。 |
| HasRealDpi | 4096 | 影像中存有 DPI 資訊。 |
| HasRealPixelSize | 8192 | 影像中存有像素大小資訊。 |
| ReadOnly | 65536 | 像素資料為唯讀。 |
| Caching | 131072 | 可快取以提升存取速度。 |

## 另見

* 名稱空間 [System::Drawing::Imaging](../)
* 函式庫 [Aspose.Slides](../../)