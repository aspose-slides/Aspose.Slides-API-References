---
title: set_Character()
second_title: Aspose.Slides dla C++ referencja API
description: "Znak akcentu Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub(U+20D0\\u2013U+20EF) Domyślna wartość: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) metoda

Znak akcentu Wartość powinna mieścić się w przedziale (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF) Domyślna wartość: Combining Circumflex Accent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## Uwagi

Przykład:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Zobacz także

* Klasa [MathAccent](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)