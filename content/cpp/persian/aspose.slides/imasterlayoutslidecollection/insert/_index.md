---
title: Insert()
second_title: Aspose.Slides برای مرجع API C++
description: یک اسلاید طرح جدید را در موقعیت مشخص شده از مجموعه درج می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) متد

یک اسلاید طرح جدید را در موقعیت مشخصی از مجموعه درج می‌کند.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس اسلاید جدید. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع طرح برای یک طرح جدید. انواع طرح پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | نام برای یک طرح جدید. اگر نام داده‌شده قبلاً استفاده شده باشد ArgumentException رخ می‌دهد. اگر پارامتر null پاس داده شود، نام به‌صورت خودکار بر اساس نوع طرح داده‌شده تولید می‌شود (به عنوان مثال \"Title Slide\" یا \"1_Title Slide\", \"2_..\", و غیره). |

### مقدار بازگشتی

اسلاید درج‌شده.

## توضیحات

طرح درج‌شده برای مقدار [SlideLayoutType::Custom](../../slidelayouttype/) از *layoutType* هیچ مکان‌نگه‌دارنده‌ای و هیچ شکل‌ای ندارد. 

## موارد مرتبط

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [String](../../../system/string/)
* کلاس [IMasterLayoutSlideCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)