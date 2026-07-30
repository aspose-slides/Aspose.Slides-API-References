---
title: get_Operator()
second_title: Riferimento API di Aspose.Slides per C++
description: "Carattere operatore N-ario Per esempio: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() metodo


Carattere dell'operatore N-ario Per esempio: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Note


Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Vedi anche

* Classe [IMathNaryOperatorProperties](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)