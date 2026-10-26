---
title: set_Operator()
second_title: Aspose.Slides для C++ API Справочник
description: "Символ n-арного оператора. Например: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) метод

Символ n-арного оператора. Например: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## Примечания

Пример:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## См. также

* Класс [IMathNaryOperatorProperties](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)