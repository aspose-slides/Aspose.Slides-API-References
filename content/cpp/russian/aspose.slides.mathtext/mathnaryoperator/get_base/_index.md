---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент Base
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() метод

аргумент Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## Примечания

Пример:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathNaryOperator](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)