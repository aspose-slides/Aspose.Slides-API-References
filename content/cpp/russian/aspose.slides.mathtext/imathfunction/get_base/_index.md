---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент функции
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() метод

Аргумент функции

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Примечания

Пример:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathFunction](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)