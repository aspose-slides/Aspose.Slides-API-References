---
title: set_Character()
second_title: Referencia de API de Aspose.Slides para C++
description: "Carácter de agrupación Valor predeterminado: U+23DF (LLAVE CURLADA INFERIOR)"
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathgroupingcharacter/set_character/
---
## MathGroupingCharacter::set_Character(char16_t) método

Valor predeterminado del carácter de agrupación: U+23DF (LLAVE CURLADA INFERIOR)

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Character(char16_t value) override
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