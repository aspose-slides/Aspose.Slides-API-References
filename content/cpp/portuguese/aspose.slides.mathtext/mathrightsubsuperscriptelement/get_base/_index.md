---
title: get_Base()
second_title: Aspose.Slides para C++ Referência da API
description: Argumento base
type: docs
weight: 53
url: /pt/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_base/
---
## MathRightSubSuperscriptElement::get_Base() método

Base argumento

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Base() override
```

## Observações

Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = subsuperscript->get_Base();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)