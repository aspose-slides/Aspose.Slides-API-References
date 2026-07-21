---
title: get_Limit()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент лимита
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() метод

Аргумент лимита

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Примечания

Пример:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathLimit](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)