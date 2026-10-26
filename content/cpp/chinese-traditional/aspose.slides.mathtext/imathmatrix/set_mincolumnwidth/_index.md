---
title: set_MinColumnWidth()
second_title: Aspose.Slides for C++ API 參考文件
description: "最小欄寬，以 twips 為單位（1/20 點）間距（亦稱 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）會加到 MinColumnWidth 以確定總矩陣欄位間距（不同欄位相同邊緣之間的距離）。預設值：0."
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) 方法


最小欄寬，以 twips 為單位（1/20 點）。間距（亦稱 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）會加到 MinColumnWidth 上，以確定矩陣的總 [Column](../../../aspose.slides/column/) 間距（不同欄位相同邊緣之間的距離）。預設值：0.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
```

## 備註


範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 另請參閱

* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)