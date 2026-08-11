---
title: set_Sound()
second_title: Aspose.Slides برای مرجع API C++
description: نمایانگر صدای در حال پخش پیوند است. IAudio را بنویسید.
type: docs
weight: 196
url: /fa/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) متد

نمایش صدای در حال پخش پیوند. [IAudio](../../iaudio/) را بنویسید.

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت پیوند اولین شکل
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // استخراج صدای پیوند به صورت آرایه بایت
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudio](../../iaudio/)
* کلاس [IHyperlink](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)