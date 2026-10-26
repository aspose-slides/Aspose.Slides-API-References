---
title: get_Base()
second_title: Aspose.Slides برای C++ مرجع API
description: آرگومان Base
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() متد

آرگومان Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## توضیحات

مثال:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathRadical](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)