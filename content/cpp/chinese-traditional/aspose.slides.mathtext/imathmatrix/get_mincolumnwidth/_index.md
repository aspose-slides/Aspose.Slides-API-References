---
title: get_MinColumnWidth()
second_title: Aspose.Slides for C++ API 參考
description: "最小列寬，以 twips 為單位（每點的 1/20）。間距（亦稱為 \u201CColumn Gap\u201D 或 \u201CGap Width\u201D）會加到 MinColumnWidth 以確定總體 Matrix Column Spacing（不同列相同邊緣之間的距離）。預設值：0."
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() 方法


最小列寬，以 twips 為單位（每點的 1/20）。間距（亦稱為 \u201CColumn Gap\u201D 或 \u201CGap Width\u201D）會加到 MinColumnWidth 以確定總體 Matrix [Column](../../../aspose.slides/column/) Spacing（不同列相同邊緣之間的距離）。預設值：0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## 備註


範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 另見

* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)