---
title: set_Character()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Výchozí hodnota znaku seskupování: U+23DF (SPODNÍ ZAVINNÁ ZÁVORKA)"
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) metoda

Znak seskupování – výchozí hodnota: U+23DF (spodní složená závorka)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## Poznámky

Příklad: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Spodní závorka
```

## Viz také

* Třída [IMathGroupingCharacter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)