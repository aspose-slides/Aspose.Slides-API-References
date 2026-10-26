---
title: set_ColumnGap()
second_title: Aspose.Slides for C++ API 参考
description: "矩阵中列之间的水平间距值；如果 ColumnGapRule 设置为 3 (\"Exactly\")，则单位解释为 twips（1/20 点）；如果 ColumnGapRule 设置为 4 (\"Multiple\")，则单位解释为 0.5 em 增量的数量。其他情况下被忽略。默认值：0"
type: docs
weight: 144
url: /zh/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) 方法


矩阵中列之间的水平间距值；如果 ColumnGapRule 设置为 3（"Exactly"），则单位解释为 twips（1/20 点）；如果 ColumnGapRule 设置为 4（"Multiple"），则单位解释为 0.5 em 的增量数。在其他情况下被忽略。默认值：0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## 备注


示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## 参见

* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)