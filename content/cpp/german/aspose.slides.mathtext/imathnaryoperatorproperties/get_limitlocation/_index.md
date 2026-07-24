---
title: get_LimitLocation()
second_title: Aspose.Slides für C++ API-Referenz
description: Der Ort der Grenzen (Tief- und Hochstellung)
type: docs
weight: 27
url: /de/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() Methode


Der Ort der Grenzen (Tief- und Hochstellung)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Hinweise


Beispiel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Siehe auch

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Klasse [IMathNaryOperatorProperties](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)