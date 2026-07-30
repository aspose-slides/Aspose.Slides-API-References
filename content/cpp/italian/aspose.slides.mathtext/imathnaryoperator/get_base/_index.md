---
title: get_Base()
second_title: Riferimento API Aspose.Slides per C++
description: Argomento base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathnaryoperator/get_base/
---
## IMathNaryOperator::get_Base() metodo


Argomento base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Base()=0
```

## Osservazioni


Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathNaryOperator](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)