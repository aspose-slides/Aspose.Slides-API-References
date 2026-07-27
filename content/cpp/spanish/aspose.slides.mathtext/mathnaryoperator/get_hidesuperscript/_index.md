---
title: get_HideSuperscript()
second_title: Referencia de la API de Aspose.Slides para C++
description: Ocultar superíndice
type: docs
weight: 144
url: /es/aspose.slides.mathtext/mathnaryoperator/get_hidesuperscript/
---
## MathNaryOperator::get_HideSuperscript() método


Ocultar superíndice

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSuperscript() override
```

## Observaciones


Ejemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## Ver también

* Clase [MathNaryOperator](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)