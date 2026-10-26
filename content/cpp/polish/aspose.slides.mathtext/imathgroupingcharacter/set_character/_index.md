---
title: set_Character()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Domyślna wartość znaku grupowania: U+23DF (dolny nawias klamrowy)"
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) metoda

Domyślna wartość znaku grupowania: U+23DF (BOTTOM CURLY BRACKET)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
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