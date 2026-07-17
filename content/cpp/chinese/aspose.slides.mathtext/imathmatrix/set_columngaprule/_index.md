---
title: set_ColumnGapRule()
second_title: Aspose.Slides for C++ API 参考
description: "矩阵列之间的水平间距类型；水平间距单位可以是 ems 或 points（以 twips 存储）。默认：SingleSpacingGap (0)"
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) method

矩阵列之间的水平间距类型；水平间距单位可以是 ems 或 points（以 twips 存储）。默认：SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另请参见

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)