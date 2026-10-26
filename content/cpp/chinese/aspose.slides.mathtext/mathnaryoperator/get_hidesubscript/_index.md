---
title: get_HideSubscript()
second_title: Aspose.Slides for C++ API 参考
description: 隐藏下标
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/mathnaryoperator/get_hidesubscript/
---
## MathNaryOperator::get_HideSubscript() 方法


隐藏下标

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSubscript() override
```

## 备注


示例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## 另请参阅

* 类 [MathNaryOperator](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)