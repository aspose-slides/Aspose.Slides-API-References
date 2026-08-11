---
title: WriteShapeStart()
second_title: Aspose.Slides برای مرجع API C++
description: قبل از رندر کردن شکل فراخوانی می‌شود. برای هر شکل یک بار فراخوانی می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید فعلی تمام می‌شود، قطعه HTML اضافه شده درج می‌شود و تصویر جدید بر روی قبلی شروع می‌گردد.
type: docs
weight: 53
url: /fa/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) متد

قبل از رندر شکل فراخوانی می‌شود. برای هر شکل یک بار فراخوانی می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید فعلی تمام می‌شود، قطعه HTML اضافه شده درج می‌گردد و تصویر جدید بالای قبلی شروع می‌شود.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | شی خروجی. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) که در حال رندر شدن است. |

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IHtmlGenerator](../../ihtmlgenerator/)
* کلاس [IShape](../../../aspose.slides/ishape/)
* کلاس [IHtmlFormattingController](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)