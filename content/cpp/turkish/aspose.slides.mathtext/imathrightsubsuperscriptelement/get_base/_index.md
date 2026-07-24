---
title: get_Base()
second_title: Aspose.Slides for C++ API Referansı
description: Temel argüman
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_base/
---
## IMathRightSubSuperscriptElement::get_Base() metodu


Temel argüman

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Base()=0
```

## Açıklamalar


Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = subsuperscript->get_Base();
```

## Bkz.

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathRightSubSuperscriptElement](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)