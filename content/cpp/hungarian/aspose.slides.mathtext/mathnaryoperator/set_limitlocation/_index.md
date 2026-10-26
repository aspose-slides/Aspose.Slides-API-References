---
title: set_LimitLocation()
second_title: Aspose.Slides C++ API-referencia
description: A határolók helye (alsó index és felső index)
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) metódus


A határolók helye (alsó index és felső index)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Megjegyzések


Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Lásd még

* Enum [MathLimitLocations](../../mathlimitlocations/)
* osztály [MathNaryOperator](../)
* névtér [Aspose::Slides::MathText](../../)
* könyvtár [Aspose.Slides](../../../)