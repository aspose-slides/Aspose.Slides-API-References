---
title: get_Superscript()
second_title: Aspose.Slides لـ C++ مرجع API
description: حرف علوي
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_superscript/
---
## MathLeftSubSuperscriptElement::get_Superscript() طريقة

Superscript

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Superscript() override
```

## ملاحظات

مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathElement](../../imathelement/)
* الفئة [MathLeftSubSuperscriptElement](../)
* نطاق الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)