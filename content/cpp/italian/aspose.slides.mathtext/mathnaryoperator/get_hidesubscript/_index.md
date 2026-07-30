---
title: get_HideSubscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Nascondi pedice
type: docs
weight: 118
url: /it/aspose.slides.mathtext/mathnaryoperator/get_hidesubscript/
---
## MathNaryOperator::get_HideSubscript() metodo


Nascondi pedice

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_HideSubscript() override
```

## Osservazioni


Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## Vedi anche

* Classe [MathNaryOperator](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)