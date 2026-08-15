---
title: ColorTransformOperation
second_title: Aspose.Slides for C++ API 參考
description: 定義顏色轉換操作。
type: docs
weight: 5747
url: /zh-hant/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enum

定義顏色轉換操作。

```cpp
enum class ColorTransformOperation
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Tint | 0 | 為顏色添加色調。參數的範圍在 0（原始顏色）到 1（白色）之間。 |
| Shade | 1 | 為顏色添加陰影。參數的範圍在 0（原始顏色）到 1（黑色）之間。 |
| Complement | 2 | 將顏色更改為 RGB 補色。m = Max(r, g, b); r = m - r; g = m - g; b = m - b; |
| Inverse | 3 | 將顏色更改為反相顏色。r = 1 - r; g = 1 - g; b = 1 - b; |
| Grayscale | 4 | 將顏色更改為具有相同亮度的灰色。參數被忽略。 |
| SetAlpha | 5 | 定義顏色的 Alpha 組件。參數的範圍在 0（透明）到 1（不透明）之間。 |
| AddAlpha | 6 | 將參數的值加到顏色的 Alpha 組件上。參數的範圍在 -1 到 1 之間。 |
| MultiplyAlpha | 7 | 將 Alpha 組件乘以參數的值。 |
| SetHue | 8 | 將顏色的色相組件更改為參數的值。參數的範圍在 0 到 360 之間。 |
| AddHue | 9 | 將參數的值加到顏色的色相組件上。參數的範圍在 -360 到 360 之間。 |
| MultiplyHue | 10 | 將色相組件乘以參數的值。 |
| SetSaturation | 11 | 將顏色的飽和度組件更改為參數的值。參數的範圍在 0 到 1 之間。 |
| AddSaturation | 12 | 將參數的值加到顏色的飽和度組件上。參數的範圍在 -1 到 1 之間。 |
| MultiplySaturation | 13 | 將飽和度組件乘以參數的值。 |
| SetLuminance | 14 | 將顏色的亮度組件更改為參數的值。參數的範圍在 0 到 1 之間。 |
| AddLuminance | 15 | 將參數的值加到顏色的亮度組件上。參數的範圍在 -1 到 1 之間。 |
| MultiplyLuminance | 16 | 將亮度組件乘以參數的值。 |
| SetRed | 17 | 將顏色的紅色組件更改為參數的值。參數的範圍在 0 到 1 之間。 |
| AddRed | 18 | 將參數的值加到顏色的紅色組件上。參數的範圍在 -1 到 1 之間。 |
| MultiplyRed | 19 | 將紅色組件乘以參數。 |
| SetGreen | 20 | 將顏色的綠色組件更改為參數的值。參數的範圍在 0 到 1 之間。 |
| AddGreen | 21 | 將參數加到顏色的綠色組件上。參數的範圍在 -1 到 1 之間。 |
| MultiplyGreen | 22 | 将綠色組件乘以參數的值。 |
| SetBlue | 23 | 将顏色的藍色組件更改為參數的值。參數的範圍在 0 到 360 之間。 |
| AddBlue | 24 | 将參數的值加到顏色的藍色組件上。參數的範圍在 -1 到 1 之間。 |
| MultiplyBlue | 25 | 将藍色組件乘以參數的值。 |
| Gamma | 26 | 伽瑪校正。參數被忽略。 |
| InverseGamma | 27 | 反向伽瑪校正。參數被忽略。 |

## 另請參閱

* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)