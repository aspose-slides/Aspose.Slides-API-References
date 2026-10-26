---
title: get_Subscript()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Subskript-Argument an, das zum Beispiel im Fall eines Integrals die untere Grenze festlegt
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() Methode


Gibt ein Index-Argument an, das beispielsweise im Fall eines Integrals die untere Grenze festlegt

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## Hinweise


Beispiel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)