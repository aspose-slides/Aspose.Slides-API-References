---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент Base
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() метод


Аргумент Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Примечания


Пример: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathRadical](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)