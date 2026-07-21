---
title: get_Base()
second_title: Справка по API Aspose.Slides для C++
description: Аргумент Base
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathbar/get_base/
---
## MathBar::get_Base() метод


Base аргумент

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBar::get_Base() override
```

## Примечания


Пример: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBar](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)