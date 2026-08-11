---
title: get_Superscript()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: معامل النص الفوقي
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_superscript/
---
## IMathRightSubSuperscriptElement::get_Superscript() method


معامل النص الفوقي

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Superscript()=0
```

## ملاحظات


مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = subsuperscript->get_Superscript();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathRightSubSuperscriptElement](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)