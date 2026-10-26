---
title: get_Character()
second_title: Справочник API Aspose.Slides для C++
description: "Символ акцента. Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF). Значение по умолчанию: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() метод

Символ акцента Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF) Значение по умолчанию: Combining Circumflex Accent (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
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