---
title: MathLeftSubSuperscriptElement()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe MathLeftSubSuperscriptElement.
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/mathleftsubsuperscriptelement/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

Inicializa uma nova instância da classe [MathLeftSubSuperscriptElement](../).

```cpp
Aspose::Slides::MathText::MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript, System::SharedPtr<IMathElement> superScript)
```

## Observações

Exemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathLeftSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)