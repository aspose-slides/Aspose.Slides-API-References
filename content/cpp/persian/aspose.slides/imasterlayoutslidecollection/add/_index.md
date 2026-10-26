---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: یک اسلاید طرح جدید را در انتهای مجموعه اضافه می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) متد

یک اسلاید طرح جدید را در انتهای مجموعه اضافه می‌کند.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع طرح برای یک طرح جدید. انواع طرح‌های پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | نام برای یک طرح جدید. اگر نام ارسال‌شده قبلاً استفاده شده باشد، ArgumentException پرتاب خواهد شد. اگر پارامتر null ارسال شود، نام به‌صورت خودکار براساس نوع طرح ارسال‌شده تولید می‌شود (به عنوان مثال "Title Slide" یا "1_Title Slide", "2_..", و غیره). |

### مقدار بازگشتی

Added slide.

## توضیحات

1) Added layout for value [SlideLayoutType::Custom](../../slidelayouttype/) of *layoutType*  contains no placeholders and no shapes. 2) Analogue of this method is method [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) accessed with [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) property. 

## موارد مرتبط

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [String](../../../system/string/)
* کلاس [IMasterLayoutSlideCollection](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)