---
title: get_Superscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica un argomento superscritto che, ad esempio, nel caso di un integrale, imposta il limite superiore
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() metodo

Specifica un argomento superscritto che, ad esempio, nel caso di un integrale, imposta il limite superiore

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## Osservazioni

Esempio: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)