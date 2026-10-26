---
title: get_GrowToMatchOperandHeight()
second_title: Справочник API Aspose.Slides для C++
description: Символ оператора растет вертикально, чтобы соответствовать высоте его операнда
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() method


Символ оператора растет вертикально, чтобы соответствовать высоте его операнда

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## Примечания


Пример: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## См. также

* Класс [IMathNaryOperatorProperties](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)