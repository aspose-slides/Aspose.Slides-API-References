---
title: get_Superscript()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Superskript-Argument an, das zum Beispiel im Falle eines Integrals die obere Grenze festlegt.
type: docs
weight: 27
url: /de/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() Methode


Gibt ein Superskript-Argument an, das zum Beispiel im Falle eines Integrals die obere Grenze festlegt.

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## Hinweise


Beispiel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)