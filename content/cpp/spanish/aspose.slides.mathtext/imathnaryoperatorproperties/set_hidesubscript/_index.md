---
title: set_HideSubscript()
second_title: Referencia de API de Aspose.Slides para C++
description: Ocultar subíndice
type: docs
weight: 92
url: /es/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesubscript/
---
## IMathNaryOperatorProperties::set_HideSubscript(bool) método


Ocultar subíndice

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSubscript(bool value)=0
```

## Observaciones


Ejemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Ver también

* Clase [IMathNaryOperatorProperties](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)