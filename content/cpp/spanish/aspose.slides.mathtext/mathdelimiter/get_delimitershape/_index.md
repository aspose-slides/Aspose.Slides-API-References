---
title: get_DelimiterShape()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape::Centered, los delimitadores se centran en el eje matemático del texto matemático y todavía se ajustan para ocupar toda la altura de su contenido. Cuando es MathDelimiterShape::Match, su altura y forma se modifican para coincidir exactamente con su contenido."
type: docs
weight: 118
url: /es/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() método


Especifica la forma de los delimitadores en el objeto delimitador. Cuando es [MathDelimiterShape::Centered](../../mathdelimitershape/), los delimitadores se centran en el eje matemático del texto matemático y aún se ajustan para ocupar toda la altura de su contenido. Cuando es [MathDelimiterShape::Match](../../mathdelimitershape/), su altura y forma se modifican para coincidir exactamente con su contenido.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Observaciones


Ejemplo: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Ver también

* Enumeración [MathDelimiterShape](../../mathdelimitershape/)
* Clase [MathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)