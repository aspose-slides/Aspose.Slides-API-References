---
title: set_GrowToMatchOperandHeight()
second_title: Referencia de la API de Aspose.Slides para C++
description: El carácter del operador crece verticalmente para coincidir con la altura de su operando
type: docs
weight: 66
url: /es/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) método

El carácter del operador crece verticalmente para coincidir con la altura de su operando

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## Observaciones

Ejemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Ver también

* Clase [IMathNaryOperatorProperties](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)