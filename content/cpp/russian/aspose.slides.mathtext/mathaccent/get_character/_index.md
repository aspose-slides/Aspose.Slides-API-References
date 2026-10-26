---
title: get_Character()
second_title: Aspose.Slides для C++ справочника API
description: "Акцентный символ Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF) Значение по умолчанию: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() метод

Акцентный символ Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF) Значение по умолчанию: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Примечания

Пример: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## См. также

* Класс [MathAccent](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)