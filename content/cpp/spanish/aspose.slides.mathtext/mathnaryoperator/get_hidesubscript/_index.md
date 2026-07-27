---
title: get_HideSubscript()
second_title: Referencia de la API de Aspose.Slides para C++
description: Ocultar subíndice
type: docs
weight: 118
url: /es/aspose.slides.mathtext/mathnaryoperator/get_hidesubscript/
---
## MathNaryOperator::get_HideSubscript() método

Ocultar subíndice

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSubscript() override
```

## Observaciones


Ejemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Ver también

* Clase [MathNaryOperator](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)