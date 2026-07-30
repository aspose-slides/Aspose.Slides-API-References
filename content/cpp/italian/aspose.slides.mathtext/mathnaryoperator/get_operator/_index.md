---
title: get_Operator()
second_title: Aspose.Slides per il riferimento API di C++
description: "Carattere operatore N-ario Per esempio: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /it/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() metodo

Carattere operatore N-ario Per esempio: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Osservazioni

Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Vedi anche

* Classe [MathNaryOperator](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)