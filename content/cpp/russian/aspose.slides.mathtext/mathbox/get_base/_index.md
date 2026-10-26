---
title: get_Base()
second_title: Aspose.Slides для C++ справочник API
description: Base аргумент
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() method

Base аргумент

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Примечания

Пример:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBox](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)