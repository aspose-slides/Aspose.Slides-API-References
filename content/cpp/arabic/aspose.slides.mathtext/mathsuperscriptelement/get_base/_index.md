---
title: get_Base()
second_title: Aspose.Slides لمرجع API لـ C++
description: معامل Base
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathsuperscriptelement/get_base/
---
## MathSuperscriptElement::get_Base() طريقة

معامل Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Base() override
```

## ملاحظات

مثال:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathSuperscriptElement](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)