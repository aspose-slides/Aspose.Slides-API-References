---
title: get_Superscript()
second_title: Referência da API Aspose.Slides para C++
description: Especifica um argumento superscrito que, por exemplo, no caso de uma integral, define o limite superior
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() método

Especifica um argumento superscrito que, por exemplo, no caso de uma integral, define o limite superior

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## Observações

Exemplo:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)