---
title: get_Character()
second_title: Aspose.Slides voor C++ API-referentie
description: "Accentteken De waarde moet binnen het bereik van (U+0300\\u2013U+036F) of(U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combinerende circumflex-accent (U+0302)"
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() methode


Accentteken De waarde moet binnen het bereik van (U+0300\\u2013U+036F) of(U+20D0\\u2013U+20EF) liggen Standaardwaarde: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Zie ook

* Klasse [MathAccent](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)