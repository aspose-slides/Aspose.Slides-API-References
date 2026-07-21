---
title: get_GrowToMatchOperandHeight()
second_title: Справочник API Aspose.Slides для C++
description: Символ оператора растет по вертикали, чтобы соответствовать высоте его операнда
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() метод


Символ оператора растет по вертикали, чтобы соответствовать высоте его операнда

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## Примечания


Пример: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## См. также

* Класс [MathNaryOperator](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)