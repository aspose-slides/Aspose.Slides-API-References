---
title: get_Superscript()
second_title: Referência da API Aspose.Slides para C++
description: Argumento superscrito
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_superscript/
---
## IMathRightSubSuperscriptElement::get_Superscript() método


Argumento superscrito

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Superscript()=0
```

## Observações


Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = subsuperscript->get_Superscript();
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathRightSubSuperscriptElement](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)