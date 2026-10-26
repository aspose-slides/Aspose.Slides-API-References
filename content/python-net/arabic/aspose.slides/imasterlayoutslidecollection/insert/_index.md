---
title: insert method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
يدرج شريحة تخطيط جديدة في الموضع المحدد من مجموعة الشرائح.

### إرجاع
الشريحة التي تم إدراجها.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | مؤشر الشريحة الجديدة. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype) | نوع التخطيط لتخطيط جديد.<br/><br/>            أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            أنواع التخطيط الأخرى غير المدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | اسم لتخطيط جديد. إذا كان الاسم الممرر مستخدمًا بالفعل سيتم رمي ArgumentException.<br/><br/>            إذا تم تمرير معلمة None فسيتم توليد الاسم تلقائيًا وفقًا لنوع التخطيط الممرر <br/><br/>            (على سبيل المثال "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

### ملاحظات
التخطيط المُدرج للقيمة SlideLayoutType.Custom من `layout_type` لا يحتوي على عناصر نائب ولا أشكال.

### الاستثناءات
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | يُرمى إذا تم تمرير قيمة غير مدعومة للمعلمة `layout_type`. أنواع التخطيط غير المدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | يُرمى إذا كانت قيمة اسم التخطيط `layout_name` مستخدمة بالفعل في <br/>            مجموعة التخطيطات هذه. |

### انظر أيضًا
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`IMasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/imasterlayoutslidecollection)
* التعداد [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)