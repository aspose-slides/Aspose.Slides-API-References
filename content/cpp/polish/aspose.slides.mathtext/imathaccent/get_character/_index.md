---
title: get_Character()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Znak akcentu Wartość powinna mieścić się w przedziale (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF) Domyślna wartość: Łączący akcent daszkowy (U+0302)"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() metoda

Znak akcentu Wartość powinna mieścić się w przedziale (U+0300\\u2013U+036F) lub(U+20D0\\u2013U+20EF) Domyślna wartość: Łączący akcent daszkowy (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
```

## Uwagi

Przykład:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Zobacz także

* Klasa [IMathAccent](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)