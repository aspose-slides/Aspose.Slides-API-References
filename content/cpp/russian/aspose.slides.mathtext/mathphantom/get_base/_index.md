---
title: get_Base()
second_title: Aspose.Slides для C++ справочника API
description: Аргумент Base
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() метод

Аргумент Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
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
* Класс [MathPhantom](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)