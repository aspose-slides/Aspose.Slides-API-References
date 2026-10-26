---
title: set_Character()
second_title: Aspose.Slides voor C++ API-referentie
description: "Accentteken De waarde moet binnen het bereik liggen van (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) Standaardwaarde: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) methode

Accentteken De waarde moet binnen het bereik liggen van (U+0300\\u2013U+036F) of(U+20D0\\u2013U+20EF) Standaardwaarde: Combining Circumflex Accent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## Opmerkingen

Voorbeeld: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Zie ook

* Klasse [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)