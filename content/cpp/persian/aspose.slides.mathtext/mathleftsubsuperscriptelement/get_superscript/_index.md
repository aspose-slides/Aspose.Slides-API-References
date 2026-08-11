---
title: get_Superscript()
second_title: مرجع API Aspose.Slides برای C++
description: بالنویس
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_superscript/
---
## MathLeftSubSuperscriptElement::get_Superscript() متد


بالنویس

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Superscript() override
```

## توضیحات


مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathLeftSubSuperscriptElement](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)