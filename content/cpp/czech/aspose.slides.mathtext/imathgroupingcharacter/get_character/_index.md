---
title: get_Character()
second_title: Aspose.Slides pro C++ API Reference
description: "Skupinový znak Výchozí hodnota: U+23DF (spodní složená závorka)"
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() metoda


Skupinový znak Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
```

## Poznámky


Příklad: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Dolní závorka
```

## Viz také

* Třída [IMathGroupingCharacter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)