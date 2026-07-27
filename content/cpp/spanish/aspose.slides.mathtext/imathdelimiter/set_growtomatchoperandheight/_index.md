---
title: set_GrowToMatchOperandHeight()
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura de su operando. El valor predeterminado es true
type: docs
weight: 105
url: /es/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) método


Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura de su operando. El valor predeterminado es true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
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