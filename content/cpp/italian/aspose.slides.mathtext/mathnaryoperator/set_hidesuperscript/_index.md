---
title: set_HideSuperscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Nascondi apice
type: docs
weight: 157
url: /it/aspose.slides.mathtext/mathnaryoperator/set_hidesuperscript/
---
## MathNaryOperator::set_HideSuperscript(bool) metodo


Nascondi apice

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_HideSuperscript(bool value) override
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