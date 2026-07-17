---
title: get_RowGap()
second_title: Aspose.Slides for C++ API 参考
description: "矩阵行之间的垂直间距的数值；如果 RowGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4（\"Multiple\"），则单位解释为半行。默认值：0"
type: docs
weight: 183
url: /zh/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() 方法

矩阵行之间的垂直间距的数值；如果 RowGapRule 设置为 3（"Exactly"），则单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4（"Multiple"），则单位解释为半行。默认值：0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## 另请参见

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)