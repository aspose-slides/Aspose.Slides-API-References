---
title: set_Sound()
second_title: Aspose.Slides برای مرجع API C++
description: نمایش‌دهندهٔ صدای پخش‌شدهٔ پیوند. IAudio را بنویسید.
type: docs
weight: 300
url: /fa/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) متد

نمایش‌دهندهٔ صدای پخش‌شدهٔ پیوند. [IAudio](../../iaudio/) را بنویسید.

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## توضیحات



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// دریافت پیوند کلیک اولین شکل
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // استخراج صدای پیوند در آرایه بایتی
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## موارد مرتبط

* نوع‌تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IAudio](../../iaudio/)
* کلاس [Hyperlink](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)