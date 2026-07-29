---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Basargument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathnaryoperator/get_base/
---
## IMMathNaryOperator::get_Base() metod


Basargument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Base()=0
```

## Anmärkningar


Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathNaryOperator](../)
* Namnområde [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)