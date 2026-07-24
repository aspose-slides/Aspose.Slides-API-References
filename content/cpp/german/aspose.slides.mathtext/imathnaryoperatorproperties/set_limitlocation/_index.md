---
title: set_LimitLocation()
second_title: Aspose.Slides für C++ API-Referenz
description: Der Ort der Grenzen (Tief- und Hochstellung)
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) Methode


Der Ort der Grenzen (Tief- und Hochstellung)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
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
* Bibliothek [Aspose.Slides](../../../)