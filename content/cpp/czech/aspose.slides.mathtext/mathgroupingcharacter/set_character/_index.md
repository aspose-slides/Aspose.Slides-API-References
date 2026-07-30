---
title: set_Character()
second_title: Aspose.Slides pro C++ API Reference
description: "Skupinový znak Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET)"
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathgroupingcharacter/set_character/
---
## MathGroupingCharacter::set_Character(char16_t) metoda


Výchozí hodnota skupinového znaku: U+23DF (BOTTOM CURLY BRACKET)

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Character(char16_t value) override
```

## Poznámky


Příklad: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Spodní závorka
```

## Viz také

* Třída [MathGroupingCharacter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)