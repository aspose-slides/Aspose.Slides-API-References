---
title: get_Base()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومانی که لهجه به آن اعمال شده است
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() متد


آرگومانی که لهجه به آن اعمال شده است

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## توضیحات


مثال:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathAccent](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)