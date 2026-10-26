---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент функции
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() метод

Аргумент функции

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
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
* Класс [MathFunction](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)