---
title: insert method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
یک اسلاید طرح جدید را در موقعیت مشخص شدهٔ مجموعه وارد می‌کند.

### Returns
اسلاید وارد شده.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | شاخص اسلاید جدید. |
| layout_type | [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype) | نوع طرح برای یک طرح جدید.<br/><br/>            انواع طرح پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            سایر انواع طرح در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | نام برای یک طرح جدید. اگر نام ارسال شده قبلاً استفاده شده باشد ArgumentException پرتاب خواهد شد.<br/><br/>            اگر مقدار None ارسال شود، نام به صورت خودکار بر اساس نوع طرح ارسال شده تولید می‌شود <br/><br/>            (به عنوان مثال "Title Slide" یا "1_Title Slide", "2_..", و غیره). |

### Remarks
طرح وارد شده برای مقدار SlideLayoutType.Custom از `layout_type` هیچ جای‌دار یا شکلی ندارد.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | در صورتی که مقدار پشتیبانی‌نشده‌ای برای پارامتر `layout_type` ارسال شود. نوع‌های طرح که در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که مقدار نام طرح `layout_name` قبلاً در این مجموعه از طرح‌ها استفاده شده باشد. |

### See Also
* کلاس [`ILayoutSlide`](/slides/python-net/fa/aspose.slides/ilayoutslide)
* کلاس [`IMasterLayoutSlideCollection`](/slides/python-net/fa/aspose.slides/imasterlayoutslidecollection)
* شمارش [`SlideLayoutType`](/slides/python-net/fa/aspose.slides/slidelayouttype)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)