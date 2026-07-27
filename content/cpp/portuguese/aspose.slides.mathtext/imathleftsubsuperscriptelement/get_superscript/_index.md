---
title: get_Superscript()
second_title: Referência da API Aspose.Slides para C++
description: Sobrescrito
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_superscript/
---
## IMathLeftSubSuperscriptElement::get_Superscript() método


Sobrescrito

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Superscript()=0
```

## Observações


Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathLeftSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)