---
title: get_Base()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Argument Base
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() metoda


Argument Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathNaryOperator](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)