---
title: get_Base()
second_title: Aspose.Slides C++ API Referencia
description: Alap argumentum
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathsuperscriptelement/get_base/
---
## MathSuperscriptElement::get_Base() metódus


Alap argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Base() override
```

## Megjegyzés


Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathSuperscriptElement](../)
* Névtere [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)