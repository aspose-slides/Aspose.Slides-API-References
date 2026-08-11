---
title: get_Subscript()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومان زیرنویس
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_subscript/
---
## IMathRightSubSuperscriptElement::get_Subscript() متد


آرگومان زیرنویس

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Subscript()=0
```

## توضیحات


مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = subsuperscript->get_Subscript();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathRightSubSuperscriptElement](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)