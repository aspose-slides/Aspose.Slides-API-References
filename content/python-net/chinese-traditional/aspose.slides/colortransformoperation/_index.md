---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/colortransformoperation/
---
## ColorTransformOperation 列舉

定義顏色轉換操作。

ColorTransformOperation 類型公開以下成員：

## 欄位

| 欄位 | 說明 |
| :- | :- |
| TINT | 為顏色加上色調。參數的範圍為 0（原始顏色）至 1（白色）。 |
| SHADE | 將顏色變暗。參數的範圍為 0（原始顏色）至 1（黑色）。 |
| COMPLEMENT | 將顏色變更為 RGB 補色。<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | 將顏色變更為反相顏色。<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | 將顏色變更為具有相同亮度的灰色。參數將被忽略。 |
| SET_ALPHA | 定義顏色的 alpha 成分。參數的範圍為 0（透明）至 1（不透明）。 |
| ADD_ALPHA | 將參數值加到顏色的 alpha 成分。參數的範圍為 -1 至 1。 |
| MULTIPLY_ALPHA | 將 alpha 成分乘以參數值。 |
| SET_HUE | 將顏色的色相成分變更為參數值。參數的範圍為 0 至 360。 |
| ADD_HUE | 將參數值加到顏色的色相成分。參數的範圍為 -360 至 360。 |
| MULTIPLY_HUE | 將色相成分乘以參數值。 |
| SET_SATURATION | 將顏色的飽和度成分變更為參數值。參數的範圍為 0 至 1。 |
| ADD_SATURATION | 將參數值加到顏色的飽和度成分。參數的範圍為 -1 至 1。 |
| MULTIPLY_SATURATION | 將飽和度成分乘以參數值。 |
| SET_LUMINANCE | 將顏色的亮度成分變更為參數值。參數的範圍為 0 至 1。 |
| ADD_LUMINANCE | 將參數值加到顏色的亮度成分。參數的範圍為 -1 至 1。 |
| MULTIPLY_LUMINANCE | 將亮度成分乘以參數值。 |
| SET_RED | 將顏色的紅色成分變更為參數值。參數的範圍為 0 至 1。 |
| ADD_RED | 將參數值加到顏色的紅色成分。參數的範圍為 -1 至 1。 |
| MULTIPLY_RED | 將紅色成分乘以參數。 |
| SET_GREEN | 將顏色的綠色成分變更為參數值。參數的範圍為 0 至 1。 |
| ADD_GREEN | 將參數加到顏色的綠色成分。參數的範圍為 -1 至 1。 |
| MULTIPLY_GREEN | 將綠色成分乘以參數值。 |
| SET_BLUE | 將顏色的藍色成分變更為參數值。參數的範圍為 0 至 360。 |
| ADD_BLUE | 將參數值加到顏色的藍色成分。參數的範圍為 -1 至 1。 |
| MULTIPLY_BLUE | 將藍色成分乘以參數值。 |
| GAMMA | Gamma 校正。參數將被忽略。 |
| INVERSE_GAMMA | 反向 Gamma 校正。參數將被忽略。 |

### 參見
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)