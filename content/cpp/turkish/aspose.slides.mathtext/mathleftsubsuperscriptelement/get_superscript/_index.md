---
title: get_Superscript()
second_title: Aspose.Slides için C++ API Referansı
description: Üst Simge
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_superscript/
---
## MathLeftSubSuperscriptElement::get_Superscript() method


Üst Simge

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Superscript() override
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

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathLeftSubSuperscriptElement](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)