---
title: get_HideSubscript()
second_title: Referencia de API de Aspose.Slides para C++
description: Ocultar subíndice
type: docs
weight: 79
url: /es/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesubscript/
---
## IMathNaryOperatorProperties::get_HideSubscript() método


Ocultar subíndice

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSubscript()=0
```

## Comentarios


Ejemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Ver también

* Clase [IMathNaryOperatorProperties](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)