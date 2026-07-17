---
title: get_ColumnGap()
second_title: Aspose.Slides for C++ API 参考
description: "矩阵列之间的水平间距值；如果 ColumnGapRule 设置为 3（\"Exactly\"），则单位解释为 twip（1/20 点）如果 ColumnGapRule 设置为 4（\"Multiple\"），则单位解释为 0.5 em 增量的数量。其他情况忽略。默认值：0"
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() 方法

矩阵列之间的水平间距值；如果 ColumnGapRule 设置为 3（"Exactly"），则单位解释为 twip（1/20 点）；如果 ColumnGapRule 设置为 4（"Multiple"），则单位解释为 0.5 em 增量的数量。其他情况忽略。默认值：0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## 另请参阅

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)