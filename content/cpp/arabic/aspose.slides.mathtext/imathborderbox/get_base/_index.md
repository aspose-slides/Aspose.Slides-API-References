---
title: get_Base()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() طريقة


معامل Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## ملاحظات


مثال:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathBorderBox](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)