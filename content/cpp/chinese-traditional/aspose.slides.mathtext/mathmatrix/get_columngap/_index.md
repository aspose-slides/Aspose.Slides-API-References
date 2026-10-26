---
title: get_ColumnGap()
second_title: Aspose.Slides for C++ API 參考
description: "矩陣中欄之間的水平間距值；如果 ColumnGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 ColumnGapRule 設為 4（\"Multiple\"），則單位解釋為 0.5 em 增量的數量。其他情況將被忽略。預設值：0"
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() 方法


矩陣中欄之間的水平間距值；如果 ColumnGapRule 設為 3（\"Exactly\"），則單位解釋為 twips（1/20 點）；如果 ColumnGapRule 設為 4（\"Multiple\"），則單位解釋為 0.5 em 增量的數量。其他情況將被忽略。預設值：0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## 備註


範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## 另請參閱

* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)