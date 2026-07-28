---
title: set_Character()
second_title: Referencja API Aspose.Slides dla C++
description: "Znak akcentu Wartość powinna być w przedziale (U+0300\\u2013U+036F) lub(U+20D0\\u2013U+20EF) Domyślna wartość: Łączący akcent cyrkumfleks (U+0302)"
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) metoda

Znak akcentu Wartość powinna być w przedziale (U+0300\\u2013U+036F) lub(U+20D0\\u2013U+20EF) Domyślna wartość: Combining Circumflex Accent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
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