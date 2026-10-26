---
title: set_ColumnGap()
second_title: Aspose.Slides for C++ API 參考文件
description: "矩陣中欄位之間的水平間距值；如果 ColumnGapRule 設為 3 (\"Exactly\")，則單位以 twips (1/20 點) 來解釋。如果 ColumnGapRule 設為 4 (\"Multiple\")，則單位以 0.5 em 增量的倍數來解釋。其他情況則忽略。預設值：0"
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) 方法


矩陣中欄位之間的水平間距值；如果 ColumnGapRule 設為 3 (\"Exactly\")，則單位以 twips (1/20 點) 來解釋。如果 ColumnGapRule 設為 4 (\"Multiple\")，則單位以 0.5 em 增量的倍數來解釋。其他情況則忽略。預設值：0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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