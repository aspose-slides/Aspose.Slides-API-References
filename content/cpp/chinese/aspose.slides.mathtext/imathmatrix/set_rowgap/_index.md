---
title: set_RowGap()
second_title: Aspose.Slides for C++ API 参考
description: "矩阵行之间的垂直间距值；如果 RowGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4（\"Multiple\"），则单位解释为半行。默认: 0"
type: docs
weight: 196
url: /zh/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) 方法

矩阵行之间的垂直间距值；如果 RowGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4（\"Multiple\"），则单位解释为半行。默认: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
```

## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## 另见

* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)