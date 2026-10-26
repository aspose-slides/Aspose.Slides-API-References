---
title: get_Base()
second_title: مرجع API Aspose.Slides برای C++
description: آرگومانی که به آن اکسنت اعمال شده است
type: docs
weight: 1
url: /fa/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() متد


آرگومانی که به آن اکسنت اعمال شده است

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## ملاحظات


مثال: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathAccent](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)