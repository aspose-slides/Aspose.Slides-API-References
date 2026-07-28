---
title: get_Character()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Znak grupowania Domyślna wartość: U+23DF (dolny nawias klamrowy)"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() metoda


Domyślna wartość znaku grupowania: U+23DF (BOTTOM CURLY BRACKET)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
```

## Uwagi


Przykład: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Dolny nawias
```

## Zobacz także

* Klasa [IMathGroupingCharacter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)