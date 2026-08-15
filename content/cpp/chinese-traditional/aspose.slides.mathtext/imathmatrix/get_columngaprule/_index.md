---
title: get_ColumnGapRule()
second_title: Aspose.Slides for C++ API 參考
description: "矩陣中欄位之水平間距的類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。預設：SingleSpacingGap (0)"
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() 方法

矩陣中欄位之水平間距的類型；水平間距單位可以是 ems 或 points（以 twips 儲存）。預設：SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## 備註

範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另請參閱

* 列舉 [MathSpacingRules](../../mathspacingrules/)
* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)