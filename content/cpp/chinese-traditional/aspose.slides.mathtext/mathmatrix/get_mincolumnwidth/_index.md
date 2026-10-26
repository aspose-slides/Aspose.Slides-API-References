---
title: get_MinColumnWidth()
second_title: Aspose.Slides for C++ API 參考文件
description: "最小欄寬，以 twip 為單位（1/20 個點）。間隙間距（亦稱為 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）會加到 MinColumnWidth，以決定總矩陣欄位間距（不同欄位相同邊緣之間的距離）。預設值：0."
type: docs
weight: 79
url: /zh-hant/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() 方法


最小欄寬，以 twip 為單位（1/20 個點） 間隙間距（亦稱為 \\u201CColumn Gap\\u201D 或 \\u201CGap Width\\u201D）會加到 MinColumnWidth 以決定總矩陣 [Column](../../../aspose.slides/column/) 間距（不同欄位相同邊緣之間的距離）。 預設值：0.

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
```

## 備註


範例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 另請參閱

* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)