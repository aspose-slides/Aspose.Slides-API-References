---
title: MathLeftSubSuperscriptElement()
second_title: Aspose.Slides için C++ API Referansı
description: MathLeftSubSuperscriptElement sınıfının yeni bir örneğini başlatır.
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/mathleftsubsuperscriptelement/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

Yeni bir [MathLeftSubSuperscriptElement](../) sınıfının örneğini başlatır.

```cpp
Aspose::Slides::MathText::MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript, System::SharedPtr<IMathElement> superScript)
```

## Açıklamalar

Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathLeftSubSuperscriptElement](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)