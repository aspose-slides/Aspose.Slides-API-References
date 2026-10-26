---
title: get_AlignScripts()
second_title: Aspose.Slides için C++ API Referansı
description: Alt ve üst indeksin hizalamasını belirtir. true olduğunda, alt ve üst indeks birbirine yatay olarak hizalanır. false olduğunda, temel şeklinin şekline göre kenarlanır. Varsayılan değer false'tur.
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() metot

Alt ve üst indeksin hizalamasını belirtir. true olduğunda, alt ve üst indeks birbirine yatay olarak hizalanır. false olduğunda, temel şeklinin şekline göre kenarlanır. Varsayılan değer false'tur.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

## Ayrıca Bakınız

* Sınıf [IMathRightSubSuperscriptElement](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)