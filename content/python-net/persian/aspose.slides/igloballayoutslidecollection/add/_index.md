---
title: add method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
یک اسلاید طرح جدید به ارائه اضافه می‌کند.

### Returns
اسلاید اضافه شده.

```python
def add(self, master, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide) | اسلاید اصلی برای یک طرح جدید. |
| layout_type | [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype) | نوع طرح برای یک طرح جدید.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | نام برای یک طرح جدید. اگر نام ارسال‌شده قبلاً استفاده شده باشد، ArgumentException پرتاب خواهد شد.<br/><br/>            اگر پارامتر None ارسال شود، نام به‌صورت خودکار بر اساس نوع طرح ارسال‌شده تولید می‌شود.<br/><br/>            (for example "Title Slide" or "1_Title Slide", "2_..", etc.). |

### Remarks
1) طرح اضافه شده برای مقدار SlideLayoutType.Custom از `layout_type` شامل هیچ کدام از متغیرهای نگهدارنده و هیچ شکلی نیست.
2) معادل این متد، متد **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** است که از ویژگی [`IMasterSlide.layout_slides`](/slides/python-net/fa/aspose.slides/imasterslide/layout_slides) دسترسی پیدا می‌کند.

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | در صورتی که مقدار پشتیبانی‌نشده‌ای برای پارامتر `layout_type` ارسال شود، پرتاب می‌شود. Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | در صورتی که `master` مقدار None باشد، پرتاب می‌شود. |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که `master` به ارائه دیگری تعلق داشته باشد، پرتاب می‌شود. |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که مقدار نام طرح `layout_name` قبلاً در مجموعه طرح‌های `master` استفاده شده باشد، پرتاب می‌شود. |

### See Also
* کلاس [`IGlobalLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/igloballayoutslidecollection)
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`IMasterSlide`](/slides/python-net/fa/aspose.slides/imasterslide)
* شمارش [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)