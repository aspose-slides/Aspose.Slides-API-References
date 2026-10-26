---
title: set_RowSpacingRule()
second_title: Aspose.Slides for C++ API 参考
description: "数组元素之间的垂直间距类型 默认: SingleLineGap"
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/matharray/set_rowspacingrule/
---
## MathArray::set_RowSpacingRule(MathRowSpacingRule) 方法

数组元素之间的垂直间距类型 默认：SingleLineGap

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacingRule(MathRowSpacingRule value) override
```

## 备注

示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## 另见

* 枚举 [MathRowSpacingRule](../../mathrowspacingrule/)
* 类 [MathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)