---
title: get_Degree()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент Degree
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() метод


Аргумент Degree

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Примечания


Пример: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathRadical](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)