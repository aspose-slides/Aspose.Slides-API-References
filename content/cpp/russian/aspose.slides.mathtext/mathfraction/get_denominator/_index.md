---
title: get_Denominator()
second_title: Справочник API Aspose.Slides для C++
description: Знаменатель
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() метод


Знаменатель

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
```

## Примечания


Пример: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathFraction](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)