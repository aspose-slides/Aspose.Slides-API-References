---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Базовый аргумент
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() метод

Базовый аргумент

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
```

## Примечания

Пример:
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathPhantom](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)