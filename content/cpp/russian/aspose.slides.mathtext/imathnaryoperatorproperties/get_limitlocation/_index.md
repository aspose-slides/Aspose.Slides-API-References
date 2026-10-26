---
title: get_LimitLocation()
second_title: Aspose.Slides для C++ справочник API
description: Расположение пределов (нижний и верхний индексы)
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() метод

Расположение пределов (нижний и верхний индексы)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Примечания

Пример:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Смотрите также

* Перечисление [MathLimitLocations](../../mathlimitlocations/)
* Класс [IMathNaryOperatorProperties](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)