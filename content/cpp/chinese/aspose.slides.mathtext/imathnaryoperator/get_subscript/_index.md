---
title: get_Subscript()
second_title: Aspose.Slides C++ API 参考
description: 指定一个下标参数，例如在积分的情况下，设置下限
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() 方法

指定一个下标参数，例如在积分的情况下，设置下限

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## 备注

示例：
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [IMathNaryOperator](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)