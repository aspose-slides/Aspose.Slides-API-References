---
title: set_Character()
second_title: Aspose.Slides C++ API referencia
description: "Csoportosító karakter alapértelmezett értéke: U+23DF (alsó görbe kapcsos zárójel)"
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) metódus


Csoportosító karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## Megjegyzések


Példa: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Alsó zárójel
```

## Lásd még

* Osztály [IMathGroupingCharacter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)