---
title: get_LimitLocation()
second_title: Referencia de API de Aspose.Slides para C++
description: La ubicación de los límites (subíndice y superíndice)
type: docs
weight: 66
url: /es/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() method


La ubicación de los límites (subíndice y superíndice)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Observaciones


Ejemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Véase también

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Clase [MathNaryOperator](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)