---
title: Accent()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een accentteken in (een teken bovenop dit element)
type: docs
weight: 196
url: /nl/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) methode

Stelt een accentteken in (een teken bovenop dit element)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| accentCharacter | char16_t | Accentteken. De waarde moet binnen het bereik (U+0300\\u2013U+036F) of (U+20D0\\u2013U+20EF) liggen. |

### Retourwaarde

Nieuwe instantie van type [IMathAccent](../../imathaccent/)
## Opmerkingen



Voorbeeld: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathAccent](../../imathaccent/)
* Klasse [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)