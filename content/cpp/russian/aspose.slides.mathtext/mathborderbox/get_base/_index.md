---
title: get_Base()
second_title: Aspose.Slides для C++ справка API
description: Аргумент Base
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathborderbox/get_base/
---
## MathBorderBox::get_Base() метод


Аргумент Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBorderBox::get_Base() override
```

## Примечания


Пример: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = borderBox->get_Base();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBorderBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)