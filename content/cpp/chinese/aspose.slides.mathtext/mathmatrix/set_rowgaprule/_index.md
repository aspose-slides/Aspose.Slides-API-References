---
title: set_RowGapRule()
second_title: Aspose.Slides for C++ API 参考
description: "矩阵行之间的垂直间距类型；垂直间距单位可以是行或点（以 twips 为单位存储）。默认值：SingleSpacingGap (0)"
type: docs
weight: 170
url: /zh/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) 方法

矩阵行之间的垂直间距类型；垂直间距单位可以是行或点（以 twips 为单位存储）。默认值：SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另请参见

* Enum [MathSpacingRules](../../mathspacingrules/)
* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)