---
title: set_UpperLimit()
second_title: Aspose.Slides для C++ справка по API
description: Указывает верхний или нижний предел
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) метод


Указывает верхний или нижний предел

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
```

## Примечания


Пример: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## См. также

* Класс [IMathLimit](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)