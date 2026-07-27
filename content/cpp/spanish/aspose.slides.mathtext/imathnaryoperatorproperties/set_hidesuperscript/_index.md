---
title: set_HideSuperscript()
second_title: Referencia API de Aspose.Slides para C++
description: Ocultar superíndice
type: docs
weight: 118
url: /es/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesuperscript/
---
## IMathNaryOperatorProperties::set_HideSuperscript(bool) method

Ocultar superíndice

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSuperscript(bool value)=0
```

## Observaciones

Ejemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## Ver también

* Clase [IMathNaryOperatorProperties](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)