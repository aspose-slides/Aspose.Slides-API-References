---
title: get_UpperLimit()
second_title: Aspose.Slides для C++ справочник API
description: Указывает верхний или нижний предел
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathlimit/get_upperlimit/
---
## IMathLimit::get_UpperLimit() метод

Указывает верхний или нижний предел

```cpp
virtual bool Aspose::Slides::MathText::IMathLimit::get_UpperLimit()=0
```

## Примечания


Пример: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## См. также

* Класс [IMathLimit](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)