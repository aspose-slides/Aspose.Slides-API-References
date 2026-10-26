---
title: set_ColumnGapRule()
second_title: Aspose.Slides for C++ API 參考文件
description: "矩陣欄之間的水平間距類型；水平間距單位可以是 ems 或點（以 twips 儲存）。預設：SingleSpacingGap (0)"
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) 方法

矩陣列之間的水平間距類型；水平間距單位可以是 ems 或點（以 twips 儲存）。預設：SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## 備註

範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另見

* 列舉 [MathSpacingRules](../../mathspacingrules/)
* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)