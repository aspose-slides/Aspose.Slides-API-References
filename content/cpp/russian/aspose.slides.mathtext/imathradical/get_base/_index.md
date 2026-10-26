---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент Base
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() метод

Аргумент Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Примечания


Пример:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // кубический корень
auto baseElem = radical->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathRadical](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)