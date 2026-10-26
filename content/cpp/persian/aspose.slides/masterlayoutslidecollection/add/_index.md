---
title: Add()
second_title: Aspose.Slides برای C++ مرجع API
description: یک اسلاید طرح جدید را به انتهای مجموعه اضافه می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) روش

یک اسلاید طرح جدید را به انتهای مجموعه اضافه می‌کند.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع طرح برای یک طرح جدید. انواع طرح پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح در حال حاضر پشتیبانی نمی‌شود: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | نام برای یک طرح جدید. اگر نام ارسال‌شده قبلاً استفاده شده باشد، ArgumentException پرتاب می‌شود. اگر پارامتر null ارسال شود، نام به‌طور خودکار بر اساس نوع طرح ارسال‌شده تولید می‌شود (به عنوان مثال \"Title Slide\" یا \"1_Title Slide\", \"2_..\", و غیره). |

### مقدار بازگشتی

اسلاید اضافه شده.

## یادداشت‌ها

۱) طرح افزوده‌شده برای مقدار [SlideLayoutType::Custom](../../slidelayouttype/) از *layoutType* شامل هیچ جای‌نگهدارنده‌ای و هیچ شکلی نیست. ۲) مشابه این متد، متد [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) است که از طریق ویژگی [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) قابل دسترسی است.

## مراجعه

* نوع شمارشی [SlideLayoutType](../../slidelayouttype/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [String](../../../system/string/)
* کلاس [MasterLayoutSlideCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)