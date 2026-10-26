---
title: get_LimitLocation()
second_title: Aspose.Slides C++ API referencia
description: A korlátok helye (alsó index és felső index)
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() metódus

A korlátok helye (alsó index és felső index)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Megjegyzések

Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Lásd még

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Osztály [IMathNaryOperatorProperties](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)