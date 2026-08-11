---
title: get_Base()
second_title: مرجع API Aspose.Slides برای C++
description: پارامتر Base
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() method

پارامتر Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## توضیحات


مثال:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathBox](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)