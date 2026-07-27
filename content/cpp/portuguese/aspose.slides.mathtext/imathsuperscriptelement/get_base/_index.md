---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathsuperscriptelement/get_base/
---
## IMathSuperscriptElement::get_Base() método


Argumento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Base()=0
```

## Observações


Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathSuperscriptElement](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)