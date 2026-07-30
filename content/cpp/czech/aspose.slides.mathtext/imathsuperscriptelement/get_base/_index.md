---
title: get_Base()
second_title: Aspose.Slides pro C++ API Reference
description: Základní argument
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathsuperscriptelement/get_base/
---
## IMathSuperscriptElement::get_Base() metoda

Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Base()=0
```

## Poznámky

Příklad:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathElement](../../imathelement/)
* třída [IMathSuperscriptElement](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)