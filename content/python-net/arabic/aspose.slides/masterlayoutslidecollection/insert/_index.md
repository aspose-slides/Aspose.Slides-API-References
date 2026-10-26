---
title: insert method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
يدرج شريحة تخطيط جديدة في الموضع المحدد للمجموعة.

### القيمة المرجعة
الشريحة المُدرجة.



```python
def insert(self, index, layout_type, layout_name):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | فهرس الشريحة الجديدة. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype) | نوع التخطيط لشريحة تخطيط جديدة.<br/><br/>            الأنواع المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            الأنواع غير المدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | اسم لتخطيط جديد. إذا كان الاسم الممرّر مستخدمًا بالفعل سيتم إلقاء ArgumentException.<br/><br/>            إذا تم تمرير معلمة None فإن الاسم يُولد تلقائيًا بناءً على نوع التخطيط الممرّر <br/><br/>            (على سبيل المثال "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

### ملاحظات
التخطيط المُدرج للقيمة SlideLayoutType.Custom من `layout_type` لا يحتوي على أي نائبة ولا على أي أشكال.

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | يتم إلقاؤه إذا تم تمرير قيمة غير مدعومة للمعامل `layout_type`. الأنواع غير المدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | يتم إلقاؤه إذا كان اسم التخطيط `layout_name` مستخدمًا بالفعل في <br/>            هذه المجموعة من التخطيطات. |

### راجع أيضًا
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`MasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/masterlayoutslidecollection)
* التعداد [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)