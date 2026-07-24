---
title: get_Character()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gruppierungszeichen Standardwert: U+23DF (untere geschweifte Klammer)"
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() Methode


Gruppierungszeichen Standardwert: U+23DF (untere geschweifte Klammer)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
```

## Anmerkungen


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