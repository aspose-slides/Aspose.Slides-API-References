---
title: get_LimitLocation()
second_title: Справочник API Aspose.Slides для C++
description: Расположение пределов (нижний и верхний индекс)
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() метод

Расположение пределов (нижний и верхний индекс)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Примечания

Пример:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## См. также

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Класс [MathNaryOperator](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)