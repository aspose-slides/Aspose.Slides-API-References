---
title: get_Numerator()
second_title: Aspose.Slides для C++ справочник API
description: Числитель
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMMathFraction::get_Numerator() метод

Числитель

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
```

## Примечания


Пример: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathFraction](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)