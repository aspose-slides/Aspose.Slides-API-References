---
title: get_Sound()
second_title: Aspose.Slides برای مرجع API C++
description: صداپخش پیوند را نشان می‌دهد. مطالعه کنید IAudio.
type: docs
weight: 183
url: /fa/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() متد

صدای پخش‌شدهٔ پیوند را نشان می‌دهد. مطالعه کنید [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## نکات

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت اولین هایپرلینک شکل
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // استخراج صدای هایپرلینک به صورت آرایه بایت
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudio](../../iaudio/)
* کلاس [IHyperlink](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)