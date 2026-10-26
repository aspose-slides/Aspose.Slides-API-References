---
title: get_Name()
second_title: Aspose.Slides для C++ Справка по API
description: Имя функции Например, имена функций — sin и cos
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() метод


Имя функции Например, имена функций — sin и cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Примечания


Пример: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathFunction](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)