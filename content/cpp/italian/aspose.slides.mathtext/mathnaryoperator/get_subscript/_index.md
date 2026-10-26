---
title: get_Subscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica un argomento di pedice che, ad esempio, nel caso di un integrale, imposta il limite inferiore
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() metodo

Specifica un argomento di pedice che, ad esempio, nel caso di un integrale, imposta il limite inferiore

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Osservazioni

Esempio:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)