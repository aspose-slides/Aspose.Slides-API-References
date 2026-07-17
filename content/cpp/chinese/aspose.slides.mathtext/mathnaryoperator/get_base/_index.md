---
title: get_Base()
second_title: Aspose.Slides for C++ API 参考
description: Base 参数
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() 方法


Base 参数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## 备注


示例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathNaryOperator](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)