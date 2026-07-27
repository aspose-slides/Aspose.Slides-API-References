---
title: get_Character()
second_title: Referencia de API de Aspose.Slides para C++
description: "Carácter de agrupación Valor predeterminado: U+23DF (LLAVE CURVA INFERIOR)"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() method


Valor predeterminado del carácter de agrupación: U+23DF (LLAVE CURVA INFERIOR)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
```

## Observaciones


Ejemplo: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Paréntesis inferior
```

## Ver también

* Clase [IMathGroupingCharacter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)