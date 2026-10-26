---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент Base
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() метод

Base аргумент

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## Примечания

Пример:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathBorderBox](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)