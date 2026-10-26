---
title: Accent()
second_title: Aspose.Slides dla C++ - referencja API
description: Ustawia znak akcentu (znak umieszczony na górze tego elementu)
type: docs
weight: 209
url: /pl/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) metoda

Ustawia znak akcentu (znak na górze tego elementu)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| accentCharacter | char16_t | Znak akcentu. Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF) |

### Wartość zwracana

Nowa instancja typu [IMathAccent](../../imathaccent/)
## Uwagi



Przykład: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathAccent](../../imathaccent/)
* Klasa [IMathElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)