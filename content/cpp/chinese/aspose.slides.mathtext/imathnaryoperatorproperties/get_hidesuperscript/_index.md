---
title: get_HideSuperscript()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏上标
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesuperscript/
---
## IMathNaryOperatorProperties::get_HideSuperscript() 方法


隐藏上标

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSuperscript()=0
```

## 备注


示例： 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## 另见

* 类 [IMathNaryOperatorProperties](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)