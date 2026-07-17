---
title: get_RowSpacingRule()
second_title: Aspose.Slides C++ API 参考
description: 数组元素之间的垂直间距类型
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/imatharray/get_rowspacingrule/
---
## IMathArray::get_RowSpacingRule() 方法


数组元素之间的垂直间距类型

```cpp
virtual MathRowSpacingRule Aspose::Slides::MathText::IMathArray::get_RowSpacingRule()=0
```

## 备注


示例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## 另请参见

* 枚举 [MathRowSpacingRule](../../mathrowspacingrule/)
* 类 [IMathArray](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)