---
title: set_ColumnGap()
second_title: Aspose.Slides for C++ API 參考
description: "矩陣中欄之水平間距的數值；如果 ColumnGapRule 設為 3（\"Exactly\"），則單位被解釋為 twips（1/20 點）；如果 ColumnGapRule 設為 4（\"Multiple\"），則單位被解釋為 0.5 em 增量的數量。其他情況下會被忽略。預設值：0"
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) 方法


矩陣中欄之水平間距的數值；如果 ColumnGapRule 設為 3（"Exactly"），則單位被解釋為 twips（1/20 點）；如果 ColumnGapRule 設為 4（"Multiple"），則單位被解釋為 0.5 em 增量的數量。其他情況下會被忽略。預設值：0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## 備註


範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## 另見

* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)