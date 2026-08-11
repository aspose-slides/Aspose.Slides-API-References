---
title: Insert()
second_title: Aspose.Slides برای C++ مرجع API
description: یک اسلاید چیدمان جدید را در موقعیت مشخص شده از مجموعه اضافه می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) متد

یک اسلاید چیدمان جدید را در موقعیت مشخص شده از مجموعه می‌افزاید.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس اسلاید جدید. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع چیدمان برای یک چیدمان جدید. نوع‌های چیدمان پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر نوع‌های چیدمان در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | نام برای یک چیدمان جدید. اگر نام ارسال‌شده قبلاً استفاده شده باشد ArgumentException پرتاب خواهد شد. اگر پارامتر null ارسال شود، نام به‌صورت خودکار بر اساس نوع چیدمان ارسال‌شده تولید می‌شود (به عنوان مثال "Title Slide" یا "1_Title Slide", "2_..", و غیره). |

### مقدار بازگشتی

اسلاید وارد شده.

## توضیحات

چیدمان وارد شده برای مقدار [SlideLayoutType::Custom](../../slidelayouttype/) از *layoutType* شامل هیچ جای‌نگهدارنده‌ای و هیچ شکلی نیست.

## موارد مرتبط

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)