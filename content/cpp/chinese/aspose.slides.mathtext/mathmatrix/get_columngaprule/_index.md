---
title: get_ColumnGapRule()
second_title: Aspose.Slides C++ API 参考
description: "矩阵列之间的水平间距类型；水平间距单位可以是 ems 或 points（以 twips 存储）。默认：SingleSpacingGap (0)"
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() 方法

矩阵列之间的水平间距类型；水平间距单位可以是 ems 或 points（以 twips 存储）。默认：SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## 备注

示例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另请参阅

* 枚举 [MathSpacingRules](../../mathspacingrules/)
* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)