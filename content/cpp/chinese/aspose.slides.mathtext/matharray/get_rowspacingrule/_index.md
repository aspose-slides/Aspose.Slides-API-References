---
title: get_RowSpacingRule()
second_title: Aspose.Slides for C++ API 参考
description: "数组元素之间的垂直间距类型 默认：SingleLineGap"
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/matharray/get_rowspacingrule/
---
## MathArray::get_RowSpacingRule() 方法

数组元素之间的垂直间距类型 默认：SingleLineGap

```cpp
MathRowSpacingRule Aspose::Slides::MathText::MathArray::get_RowSpacingRule() override
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## 另见

* Enum [MathRowSpacingRule](../../mathrowspacingrule/)
* Class [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)