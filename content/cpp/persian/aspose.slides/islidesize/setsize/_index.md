---
title: SetSize()
second_title: Aspose.Slides برای C++ مرجع API
description: "اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتوا را مقیاس می‌زند. اختصاص هر مقدار غیر از SlideSizeType::Custom، ISlideSize::get_Size را بر اساس نوع انتخاب‌شده تنظیم می‌کند، در حالی که ISlideSize::get_Orientation را حفظ می‌کند."
type: docs
weight: 53
url: /fa/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) متد

اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتویات موجود را مقیاس می‌زند. اختصاص هر مقدار غیر از [SlideSizeType::Custom](../../slidesizetype/)، [ISlideSize::get_Size](../get_size/) را بر اساس نوع انتخاب‌شده تنظیم می‌کند، در حالی که [ISlideSize::get_Orientation](../get_orientation/) را حفظ می‌کند.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | The predefined slide size to apply. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |
## توضیحات

اختصاص هر مقدار غیر از [SlideSizeType::Custom](../../slidesizetype/)، [System::Drawing::Size](../../../system.drawing/size/) را بر اساس نوع انتخاب‌شده تنظیم می‌کند، در حالی که [Orientation](../../orientation/) را حفظ می‌کند. 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) متد

ابعاد اسلاید را به‌صورت صریح تنظیم می‌کند و محتویات موجود را مقیاس می‌زند. این عمل مقدار [ISlideSize::get_Type](../get_type/) را به [SlideSizeType::Custom](../../slidesizetype/) بازنشانی می‌کند و [ISlideSize::get_Orientation](../get_orientation/) را تنظیم می‌کند.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |
## توضیحات

این مقدار [ISlideSize::get_Type](../get_type/) را به [SlideSizeType::Custom](../../slidesizetype/) بازنشانی می‌کند و [Orientation](../../orientation/) را تنظیم می‌کند. 

## مراجع

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* کلاس [ISlideSize](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)