---
title: set_LimitLocation()
second_title: Aspose.Slides for C++ API-referentie
description: De locatie van limieten (subscript en superscript)
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) methode

De locatie van limieten (subscript en superscript)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Opmerkingen

Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Zie ook

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Klasse [MathNaryOperator](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)