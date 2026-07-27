---
title: get_GrowToMatchOperandHeight()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter cuando es verdadero, los delimitadores crecen verticalmente para que coincida con la altura de su operando. El valor predeterminado es true
type: docs
weight: 92
url: /es/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() método

Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es verdadero, los delimitadores crecen verticalmente para que coincida con la altura de su operando. El valor predeterminado es true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Observaciones

Ejemplo: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Ver también

* Clase [IMathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)