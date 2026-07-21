---
title: set_LimitLocation()
second_title: Aspose.Slides для C++ справочник API
description: Расположение пределов (нижний и верхний индекс)
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) метод

Расположение пределов (нижний и верхний индекс)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Примечания

Пример:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## См. также

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)