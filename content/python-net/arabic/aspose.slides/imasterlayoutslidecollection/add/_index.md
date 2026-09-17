---
title: add method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.

### القيمة المرجعة
تمت إضافة الشريحة.

```python
def add(self, layout_type, layout_name):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype) | نوع التخطيط لشريحة تخطيط جديدة.<br/><br/> الأنواع المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/> الأنواع الأخرى غير مدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | اسم لشريحة تخطيط جديدة. إذا كان الاسم الممرَّر مستخدمًا بالفعل سيتم إثارة استثناء ArgumentException.<br/><br/> إذا تم تمرير معامل None فسيتم إنشاء الاسم تلقائيًا بناءً على نوع التخطيط الممرَّر <br/><br/> (على سبيل المثال "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

### ملاحظات
1) يحتوي التخطيط المضاف للقيمة SlideLayoutType.Custom من `layout_type` على لا أماكن حجز ولا أشكال.
2) نظير هذه الطريقة هو
method **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**
المُتاح عبر خاصية [`IPresentation.layout_slides`](/slides/python-net/ar/aspose.slides/ipresentation/layout_slides).

### الاستثناءات
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | يُطرح إذا تم تمرير قيمة غير مدعومة للمعامل `layout_type`. أنواع التخطيط غير المدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح إذا كان اسم التخطيط `layout_name` مستخدمًا بالفعل في <br/>            مجموعة التخطيطات هذه. |

### انظر أيضًا
* الفئة [`ILayoutSlide`](/slides/python-net/ar/aspose.slides/ilayoutslide)
* الفئة [`IMasterLayoutSlideCollection`](/slides/python-net/ar/aspose.slides/imasterlayoutslidecollection)
* تعداد [`SlideLayoutType`](/slides/python-net/ar/aspose.slides/slidelayouttype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)