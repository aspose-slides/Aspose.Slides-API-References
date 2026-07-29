---
title: set_Character()
second_title: Aspose.Slides för C++ API-referens
description: "Standardvärde för grupperingstecken: U+23DF (BOTTOM CURLY BRACKET)"
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) metod


Standardvärde för grupperingstecken: U+23DF (NEDRE KLAMMERPARENTES)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## Anmärkningar


Exempel:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Nedre parentes
```

## Se även

* Klass [IMathGroupingCharacter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)