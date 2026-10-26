---
title: set_HideSuperscript()
second_title: Referencia de la API de Aspose.Slides para C++
description: Ocultar superíndice
type: docs
weight: 157
url: /es/aspose.slides.mathtext/mathnaryoperator/set_hidesuperscript/
---
## MathNaryOperator::set_HideSuperscript(bool) método


Ocultar superíndice

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSuperscript(bool value) override
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