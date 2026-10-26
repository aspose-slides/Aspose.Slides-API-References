---
title: get_RowGapRule()
second_title: Aspose.Slides for C++ API 參考
description: "矩陣中行與行之間的垂直間距類型；垂直間距單位可以是行或點（以 twips 為單位存儲）。預設值：SingleSpacingGap (0)"
type: docs
weight: 157
url: /zh-hant/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() 方法


矩陣中行與行之間的垂直間距類型；垂直間距單位可以是行或點（以 twips 為單位存儲）。預設值：SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## 備註


範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另見

* 列舉 [MathSpacingRules](../../mathspacingrules/)
* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)