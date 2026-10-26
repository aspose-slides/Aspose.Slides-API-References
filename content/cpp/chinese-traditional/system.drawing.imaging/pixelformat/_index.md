---
title: PixelFormat
second_title: Aspose.Slides for C++ API 參考文件
description: 指定像素的顏色資料格式。
type: docs
weight: 326
url: /zh-hant/system.drawing.imaging/pixelformat/
---
## PixelFormat 列舉

指定像素的顏色資料格式。

```cpp
enum class PixelFormat
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Indexed | 65536 | 指定像素資料包含顏色索引值，這表示它們是系統色彩表中顏色的索引。 |
| Gdi | 131072 | 指定像素資料包含 GDI 顏色。 |
| Alpha | 262144 | 指定像素資料包含未預先乘算的 alpha 值。 |
| PAlpha | 524288 | 指定像素資料包含預先乘算的 alpha 值。 |
| Extended | 1048576 | 保留。 |
| Canonical | 2097152 | 指定每像素 32 位元的像素格式，具有 24 位元的色彩深度和 8 位元的 alpha 通道。 |
| Undefined | 0 | 指定像素格式未定義。 |
| DontCare | 0 | 未指定像素格式。 |
| Format1bppIndexed | n/a | 指定像素格式為每像素 1 位元的索引色。 |
| Format4bppIndexed | n/a | 指定像素格式為每像素 4 位元的索引色。 |
| Format8bppIndexed | n/a | 指定像素格式為每像素 8 位元的索引色。 |
| Format16bppGrayScale | n/a | 指定像素格式為每像素 16 位元。色彩資訊指定 65536 種灰階。 |
| Format16bppRgb555 | n/a | 指定像素格式為每像素 16 位元，紅、綠、藍每個分量各 5 位元，剩餘位元未使用。 |
| Format16bppRgb565 | n/a | 指定像素格式為每像素 16 位元，紅色 5 位元，綠色 6 位元，藍色 5 位元。 |
| Format16bppArgb1555 | n/a | 指定像素格式為每像素 16 位元，紅、綠、藍每個分量各 5 位元，且有 1 位元的 alpha。 |
| Format24bppRgb | n/a | 指定像素格式為每像素 24 位元，紅、綠、藍每個分量各 8 位元。 |
| Format32bppRgb | n/a | 指定像素格式為每像素 32 位元，紅、綠、藍每個分量各 8 位元，剩餘 8 位元未使用。 |
| Format32bppArgb | n/a | 指定像素格式為每像素 32 位元，紅、綠、藍每個分量各 8 位元，且有 8 位元的 alpha。 |
| Format32bppPArgb | n/a | 指定像素格式為每像素 32 位元，紅、綠、藍每個分量各 8 位元，且有 8 位元的 alpha。紅、綠、藍分量會依照 alpha 分量的值預先乘算。 |
| Format48bppRgb | n/a | 指定像素格式為每像素 48 位元，紅、綠、藍每個分量各 16 位元。 |
| Format64bppArgb | n/a | 指定像素格式為每像素 64 位元，紅、綠、藍每個分量各 16 位元，且有 16 位元的 alpha。 |
| Format64bppPArgb | n/a | 指定像素格式為每像素 64 位元，紅、綠、藍每個分量各 16 位元，且有 16 位元的 alpha。紅、綠、藍分量會依照 alpha 分量的值預先乘算。 |
| Format32bppCMYK | n/a | 指定像素格式為每像素 32 位元，青色、洋紅、黃色與黑色（Key）每個分量各 8 位元。 |
| Max | 16 | 此列舉的最大值。 |

## 另見

* 命名空間 [System::Drawing::Imaging](../)
* 函式庫 [Aspose.Slides](../../)