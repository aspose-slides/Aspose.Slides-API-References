---
title: get_RowGapRule()
second_title: Aspose.Slides 用于 C++ 的 API 参考
description: "矩阵行之间的垂直间距类型；垂直间距单位可以是行或点（以 twips 存储）。默认值：SingleSpacingGap (0)"
type: docs
weight: 157
url: /zh/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() 方法

矩阵行之间的垂直间距类型；垂直间距单位可以是行或点（以 twips 存储）。默认值：SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另请参见

* 枚举 [MathSpacingRules](../../mathspacingrules/)
* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)