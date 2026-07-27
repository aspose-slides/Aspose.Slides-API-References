---
title: get_Superscript()
second_title: Referência da API Aspose.Slides para C++
description: Especifica um argumento supersript que, por exemplo, no caso de uma integral, define o limite superior
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() método


Especifica um argumento supersript que, por exemplo, no caso de uma integral, define o limite superior

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathNaryOperator](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)