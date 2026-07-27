---
title: get_Base()
second_title: Aspose.Slides para C++ Referência da API
description: Argumento Base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() método


Argumento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## Observações


Exemplo: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)