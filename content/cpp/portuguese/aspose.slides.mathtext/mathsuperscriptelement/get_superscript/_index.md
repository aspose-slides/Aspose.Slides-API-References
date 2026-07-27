---
title: get_Superscript()
second_title: Referência da API Aspose.Slides para C++
description: Sobrescrito
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathsuperscriptelement/get_superscript/
---
## MathSuperscriptElement::get_Superscript() método

Sobrescrito

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Superscript() override
```

## Observações

Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathSuperscriptElement](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)