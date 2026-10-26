---
title: get_HideSuperscript()
second_title: Aspose.Slides для C++ справочник API
description: Скрыть верхний индекс
type: docs
weight: 105
url: /ru/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesuperscript/
---
## IMathNaryOperatorProperties::get_HideSuperscript() метод


Скрыть верхний индекс

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSuperscript()=0
```

## Примечания


Пример: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## См. также

* Класс [IMathNaryOperatorProperties](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)