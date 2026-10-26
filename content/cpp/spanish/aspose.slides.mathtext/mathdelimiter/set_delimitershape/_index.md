---
title: set_DelimiterShape()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Especifica la forma de los delimitadores en el objeto delimitador. Cuando es MathDelimiterShape::Centered, los delimitadores se centran alrededor del eje matemático del texto matemático y aún pueden ajustarse para cubrir toda la altura de su contenido. Cuando es MathDelimiterShape::Match, su altura y forma se alteran para coincidir exactamente con su contenido."
type: docs
weight: 131
url: /es/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) método

Especifica la forma de los delimitadores en el objeto delimitador. Cuando es [MathDelimiterShape::Centered](../../mathdelimitershape/), los delimitadores se centran alrededor del eje matemático del texto matemático y todavía pueden ajustarse para cubrir toda la altura de su contenido. Cuando es [MathDelimiterShape::Match](../../mathdelimitershape/), su altura y forma se alteran para coincidir exactamente con su contenido.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Comentarios

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