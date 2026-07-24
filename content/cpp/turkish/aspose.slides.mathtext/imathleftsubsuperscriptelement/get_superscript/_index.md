---
title: get_Superscript()
second_title: Aspose.Slides for C++ API Referansı
description: Üst Simge
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_superscript/
---
## IMathLeftSubSuperscriptElement::get_Superscript() metodu

Üst Simge

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Superscript()=0
```

## Açıklamalar


Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathLeftSubSuperscriptElement](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)