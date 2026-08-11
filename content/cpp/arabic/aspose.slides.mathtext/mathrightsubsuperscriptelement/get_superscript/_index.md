---
title: get_Superscript()
second_title: Aspose.Slides لـ C++ مرجع API
description: معامل الفوقية
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_superscript/
---
## MathRightSubSuperscriptElement::get_Superscript() طريقة

معامل الفوقية

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Superscript() override
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
* فئة [MathRightSubSuperscriptElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)