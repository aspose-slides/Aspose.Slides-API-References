---
title: Add()
second_title: مرجع API Aspose.Slides برای C++
description: یک اسلاید طرح جدید به ارائه اضافه می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) متد

یک اسلاید طرح جدید به ارائه اضافه می‌شود.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | اسلاید اصلی برای یک طرح جدید. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع طرح برای یک طرح جدید. انواع طرح‌های پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. انواع طرح دیگر در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | نام برای یک طرح جدید. اگر نام ارائه‌شده قبلاً استفاده شده باشد ArgumentException رخ خواهد داد. اگر پارامتر null پاس داده شود، نام به صورت خودکار بر اساس نوع طرح پاس داده شده تولید می‌شود (مثلاً "Title Slide" یا "1_Title Slide"، "2_.." و غیره). |

### مقدار بازگشت

اسلاید اضافه شده.

## نکات

1) طرح اضافه‌شده برای مقدار [SlideLayoutType::Custom](../../slidelayouttype/) از *layoutType* حاوی هیچ جای‌نگهدارنده و هیچ شکلی نیست. 2) معادل این متد، متد [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) است که از ویژگی [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) دسترسی می‌یابد. 

## مراجع

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [IGlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)