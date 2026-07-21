---
title: set_Character()
second_title: Aspose.Slides для C++ справочник API
description: "Символ акцента Значение должно быть в диапазоне (U+0300\\u2013U+036F) или(U+20D0\\u2013U+20EF) Значение по умолчанию: Комбинирующий циркумфлексный акцент (U+0302)"
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) метод


Символ акцента Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или(U+20D0\\u2013U+20EF) Значение по умолчанию: Комбинирующий циркумфлексный акцент (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
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