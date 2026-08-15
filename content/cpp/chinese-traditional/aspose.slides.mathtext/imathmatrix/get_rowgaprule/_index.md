---
title: get_RowGapRule()
second_title: Aspose.Slides for C++ API 參考文件
description: "矩陣中各列之垂直間距的類型；垂直間距單位可以是行或點（以 twips 儲存）。預設值：SingleSpacingGap (0)"
type: docs
weight: 157
url: /zh-hant/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() 方法

矩陣中各列之垂直間距的類型；垂直間距單位可以是行或點（以 twips 儲存）。預設值：SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```
## 備註

範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```
## 另請參閱

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)