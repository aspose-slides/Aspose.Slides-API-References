---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathsubscriptelement/get_base/
---
## MathSubscriptElement::get_Base() método


Argumento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Base() override
```

## Observações


Exemplo:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto baseElem = subscriptElement->get_Base();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathSubscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)