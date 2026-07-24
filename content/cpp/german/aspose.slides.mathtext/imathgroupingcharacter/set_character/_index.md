---
title: set_Character()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gruppierungszeichen Standardwert: U+23DF (untere geschweifte Klammer)"
type: docs
weight: 27
url: /de/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) Methode

Gruppierungszeichen Standardwert: U+23DF (untere geschweifte Klammer)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## Hinweise

Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Untere Klammer
```

## Siehe auch

* Klasse [IMathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)