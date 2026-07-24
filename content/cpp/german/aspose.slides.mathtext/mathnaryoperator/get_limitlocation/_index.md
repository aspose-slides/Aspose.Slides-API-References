---
title: get_LimitLocation()
second_title: Aspose.Slides für C++ API-Referenz
description: Der Ort der Grenzen (tiefgestellt und hochgestellt)
type: docs
weight: 66
url: /de/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() Methode


Der Ort der Grenzen (tiefgestellt und hochgestellt)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Hinweise


Beispiel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Siehe auch

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)