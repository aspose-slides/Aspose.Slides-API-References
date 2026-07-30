---
title: get_HideSuperscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Nascondi apice
type: docs
weight: 144
url: /it/aspose.slides.mathtext/mathnaryoperator/get_hidesuperscript/
---
## MathNaryOperator::get_HideSuperscript() metodo


Nascondi apice

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSuperscript() override
```

## Osservazioni


Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## Vedi anche

* Classe [MathNaryOperator](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)