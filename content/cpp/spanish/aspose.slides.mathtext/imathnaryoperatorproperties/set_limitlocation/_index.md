---
title: set_LimitLocation()
second_title: Referencia de la API de Aspose.Slides para C++
description: La ubicación de los límites (subíndice y superíndice)
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) método


La ubicación de los límites (subíndice y superíndice)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Observaciones


Ejemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Ver también

* Enumeración [MathLimitLocations](../../mathlimitlocations/)
* Clase [IMathNaryOperatorProperties](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)