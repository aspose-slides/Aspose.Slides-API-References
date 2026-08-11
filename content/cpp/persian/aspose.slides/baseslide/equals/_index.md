---
title: Equals()
second_title: Aspose.Slides برای C++ مرجع API
description: تعیین می‌کند آیا دو نمونه IBaseSlide برابر هستند یا خیر. مقدار بازگشتی بر اساس ساختار اسلاید و محتویات ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسایی‌کننده یکتا، مانند SlideId، و محتویات پویا، مانند مقدار جاری تاریخ در Date Placeholder، را در نظر نمی‌گیرد.
type: docs
weight: 170
url: /fa/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) متد

تعیین می‌کند که آیا دو نمونه [IBaseSlide](../../ibaseslide/) برابر هستند یا خیر. مقدار بازگشتی بر اساس ساختار اسلاید و محتویات ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسایی‌کننده‌ی یکتا، مانند SlideId و محتویات پویا، مانند مقدار تاریخ جاری در Date [Placeholder](../../placeholder/) را در نظر نمی‌گیرد.

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | [IBaseSlide](../../ibaseslide/) برای مقایسه با [IBaseSlide](../../ibaseslide/) فعلی. |

### مقدار بازگشت

**true** اگر [IBaseSlide](../../ibaseslide/) مشخص شده با [IBaseSlide](../../ibaseslide/) فعلی برابر باشد؛ در غیر این صورت، **false**.

## توضیحات

مثال زیر نشان می‌دهد چگونه دو اسلاید را مقایسه کنیم. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IBaseSlide](../../ibaseslide/)
* کلاس [BaseSlide](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)