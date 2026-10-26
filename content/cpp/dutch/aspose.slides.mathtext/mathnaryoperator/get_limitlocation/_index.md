---
title: get_LimitLocation()
second_title: Aspose.Slides voor C++ API Referentie
description: De locatie van limieten (subscript en superscript)
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() methode


De locatie van limieten (subscript en superscript)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
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
* Library [Aspose.Slides](../../../)