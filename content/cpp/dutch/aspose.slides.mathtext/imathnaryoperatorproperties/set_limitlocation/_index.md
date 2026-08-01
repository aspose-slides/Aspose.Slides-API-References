---
title: set_LimitLocation()
second_title: Aspose.Slides voor C++ API Referentie
description: De locatie van limieten (subscript en superscript)
type: docs
weight: 40
url: /nl/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) methode

De locatie van limieten (subscript en superscript)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
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
* Library [Aspose.Slides](../../../)