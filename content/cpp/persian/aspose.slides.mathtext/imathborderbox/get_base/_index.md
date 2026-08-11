---
title: get_Base()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومان Base
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() method


آرگومان Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## توضیحات


مثال: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathBorderBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)