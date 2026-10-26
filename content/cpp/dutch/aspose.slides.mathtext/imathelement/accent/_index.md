---
title: Accent()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een accentteken in (een teken bovenaan dit element)
type: docs
weight: 209
url: /nl/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) methode

Stelt een accentteken in (een teken bovenaan dit element)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
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
* Class [IMathAccent](../../imathaccent/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)