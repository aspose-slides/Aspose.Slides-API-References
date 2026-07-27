---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_base/
---
## IMathRightSubSuperscriptElement::get_Base() method


Argumento base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Base()=0
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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathRightSubSuperscriptElement](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)