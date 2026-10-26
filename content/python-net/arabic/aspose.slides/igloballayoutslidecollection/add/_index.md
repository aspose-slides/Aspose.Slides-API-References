---
title: add method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Adds a new layout slide to the presentation.

### القيمة المرجعة

الشريحة المضافة.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide) | الشريحة الرئيسية لتصميم جديد. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype) | نوع التخطيط لتصميم جديد.<br/><br/>            Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | اسم لتصميم جديد. إذا كان الاسم الممرّر مُستَخدمًا بالفعل سيتم إلقاء ArgumentException.<br/><br/>            إذا تم تمرير معامل None فسيتم إنشاء الاسم تلقائيًا وفقًا لنوع التخطيط الممرّر <br/><br/>            (مثال: "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

### ملاحظات

1) التخطيط المضاف للقيمة SlideLayoutType.Custom من `layout_type` لا يحتوي على نائبات ولا أشكال.
2) النظير لهذه الطريقة هو الطريقة **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** التي يتم الوصول إليها عبر الخاصية [`IMasterSlide.layout_slides`](/slides/python-net/ar/aspose.slides/imasterslide/layout_slides).

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | يُطلق إذا تم تمرير قيمة غير مدعومة للمعامل `layout_type`. Layout types that are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | يُطلق إذا كان `master` هو None. |
| **RuntimeError(Proxy error(ArgumentException))** | يُطلق إذا كان `master` ينتمي إلى عرض تقديمي آخر. |
| **RuntimeError(Proxy error(ArgumentException))** | يُطلق إذا كان قيمة اسم التخطيط `layout_name` مُستَخدة بالفعل في مجموعة التخطيطات الخاصة بـ `master`. |



### انظر أيضًا
* الفئة [`IGlobalLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/igloballayoutslidecollection)
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`IMasterSlide`](/slides/python-net/ar/aspose.slides/imasterslide)
* التعداد [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)