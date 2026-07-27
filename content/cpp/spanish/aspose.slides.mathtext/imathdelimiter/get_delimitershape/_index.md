---
title: get_DelimiterShape()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape::Centered, los delimitadores se centran alrededor del eje matemático del texto matemático y aún se hacen para ajustarse a toda la altura de su contenido. Cuando es MathDelimiterShape::Match, su altura y forma se alteran para coincidir exactamente con su contenido."
type: docs
weight: 118
url: /es/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() método

Especifica la forma de los delimitadores en el objeto delimitador. Cuando es [MathDelimiterShape::Centered](../../mathdelimitershape/), los delimitadores se centran alrededor del eje matemático del texto matemático y aún se hacen para ajustarse a toda la altura de su contenido. Cuando es [MathDelimiterShape::Match](../../mathdelimitershape/), su altura y forma se alteran para coincidir exactamente con su contenido.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Observaciones

Ejemplo: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Véase también

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Clase [IMathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)