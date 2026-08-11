---
title: get_Base()
second_title: Aspose.Slides لمرجع API C++
description: معامل Base
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() طريقة

معامل Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## ملاحظات

مثال:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // جذر مكعب
auto baseElem = radical->get_Base();
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathRadical](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)