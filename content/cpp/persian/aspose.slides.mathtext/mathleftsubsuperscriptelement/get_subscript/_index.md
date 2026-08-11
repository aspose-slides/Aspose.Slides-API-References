---
title: get_Subscript()
second_title: Aspose.Slides برای C++ مرجع API
description: زیرنویس
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_subscript/
---
## MathLeftSubSuperscriptElement::get_Subscript() متد


زیرنویس

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Subscript() override
```

## توضیحات


مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathLeftSubSuperscriptElement](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)