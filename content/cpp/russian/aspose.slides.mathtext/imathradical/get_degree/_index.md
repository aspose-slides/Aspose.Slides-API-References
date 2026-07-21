---
title: get_Degree()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент Degree
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() метод

Degree аргумент

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Примечания

Пример: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // кубический корень
auto degreeElem = radical->get_Degree();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathRadical](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)