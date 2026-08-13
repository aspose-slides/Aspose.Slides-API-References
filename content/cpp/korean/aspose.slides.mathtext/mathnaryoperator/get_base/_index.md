---
title: get_Base()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Base 인수
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() 메서드


Base 인수

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## 비고


예제: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)