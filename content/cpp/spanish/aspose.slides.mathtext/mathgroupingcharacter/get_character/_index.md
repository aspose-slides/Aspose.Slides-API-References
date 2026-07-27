---
title: get_Character()
second_title: Referencia de API de Aspose.Slides para C++
description: "Carácter de agrupación Valor predeterminado: U+23DF (corchete rizado inferior)"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathgroupingcharacter/get_character/
---
## MathGroupingCharacter::get_Character() método


Carácter de agrupación Valor predeterminado: U+23DF (corchete rizado inferior)

```cpp
char16_t Aspose::Slides::MathText::MathGroupingCharacter::get_Character() override
```

## Observaciones


Ejemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Paréntesis inferior
```

## Ver también

* Clase [MathGroupingCharacter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)