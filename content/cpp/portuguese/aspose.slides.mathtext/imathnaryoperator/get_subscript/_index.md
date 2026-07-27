---
title: get_Subscript()
second_title: Aspose.Slides para C++ - Referência da API
description: Especifica um argumento de subscrito que, por exemplo, no caso de uma integral, define o limite inferior
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() método

Especifica um argumento de subscrito que, por exemplo, no caso de uma integral, define o limite inferior

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## Observações

Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathNaryOperator](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)