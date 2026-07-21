---
title: Accent()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает знак акцента (символ в верхней части этого элемента)
type: docs
weight: 209
url: /ru/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) метод

Устанавливает знак акцента (символ в верхней части этого элемента)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| accentCharacter | char16_t | Символ акцента. Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF) |

### Возвращаемое значение

Новый экземпляр типа [IMathAccent](../../imathaccent/)
## Примечание

Пример:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathAccent](../../imathaccent/)
* Класс [IMathElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)