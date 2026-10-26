---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API 參考
description: "矩陣行之間的垂直間距類型；垂直間距單位可以是行或點（以 twips 為單位存儲）。預設值：SingleSpacingGap (0)"
type: docs
weight: 170
url: /zh-hant/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) 方法


矩陣行之間的垂直間距類型；垂直間距單位可以是行或點（以 twips 為單位存儲）。預設值：SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## 備註


範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另請參閱

* 列舉 [MathSpacingRules](../../mathspacingrules/)
* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)