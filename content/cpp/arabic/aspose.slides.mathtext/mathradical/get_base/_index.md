---
title: get_Base()
second_title: Aspose.Slides لمرجع API C++
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() طريقة


معامل Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## ملاحظات


مثال: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathRadical](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)