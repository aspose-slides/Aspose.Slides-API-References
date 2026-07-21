---
title: get_Operator()
second_title: Aspose.Slides для C++ справочник API
description: "Символ n-арного оператора. Например: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() метод


Символ n-арного оператора. Например: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Примечания


Пример: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Смотрите также

* Класс [IMathNaryOperatorProperties](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)