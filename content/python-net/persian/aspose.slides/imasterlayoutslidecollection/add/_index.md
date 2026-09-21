---
title: add method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
یک اسلاید طرح جدید به انتهای مجموعه اضافه می‌کند.

### بازگشت
اسلاید اضافه شده.



```python
def add(self, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype) | نوع طرح برای یک طرح جدید.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | نام برای یک طرح جدید. اگر نام ارائه شده قبلاً در استفاده باشد ArgumentException پرتاب خواهد شد.<br/><br/>            اگر پارامتر None پاس شود، نام به‌صورت خودکار نسبت به نوع طرح پاس شده تولید می‌شود.<br/><br/>            (for example "Title Slide" or "1_Title Slide", "2_..", etc.). |

### توضیحات
1) طرح اضافه شده برای مقدار SlideLayoutType.Custom از `layout_type` شامل هیچ جای‌نگهدار و هیچ شکلی نیست.
2) معادل این متد، متد **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** است که با ویژگی [`IPresentation.layout_slides`](/slides/python-net/fa/aspose.slides/ipresentation/layout_slides) قابل دسترسی است.

### استثناها
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | در صورتی که مقدار پشتیبانی نشده‌ای برای پارامتر `layout_type` پاس شود، پرتاب می‌شود. Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که مقدار نام طرح `layout_name` در این مجموعه از طرح‌ها قبلاً استفاده شده باشد، پرتاب می‌شود. |

### موارد مرتبط
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`IMasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/imasterlayoutslidecollection)
* شمارش [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)