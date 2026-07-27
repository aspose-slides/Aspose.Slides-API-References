---
title: set_LimitLocation()
second_title: Referencia de API de Aspose.Slides para C++
description: La ubicación de los límites (subíndice y superíndice)
type: docs
weight: 79
url: /es/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) método


La ubicación de los límites (subíndice y superíndice)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Observaciones


Ejemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Ver también

* Enumeración [MathLimitLocations](../../mathlimitlocations/)
* Clase [MathNaryOperator](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)