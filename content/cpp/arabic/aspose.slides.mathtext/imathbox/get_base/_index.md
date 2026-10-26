---
title: get_Base()
second_title: Aspose.Slides للغة C++ مرجع API
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() طريقة



Base معامل

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## ملاحظات


مثال: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathBox](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)