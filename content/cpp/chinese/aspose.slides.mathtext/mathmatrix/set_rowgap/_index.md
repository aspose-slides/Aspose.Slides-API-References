---
title: set_RowGap()
second_title: Aspose.Slides for C++ API 参考
description: "矩阵行之间的垂直间距的值；如果 RowGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）如果 RowGapRule 设置为 4（\"Multiple\"），则单位解释为 half-lines。默认值：0"
type: docs
weight: 196
url: /zh/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) 方法

矩阵行之间的垂直间距的值；如果 RowGapRule 设置为 3（"Exactly"），则单位解释为 twips（1/20 点）如果 RowGapRule 设置为 4（"Multiple"），则单位解释为 half-lines。默认值：0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## 备注

示例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## 另见

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)