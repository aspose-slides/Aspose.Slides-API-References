---
title: get_Limit()
second_title: Справка API Aspose.Slides для C++
description: Аргумент ограничения
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() метод

Аргумент ограничения

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Примечания

Пример:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathLimit](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)