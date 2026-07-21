---
title: get_Denominator()
second_title: Aspose.Slides для C++ справочник API
description: Знаменатель
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() method


Denominator

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## Примечания


Пример: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathFraction](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)