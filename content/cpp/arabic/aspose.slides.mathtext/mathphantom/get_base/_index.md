---
title: get_Base()
second_title: Aspose.Slides لـ C++ مرجع API
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() طريقة


معامل Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## ملاحظات


مثال:
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathPhantom](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)