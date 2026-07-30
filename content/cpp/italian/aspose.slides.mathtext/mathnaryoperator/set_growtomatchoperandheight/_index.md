---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides per C++ Riferimento API
description: Il carattere operatore cresce verticalmente per corrispondere all'altezza del suo operando
type: docs
weight: 105
url: /it/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) metodo


Il carattere operatore cresce verticalmente per corrispondere all'altezza del suo operando

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
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