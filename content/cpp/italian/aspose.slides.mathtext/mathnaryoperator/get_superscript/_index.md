---
title: get_Superscript()
second_title: Aspose.Slides per C++ Riferimento API
description: Specifica un argomento superscript che, ad esempio, nel caso di un integrale, imposta il limite superiore
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() metodo


Specifica un argomento superscript che, per esempio, nel caso di un integrale, imposta il limite superiore

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
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
* Classe [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)