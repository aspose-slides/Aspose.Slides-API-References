---
title: set_GrowToMatchOperandHeight()
second_title: Riferimento API Aspose.Slides per C++
description: Il carattere dell'operatore cresce verticalmente per adattarsi all'altezza del suo operando
type: docs
weight: 66
url: /it/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) metodo


Il carattere dell'operatore cresce verticalmente per corrispondere all'altezza del suo operando

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## Note


Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Vedi anche

* Classe [IMathNaryOperatorProperties](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)