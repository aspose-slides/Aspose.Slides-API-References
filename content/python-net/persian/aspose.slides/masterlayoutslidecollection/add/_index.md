---
title: add method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
یک اسلاید چیدمان جدید به انتهای مجموعه اضافه می‌کند.

### بازگشت

اسلاید اضافه‌شده.



```python
def add(self, layout_type, layout_name):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype) | نوع چیدمان برای یک چیدمان جدید.<br/><br/>            انواع چیدمان‌های پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            سایر انواع چیدمان در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | نام برای یک چیدمان جدید. اگر نام داده‌شده قبلاً استفاده شده باشد ArgumentException رخ خواهد داد.<br/><br/>            اگر پارامتر None پاس شود، نام به‌صورت خودکار بر اساس نوع چیدمان داده‌شده تولید می‌شود<br/><br/>            (به‌عنوان مثال "Title Slide" یا "1_Title Slide"، "2_.." و غیره). |

### یادداشت‌ها

1) چیدمان اضافه‌شده برای مقدار SlideLayoutType.Custom از `layout_type` شامل هیچ جای‌گذاری و هیچ شکل‌ای نیست.  
2) معادل این متد، متد **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** است که با خصوصیت [`IPresentation.layout_slides`](/slides/python-net/fa/aspose.slides/ipresentation/layout_slides) دسترسی می‌شود.

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | در صورتی که مقدار پشتیبانی‌نشده‌ای برای پارامتر `layout_type` پاس شود، خطا رخ می‌دهد. انواع چیدمان که در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که مقدار نام چیدمان `layout_name` قبلاً در این مجموعه چیدمان‌ها استفاده شده باشد، خطا رخ می‌دهد.<br/> |

### همچنین ببینید
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`MasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection)
* شمارش [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)