---
title: get_Superscript()
second_title: Referencia de la API de Aspose.Slides para C++
description: Superíndice
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathsuperscriptelement/get_superscript/
---
## IMathSuperscriptElement::get_Superscript() método


Superscript

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Superscript()=0
```

## Observaciones


Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathSuperscriptElement](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)