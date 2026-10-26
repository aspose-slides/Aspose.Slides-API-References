---
title: set_Character()
second_title: Aspose.Slides для C++ справка API
description: "Акцентный символ Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF) Значение по умолчанию: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) метод

Акцентный символ Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или(U+20D0\\u2013U+20EF) Значение по умолчанию: Combining Circumflex Accent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Примечания

Пример:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## См. также

* Класс [IMathAccent](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)