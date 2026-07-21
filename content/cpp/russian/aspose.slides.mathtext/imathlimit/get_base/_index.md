---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Базовый аргумент
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() method

Базовый аргумент

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## Примечания

Пример:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathLimit](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)