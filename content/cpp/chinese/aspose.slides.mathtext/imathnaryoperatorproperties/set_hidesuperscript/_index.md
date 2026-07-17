---
title: set_HideSuperscript()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏上标
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesuperscript/
---
## IMathNaryOperatorProperties::set_HideSuperscript(bool) 方法

隐藏上标

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSuperscript(bool value)=0
```

## 备注

示例:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## 另请参见

* 类 [IMathNaryOperatorProperties](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)