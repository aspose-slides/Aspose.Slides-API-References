---
title: set_GrowToMatchOperandHeight()
second_title: Справка API Aspose.Slides для C++
description: Символ оператора растет вертикально, чтобы соответствовать высоте его операнда
type: docs
weight: 105
url: /ru/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) метод


Символ оператора растет вертикально, чтобы соответствовать высоте его операнда

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## Примечания


Пример: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Смотрите также

* Класс [MathNaryOperator](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)