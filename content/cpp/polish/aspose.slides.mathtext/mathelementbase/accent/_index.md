---
title: Accent()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Ustawia znak akcentu (znak na górze tego elementu)
type: docs
weight: 196
url: /pl/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) metoda

Ustawia znak akcentu (znak na górze tego elementu)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| accentCharacter | char16_t | Znak akcentu. Wartość powinna mieści się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF) |

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
* Klasa [MathElementBase](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)