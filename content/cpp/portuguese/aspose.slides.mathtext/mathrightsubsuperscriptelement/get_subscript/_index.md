---
title: get_Subscript()
second_title: Aspose.Slides para C++ Referência da API
description: Argumento de subscrito
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_subscript/
---
## MathRightSubSuperscriptElement::get_Subscript() método


Argumento de subscrito

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Subscript() override
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

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRightSubSuperscriptElement](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)