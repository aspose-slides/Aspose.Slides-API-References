---
title: get_Sound()
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر صدای در حال پخش پیوند است. بخوانید IAudio.
type: docs
weight: 287
url: /fa/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() متد


نمایانگر صدای در حال پخش پیوند است. بخوانید [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## توضیحات



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

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudio](../../iaudio/)
* کلاس [Hyperlink](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)