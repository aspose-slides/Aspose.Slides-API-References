---
title: set_HideSuperscript()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏上标
type: docs
weight: 157
url: /zh/aspose.slides.mathtext/mathnaryoperator/set_hidesuperscript/
---
## MathNaryOperator::set_HideSuperscript(bool) 方法


隐藏上标

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSuperscript(bool value) override
```

## 备注


示例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## 另请参阅

* 类 [MathNaryOperator](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)