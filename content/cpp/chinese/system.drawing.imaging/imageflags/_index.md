---
title: ImageFlags
second_title: Aspose.Slides for C++ API 参考
description: 表示 Image 对象所表示的像素数据的属性。
type: docs
weight: 274
url: /zh/system.drawing.imaging/imageflags/
---
## ImageFlags 枚举

表示 [Image](../../system.drawing/image/) 对象所表示的像素数据的属性。

```cpp
enum class ImageFlags
```

### 取值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | 可缩放。 |
| HasAlpha | 2 | 包含 alpha 信息。 |
| HasTranslucent | 4 | 存在大于 0 且小于 255 的 alpha 值。 |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | 像素数据以 RGB 颜色空间表示。 |
| ColorSpaceCmyk | 32 | 像素数据以 CMYK 颜色空间表示。 |
| ColorSpaceGray | 64 | 像素数据为灰度。 |
| ColorSpaceYcbcr | 128 | 像素数据以 YCBCR 颜色空间表示。 |
| ColorSpaceYcck | 256 | 像素数据以 YCCK 颜色空间表示。 |
| HasRealDpi | 4096 | 图像中存储了 DPI 信息。 |
| HasRealPixelSize | 8192 | 图像中存储了像素的大小。 |
| ReadOnly | 65536 | 像素数据为只读。 |
| Caching | 131072 | 可缓存以加快访问。 |

## 另请参见

* 命名空间 [System::Drawing::Imaging](../)
* 库 [Aspose.Slides](../../)