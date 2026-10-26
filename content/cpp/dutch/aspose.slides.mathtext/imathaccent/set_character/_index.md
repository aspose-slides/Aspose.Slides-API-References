---
title: set_Character()
second_title: Aspose.Slides voor C++ API-referentie
description: "Accentteken De waarde moet binnen het bereik liggen van (U+0300\\u2013U+036F) of(U+20D0\\u2013U+20EF) Standaardwaarde: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) methode

Accentteken De waarde moet binnen het bereik van (U+0300\\u2013U+036F) of(U+20D0\\u2013U+20EF) Standaardwaarde: Combining Circumflex Accent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Opmerkingen

Voorbeeld:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Zie ook

* Klasse [IMathAccent](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)