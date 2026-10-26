---
title: get_RowGapRule()
second_title: Aspose.Slides C++ API 参考
description: "矩阵行之间垂直间距的类型；垂直间距单位可以是行或点（以 twips 存储）。默认：SingleSpacingGap (0)"
type: docs
weight: 157
url: /zh/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() 方法


矩阵行之间垂直间距的类型；垂直间距单位可以是行或点（以 twips 存储）。默认：SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## 备注


示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## 另见

* 枚举 [MathSpacingRules](../../mathspacingrules/)
* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)