---
title: set_DelimiterShape()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape::Centered, los delimitadores se centran alrededor del eje matemático del texto matemático y aún pueden ajustarse para ocupar toda la altura de sus contenidos. Cuando es MathDelimiterShape::Match, su altura y forma se alteran para coincidir exactamente con sus contenidos."
type: docs
weight: 131
url: /es/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) método

Especifica la forma de los delimitadores en el objeto delimitador. Cuando es [MathDelimiterShape::Centered](../../mathdelimitershape/), los delimitadores se centran alrededor del eje matemático del texto matemático y aún pueden ajustarse para ocupar toda la altura de su contenido. Cuando es [MathDelimiterShape::Match](../../mathdelimitershape/), su altura y forma se alteran para coincidir exactamente con su contenido.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Observaciones

Ejemplo:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Ver también

* Enumeración [MathDelimiterShape](../../mathdelimitershape/)
* Clase [IMathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)