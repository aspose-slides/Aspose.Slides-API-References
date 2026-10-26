---
title: set_AlignScripts()
second_title: Aspose.Slides için C++ API Referansı
description: Alt ve üst metnin hizalamasını belirler. true olduğunda, alt ve üst metin yatay olarak birbirine hizalanır. false olduğunda, temel şekline göre kernlenir. Varsayılan değer false'tur.
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) yöntemi

Alt metin/üst metnin hizalamasını belirler. True olduğunda, alt ve üst metin yatay olarak birbirine hizalanır. False olduğunda, temel şekline göre kernlenir. Varsayılan değer false'dur.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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

* Sınıf [MathRightSubSuperscriptElement](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)