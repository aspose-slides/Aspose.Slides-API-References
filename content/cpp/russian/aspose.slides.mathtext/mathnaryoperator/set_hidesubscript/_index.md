---
title: set_HideSubscript()
second_title: Aspose.Slides для C++ API Reference
description: Скрыть нижний индекс
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/mathnaryoperator/set_hidesubscript/
---
## MathNaryOperator::set_HideSubscript(bool) метод


Скрыть нижний индекс

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSubscript(bool value) override
```

## Примечания


Пример: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## См. также

* Класс [MathNaryOperator](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)