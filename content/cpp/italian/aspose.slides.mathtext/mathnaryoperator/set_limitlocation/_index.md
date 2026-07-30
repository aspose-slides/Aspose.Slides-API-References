---
title: set_LimitLocation()
second_title: Riferimento API Aspose.Slides per C++
description: La posizione dei limiti (pedice e apice)
type: docs
weight: 79
url: /it/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) metodo

La posizione dei limiti (pedice e apice)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Osservazioni

Esempio:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Vedi anche

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Classe [MathNaryOperator](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)