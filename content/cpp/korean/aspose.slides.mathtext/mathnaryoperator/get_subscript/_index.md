---
title: get_Subscript()
second_title: Aspose.Slides for C++ API 참조
description: 예를 들어 적분의 경우와 같이 하한을 설정하는 첨자 인수를 지정합니다.
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() 메서드


예를 들어 적분의 경우와 같이, 하한을 설정하는 첨자 인수를 지정합니다.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## 비고


예: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)