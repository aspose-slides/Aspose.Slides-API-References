---
title: get_Base()
second_title: Aspose.Slides لـ C++ مرجع API
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() طريقة

معامل Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
```

## ملاحظات


مثال:
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathPhantom](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)