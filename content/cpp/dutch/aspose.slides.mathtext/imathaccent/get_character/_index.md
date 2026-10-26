---
title: get_Character()
second_title: Aspose.Slides voor C++ API-referentie
description: "Accentkarakter De waarde moet binnen het bereik liggen van (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) Standaardwaarde: Combineerbaar circumflexaccent (U+0302)"
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() methode


Accentkarakter De waarde moet binnen het bereik liggen van (U+0300\\u2013U+036F) of(U+20D0\\u2013U+20EF) Standaardwaarde: Combineerbaar circumflexaccent (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
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