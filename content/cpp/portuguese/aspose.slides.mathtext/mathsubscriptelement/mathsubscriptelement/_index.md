---
title: MathSubscriptElement()
second_title: Aspose.Slides para C++ Referência da API
description: Inicializa uma nova instância da classe MathSubscriptElement.
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathsubscriptelement/mathsubscriptelement/
---
## MathSubscriptElement::MathSubscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) construtor


Inicializa uma nova instância da classe [MathSubscriptElement](../).

```cpp
Aspose::Slides::MathText::MathSubscriptElement::MathSubscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript)
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathSubscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)