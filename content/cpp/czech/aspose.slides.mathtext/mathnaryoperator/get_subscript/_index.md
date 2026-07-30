---
title: get_Subscript()
second_title: Aspose.Slides pro C++ referenci API
description: Určuje argument dolního indexu, který například v případě integrálu nastavuje dolní mez
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() metoda

Určuje argument dolního indexu, který například v případě integrálu nastavuje dolní mez

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Poznámky

Příklad:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)