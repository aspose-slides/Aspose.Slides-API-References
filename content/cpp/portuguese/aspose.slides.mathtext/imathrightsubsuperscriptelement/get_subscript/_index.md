---
title: get_Subscript()
second_title: Aspose.Slides para C++ Referência da API
description: Argumento de subscrito
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_subscript/
---
## IMathRightSubSuperscriptElement::get_Subscript() método


Argumento de subscrito

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Subscript()=0
```

## Observações


Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = subsuperscript->get_Subscript();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathRightSubSuperscriptElement](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)