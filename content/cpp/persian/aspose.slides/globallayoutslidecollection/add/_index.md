---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: یک اسلاید طرح جدید را به ارائه اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) متد

یک اسلاید طرح جدید به ارائه اضافه می‌کند.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | اسلاید اصلی برای یک طرح جدید. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع طرح برای یک طرح جدید. انواع طرح‌های پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | نام برای یک طرح جدید. اگر نام ارسال‌شده قبلاً استفاده شده باشد، ArgumentException پرتاب می‌شود. اگر پارامتر null ارسال شود، نام به‌طور خودکار بر اساس نوع طرح ارسال‌شده تولید می‌شود (به عنوان مثال "Title Slide" یا "1_Title Slide"، "2_.." و غیره). |

### مقدار بازگشتی

اسلاید اضافه‌شده.

## توضیحات

1) طرح اضافه‌شده برای مقدار [SlideLayoutType::Custom](../../slidelayouttype/) از *layoutType* هیچ جای‌نگه‌داری و هیچ شکلی ندارد. 2) معادل این متد، متد [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) است که با ویژگی [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) دسترسی پیدا می‌کند. 

## موارد مرتبط

* شمارش [SlideLayoutType](../../slidelayouttype/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ILayoutSlide](../../ilayoutslide/)
* کلاس [IMasterSlide](../../imasterslide/)
* کلاس [String](../../../system/string/)
* کلاس [GlobalLayoutSlideCollection](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)