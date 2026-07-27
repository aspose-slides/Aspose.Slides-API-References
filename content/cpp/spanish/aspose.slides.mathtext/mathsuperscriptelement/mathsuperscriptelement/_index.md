---
title: MathSuperscriptElement()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase MathSuperscriptElement.
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathsuperscriptelement/mathsuperscriptelement/
---
## MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

Inicializa una nueva instancia de la clase [MathSuperscriptElement](../).

```cpp
Aspose::Slides::MathText::MathSuperscriptElement::MathSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> superScript)
```

## Observaciones

Ejemplo:
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathSuperscriptElement](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)