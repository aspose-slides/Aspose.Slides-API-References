---
title: get_Numerator()
second_title: Справочник API Aspose.Slides для C++
description: Числитель
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() метод


Числитель

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
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
* Класс [MathFraction](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)