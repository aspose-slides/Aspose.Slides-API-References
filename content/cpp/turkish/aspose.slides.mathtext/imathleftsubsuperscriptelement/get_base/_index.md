---
title: get_Base()
second_title: Aspose.Slides için C++ API Referansı
description: Temel argüman
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_base/
---
## IMathLeftSubSuperscriptElement::get_Base() yöntemi

Temel argüman

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Base()=0
```

## Açıklamalar

Örnek:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = leftSubSuperscript->get_Base();
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathLeftSubSuperscriptElement](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)