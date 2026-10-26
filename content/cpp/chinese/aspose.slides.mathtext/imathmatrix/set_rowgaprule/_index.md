---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API 参考
description: "矩阵行之间的垂直间距类型；垂直间距单位可以是行或点（以 twips 存储）。默认值：SingleSpacingGap (0)"
type: docs
weight: 170
url: /zh/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) method


矩阵行之间的垂直间距类型；垂直间距单位可以是行或点（以 twips 存储）。默认值：SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## 备注


示例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另请参阅

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)