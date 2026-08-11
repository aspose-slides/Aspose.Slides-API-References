---
title: MathLeftSubSuperscriptElement()
second_title: Aspose.Slides: مرجع API لـ C++
description: تهيء نسخة جديدة من الفئة MathLeftSubSuperscriptElement.
type: docs
weight: 40
url: /ar/aspose.slides.mathtext/mathleftsubsuperscriptelement/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) منشئ

يُهيئ نسخة جديدة من الفئة [MathLeftSubSuperscriptElement](../).

```cpp
Aspose::Slides::MathText::MathLeftSubSuperscriptElement::MathLeftSubSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript, System::SharedPtr<IMathElement> superScript)
```

## ملاحظات

مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathLeftSubSuperscriptElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)