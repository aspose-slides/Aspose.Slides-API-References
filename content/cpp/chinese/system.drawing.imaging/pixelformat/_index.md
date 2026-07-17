---
title: PixelFormat
second_title: Aspose.Slides C++ API 参考
description: 指定像素的颜色数据格式。
type: docs
weight: 326
url: /zh/system.drawing.imaging/pixelformat/
---
## PixelFormat 枚举

指定像素的颜色数据格式。

```cpp
enum class PixelFormat
```

### Values

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Indexed | 65536 | 指定像素数据包含颜色索引值，这意味着它们是系统颜色表中颜色的索引。 |
| Gdi | 131072 | 指定像素数据包含 GDI 颜色。 |
| Alpha | 262144 | 指定像素数据包含未预乘的 alpha 值。 |
| PAlpha | 524288 | 指定像素数据包含预乘的 alpha 值。 |
| Extended | 1048576 | 保留。 |
| Canonical | 2097152 | 指定每像素 32 位的像素格式，包含 24 位颜色深度和 8 位 alpha 通道。 |
| Undefined | 0 | 指定像素格式未定义。 |
| DontCare | 0 | 像素格式未指定。 |
| Format1bppIndexed | n/a | 指定像素格式为每像素 1 位的索引颜色。 |
| Format4bppIndexed | n/a | 指定像素格式为每像素 4 位的索引颜色。 |
| Format8bppIndexed | n/a | 指定像素格式为每像素 8 位的索引颜色。 |
| Format16bppGrayScale | n/a | 指定像素格式为每像素 16 位。颜色信息提供 65536 种灰度。 |
| Format16bppRgb555 | n/a | 指定像素格式为每像素 16 位，其中红、绿、蓝分量各占 5 位，剩余位未使用。 |
| Format16bppRgb565 | n/a | 指定像素格式为每像素 16 位，其中红色占 5 位，绿色占 6 位，蓝色占 5 位。 |
| Format16bppArgb1555 | n/a | 指定像素格式为每像素 16 位，其中红、绿、蓝分量各占 5 位，alpha 占 1 位。 |
| Format24bppRgb | n/a | 指定像素格式为每像素 24 位，其中红、绿、蓝分量各占 8 位。 |
| Format32bppRgb | n/a | 指定像素格式为每像素 32 位，其中红、绿、蓝分量各占 8 位，剩余 8 位未使用。 |
| Format32bppArgb | n/a | 指定像素格式为每像素 32 位，其中红、绿、蓝分量各占 8 位，alpha 占 8 位。 |
| Format32bppPArgb | n/a | 指定像素格式为每像素 32 位，其中红、绿、蓝分量各占 8 位，alpha 占 8 位。红、绿、蓝分量根据 alpha 分量的值进行预乘。 |
| Format48bppRgb | n/a | 指定像素格式为每像素 48 位，其中红、绿、蓝分量各占 16 位。 |
| Format64bppArgb | n/a | 指定像素格式为每像素 64 位，其中红、绿、蓝分量各占 16 位，alpha 占 16 位。 |
| Format64bppPArgb | n/a | 指定像素格式为每像素 64 位，其中红、绿、蓝分量各占 16 位，alpha 占 16 位。红、绿、蓝分量根据 alpha 分量的值进行预乘。 |
| Format32bppCMYK | n/a | 指定像素格式为每像素 32 位，其中青色、品红、黄色和键（黑）分量各占 8 位。 |
| Max | 16 | 此枚举的最大值。 |

## 另见

* 命名空间 [System::Drawing::Imaging](../)
* 库 [Aspose.Slides](../../)