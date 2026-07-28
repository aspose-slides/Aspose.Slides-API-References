---
title: get_Character()
second_title: Aspose.Slides dla C++ — Dokumentacja API
description: "Znak akcentu Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF) Domyślna wartość: Łączący akcent cyrkumfleks (U+0302)"
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() metoda


Znak akcentu Wartość powinna znajdować się w przedziale (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF) Domyślna wartość: Łączący akcent cyrkumfleks (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
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