---
title: get_AlignScripts()
second_title: Aspose.Slides for C++ API Referansı
description: Alt ve üst simgenin hizalamasını belirler. true olduğunda, alt ve üst simgeler birbirine yatay olarak hizalanır. false olduğunda, temel şekline göre kenar boşluğu uygulanır. Varsayılan değer false'tur.
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() metod

Alt ve üst simgenin hizalamasını belirler. true olduğunda, alt ve üst simgeler birbirine yatay olarak hizalanır. false olduğunda, temel şekline göre kenar boşluğu uygulanır. Varsayılan değer false'tur.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
```

## Açıklamalar

Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## İlgili

* Sınıf [MathRightSubSuperscriptElement](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)