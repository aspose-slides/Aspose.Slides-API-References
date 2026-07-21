---
title: get_Base()
second_title: Aspose.Slides for C++: справочник API
description: Аргумент Base
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() метод

Аргумент Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## Примечания

Пример:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathBar](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)