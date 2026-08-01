---
title: get_LimitLocation()
second_title: Aspose.Slides voor C++ API-referentie
description: De locatie van limieten (subscript en superscript)
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() methode

De locatie van limieten (subscript en superscript)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Zie ook

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Klasse [IMathNaryOperatorProperties](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)