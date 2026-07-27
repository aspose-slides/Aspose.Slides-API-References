---
title: get_Subscript()
second_title: Referência da API Aspose.Slides para C++
description: Especifica um argumento subscrito que, por exemplo, no caso de uma integral, define o limite inferior
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() método


Especifica um argumento subscrito que, por exemplo, no caso de uma integral, define o limite inferior

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathNaryOperator](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)