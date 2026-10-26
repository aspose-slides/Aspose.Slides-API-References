---
title: get_Superscript()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Superskript-Argument an, das zum Beispiel im Fall eines Integrals die obere Grenze festlegt.
type: docs
weight: 27
url: /de/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() Methode


Gibt ein Superskript-Argument an, das zum Beispiel im Fall eines Integrals die obere Grenze festlegt.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
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
* Klasse [MathNaryOperator](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)