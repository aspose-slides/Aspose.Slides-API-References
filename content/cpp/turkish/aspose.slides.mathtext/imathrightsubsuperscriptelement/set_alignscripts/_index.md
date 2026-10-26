---
title: set_AlignScripts()
second_title: Aspose.Slides için C++ API Referansı
description: Alt/üst simgenin hizalamasını belirtir. true olduğunda, alt simge ve üst simge yatay olarak birbirine hizalanır. false olduğunda, temel şeklinin biçimine göre kenar boşluğu uygulanır. Varsayılan değer false'tur.
type: docs
weight: 53
url: /tr/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) metot


Üst/alt simgenin hizalamasını belirtir. true olduğunda, alt simge ve üst simge yatay olarak birbirine hizalanır. false olduğunda, temel şeklinin şekline göre kenar boşluğu uygulanır. Varsayılan değer false'tur.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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

## Bakınız

* Sınıf [IMathRightSubSuperscriptElement](../)
* İsim alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)