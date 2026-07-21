---
title: get_Character()
second_title: Aspose.Slides для C++: справка по API
description: "Группирующий символ Значение по умолчанию: U+23DF (нижняя фигурная скобка)"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() метод

Группирующий символ Значение по умолчанию: U+23DF (нижняя фигурная скобка)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
```
## Примечания

Пример: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Нижняя скобка
```
## См. также

* Класс [IMathGroupingCharacter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)