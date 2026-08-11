---
title: get_Base()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومان Base
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() متد

آرگومان Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## توضیحات

مثال: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // ریشه سوم
auto baseElem = radical->get_Base();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathRadical](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)