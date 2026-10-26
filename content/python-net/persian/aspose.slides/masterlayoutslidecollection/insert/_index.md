---
title: insert method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
یک اسلاید طرح جدید را در موقعیت مشخص شده از مجموعه اضافه می‌کند.

### بازگشت
اسلاید اضافه‌شده.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس اسلاید جدید. |
| layout_type | [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype) | نوع طرح برای یک طرح جدید.<br/><br/>            انواع طرح‌های پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            سایر انواع طرح در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | نام برای یک طرح جدید. اگر نام عبور شده در حال حاضر استفاده باشد ArgumentException پرتاب می‌شود.<br/><br/>            اگر پارامتر None عبور شود، نام به‌صورت خودکار بر اساس نوع طرح عبور شده تولید می‌شود <br/><br/>            (به عنوان مثال "Title Slide" یا "1_Title Slide", "2_..", و غیره). |

### ملاحظات
طرح اضافه‌شده برای مقدار SlideLayoutType.Custom از `layout_type` شامل هیچ جای‌نگهدارنده‌ای و هیچ شکلی نیست.

### استثنائات
| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | اگر مقدار پشتیبانی‌نشده‌ای از پارامتر `layout_type` عبور شود، پرتاب می‌شود. انواع طرح که در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | اگر مقدار نام طرح `layout_name` در <br/>            این مجموعهٔ طرح‌ها قبلاً استفاده شده باشد، پرتاب می‌شود. |

### مراجع
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`MasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/masterlayoutslidecollection)
* enumeration [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)