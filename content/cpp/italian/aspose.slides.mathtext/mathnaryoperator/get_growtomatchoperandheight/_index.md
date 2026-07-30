---
title: get_GrowToMatchOperandHeight()
second_title: Riferimento API di Aspose.Slides per C++
description: Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando
type: docs
weight: 92
url: /it/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() metodo


Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## Osservazioni


Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Vedi anche

* Classe [MathNaryOperator](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)