---
title: get_GrowToMatchOperandHeight()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura de su operando. El valor predeterminado es true
type: docs
weight: 92
url: /es/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() método


Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura de su operando. El valor predeterminado es true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Observaciones


Ejemplo: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Ver también

* Clase [MathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)