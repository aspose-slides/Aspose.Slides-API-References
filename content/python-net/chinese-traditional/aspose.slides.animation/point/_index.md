---
title: Point class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.animation/point/
---
## Point 類別

表示動畫點。

Point 類型公開以下成員：

## 建構子

| 建構子 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.animation/point/__init__/#) | 預設建構子。 |
| [`__init__(self, time, value, formula)`](/slides/python-net/zh-hant/aspose.slides.animation/point/__init__/#float-any-str) | 使用時間、值與公式建立動畫點。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`time`](/slides/python-net/zh-hant/aspose.slides.animation/point/time/) | 表示時間值。<br/>            讀寫 **float**。 |
| [`value`](/slides/python-net/zh-hant/aspose.slides.animation/point/value/) | 表示點的值。<br/>            僅限: bool, ColorFormat, float, int, string。<br/>            讀寫 **any**。 |
| [`formula`](/slides/python-net/zh-hant/aspose.slides.animation/point/formula/) | 公式可在 values、from、to、by 屬性中組成，包含以下內容：<br/>            標準算術運算子: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            常數: ‘pi’ ‘e’<br/>            條件運算子: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            比較運算子: '==', '>=', '', '!=', '!'<br/>            三角函數運算子: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            自然對數 ‘ln()’<br/>            屬性參照（主機支援的屬性）<br/>            <br/>            例如: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            讀寫 **str**。 |

### 另見
* 模組 [`aspose.slides.animation`](/slides/python-net/zh-hant/aspose.slides.animation)
* 函式庫 [`Aspose.Slides`](/slides/python-net)