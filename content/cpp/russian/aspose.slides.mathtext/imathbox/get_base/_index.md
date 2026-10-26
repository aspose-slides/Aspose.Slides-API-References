---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Base аргумент
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() метод

Base аргумент

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## Замечания

Пример: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)