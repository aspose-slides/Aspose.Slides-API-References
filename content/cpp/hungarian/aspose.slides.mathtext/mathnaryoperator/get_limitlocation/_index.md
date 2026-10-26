---
title: get_LimitLocation()
second_title: Aspose.Slides for C++ API referencia
description: A határok (alsó és felső index) helye
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() metódus


A határok (alsó és felső index) helye

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Megjegyzés


Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Lásd még

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Osztály [MathNaryOperator](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)