---
title: add method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.

### Returns
الشريحة المضافة.

```python
def add(self, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype) | نوع التخطيط لشريحة تخطيط جديدة.<br/><br/> الأنواع المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/> الأنواع غير المدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | اسم لتخطيط جديد. إذا كان الاسم الممرّر قيد الاستخدام بالفعل سيتم رمي استثناء ArgumentException.<br/><br/> إذا تم تمرير معامل None فسيتم توليد الاسم تلقائيًا بناءً على نوع التخطيط الممرّر <br/><br/> (على سبيل المثال "Title Slide" أو "1_Title Slide", "2_..", إلخ). |

### Remarks
1) يحتوي التخطيط المضاف للقيمة SlideLayoutType.Custom لـ `layout_type` على لا إحاطات ولا أشكال.  
2) نظير هذه الطريقة هو الطريقة **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** التي يتم الوصول إليها عبر الخاصية [`IPresentation.layout_slides`](/slides/python-net/ar/aspose.slides/ipresentation/layout_slides).

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | يتم رمي الاستثناء إذا تم تمرير قيمة غير مدعومة للمعامل `layout_type`. الأنواع غير المدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | يتم رمي الاستثناء إذا كان قيمة اسم التخطيط `layout_name` قيد الاستخدام بالفعل في <br/> هذه مجموعة التخطيطات. |

### See Also
* فئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* فئة [`MasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/masterlayoutslidecollection)
* تعداد [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)