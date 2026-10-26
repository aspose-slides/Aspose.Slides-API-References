---
title: add method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
يضيف شريحة تخطيط جديدة إلى العرض التقديمي.

### القيمة المرجعة

الشريحة المضافة.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide) | شريحة رئيسية لتخطيط جديد. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype) | نوع التخطيط لتخطيط جديد.<br/><br/>            أنواع التخطيطات المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            أنواع التخطيطات الأخرى غير مدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | اسم لتخطيط جديد. إذا كان الاسم الممرَّر مُستخدمًا بالفعل سيتم إلقاء ArgumentException.<br/><br/>            إذا تم تمرير معامل None فسيتم إنشاء الاسم تلقائيًا بناءً على نوع التخطيط الممرَّر <br/><br/>            (على سبيل المثال "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

### ملاحظات

1) التخطيط المضاف للقيمة SlideLayoutType.Custom من `layout_type` لا يحتوي على عناصر نائب ولا أشكال.
2) النظير لهذه الطريقة هو الطريقة **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** التي يتم الوصول إليها عبر خاصية [`IMasterSlide.layout_slides`](/slides/python-net/ar/aspose.slides/imasterslide/layout_slides).

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | تم إلقاء الاستثناء إذا تم تمرير قيمة غير مدعومة للمعامل `layout_type`. أنواع التخطيطات غير المدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | تم إلقاء الاستثناء إذا كان `master` يساوي None. |
| **RuntimeError(Proxy error(ArgumentException))** | تم إلقاء الاستثناء إذا كان `master` يخص عرضًا تقديميًا آخر. |
| **RuntimeError(Proxy error(ArgumentException))** | تم إلقاء الاستثناء إذا كان اسم التخطيط `layout_name` مُستخدمًا بالفعل في <br/>            مجموعة التخطيطات الخاصة بـ `master`. |



### انظر أيضًا
* الفئة [`GlobalLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/globallayoutslidecollection)
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide)
* التعداد [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)