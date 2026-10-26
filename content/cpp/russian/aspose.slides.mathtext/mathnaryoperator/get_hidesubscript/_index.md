---
title: get_HideSubscript()
second_title: Aspose.Slides для C++ справка API
description: Скрыть нижний индекс
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/mathnaryoperator/get_hidesubscript/
---
## MathNaryOperator::get_HideSubscript() метод


Скрыть нижний индекс

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSubscript() override
```

## Замечания


Пример: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## См. также

* Класс [MathNaryOperator](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)