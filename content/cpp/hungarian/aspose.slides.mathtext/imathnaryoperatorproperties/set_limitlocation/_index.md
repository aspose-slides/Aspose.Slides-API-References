---
title: set_LimitLocation()
second_title: Aspose.Slides for C++ API referencia
description: A korlátok helye (alsó index és felső index)
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) method

A korlátok helye (alsó index és felső index)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Megjegyzés


Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Lásd még

* Felsorolás [MathLimitLocations](../../mathlimitlocations/)
* Osztály [IMathNaryOperatorProperties](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)