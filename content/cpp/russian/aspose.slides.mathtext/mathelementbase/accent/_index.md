---
title: Accent()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает знак акцента (символ над верхней частью этого элемента)
type: docs
weight: 196
url: /ru/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) метод

Устанавливает знак акцента (символ над верхней частью этого элемента)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| accentCharacter | char16_t | Символ акцента. Значение должно находиться в диапазоне (U+0300\\u2013U+036F) или (U+20D0\\u2013U+20EF) |

### Возвращаемое значение

New instance of type [IMathAccent](../../imathaccent/)
## Примечания

Пример: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathAccent](../../imathaccent/)
* Класс [MathElementBase](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)