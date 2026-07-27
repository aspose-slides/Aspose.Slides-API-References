---
title: get_Subscript()
second_title: Aspose.Slides para C++ Referência da API
description: Subscrito
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_subscript/
---
## MathLeftSubSuperscriptElement::get_Subscript() method


Subscrito

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Subscript() override
```

## Observações


Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathLeftSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)