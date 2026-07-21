---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Базовый аргумент
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathgroupingcharacter/get_base/
---
## IMathGroupingCharacter::get_Base() метод

Базовый аргумент

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathGroupingCharacter::get_Base()=0
```

## Примечания

Пример:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathGroupingCharacter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)