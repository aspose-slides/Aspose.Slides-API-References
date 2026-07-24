---
title: get_Superscript()
second_title: Aspose.Slides için C++ API Referansı
description: Üst simge argümanı
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_superscript/
---
## IMathRightSubSuperscriptElement::get_Superscript() metodu

Üst simge argümanı

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Superscript()=0
```

## Açıklamalar

Örnek:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = subsuperscript->get_Superscript();
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathRightSubSuperscriptElement](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)