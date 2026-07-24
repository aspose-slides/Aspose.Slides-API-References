---
title: get_Subscript()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Subskript-Argument an, das beispielsweise im Fall eines Integrals die untere Grenze festlegt
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() Methode

Gibt ein Subskript-Argument an, das beispielsweise im Fall eines Integrals die untere Grenze festlegt

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Bemerkungen

Beispiel:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)