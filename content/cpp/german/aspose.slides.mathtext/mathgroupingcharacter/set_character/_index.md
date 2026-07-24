---
title: set_Character()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gruppierungszeichen Standardwert: U+23DF (untere geschweifte Klammer)"
type: docs
weight: 27
url: /de/aspose.slides.mathtext/mathgroupingcharacter/set_character/
---
## MathGroupingCharacter::set_Character(char16_t) Methode

Gruppierungszeichen Standardwert: U+23DF (untere geschweifte Klammer)

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Character(char16_t value) override
```

## Hinweise


Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Unterer Klammer
```

## Siehe auch

* Klasse [MathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)