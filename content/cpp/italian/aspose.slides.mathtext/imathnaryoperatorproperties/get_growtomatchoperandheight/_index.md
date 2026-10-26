---
title: get_GrowToMatchOperandHeight()
second_title: Riferimento API di Aspose.Slides per C++
description: Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando
type: docs
weight: 53
url: /it/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() metodo


Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## Osservazioni


Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Vedi anche

* Classe [IMathNaryOperatorProperties](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)