---
title: WriteShapeEnd()
second_title: راهنمای API Aspose.Slides برای C++
description: قبل از رندر کردن شکل فراخوانی می‌شود. یک بار برای هر شکل فراخوانی می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید فعلی تمام می‌شود، بخش HTML افزوده می‌شود و تصویر جدید بر روی تصویر قبلی آغاز می‌شود.
type: docs
weight: 66
url: /fa/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) متد

قبل از رندر کردن شکل فراخوانی می‌شود. یک بار برای هر شکل فراخوانی می‌شود. اگر این تابع چیزی را به generator بنویسد، تولید تصویر اسلاید فعلی تمام خواهد شد، بخش html اضافه شده وارد می‌شود و تصویر جدید روی تصویر قبلی آغاز خواهد شد.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | شی خروجی. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) که آخرین بار رندر می‌شود. |

## مراجعه

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IHtmlGenerator](../../ihtmlgenerator/)
* کلاس [IShape](../../../aspose.slides/ishape/)
* کلاس [IHtmlFormattingController](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)