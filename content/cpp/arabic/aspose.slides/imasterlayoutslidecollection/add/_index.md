---
title: Add()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) طريقة

يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### الحجج

| معامل | نوع | الوصف |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع التخطيط لشريحة جديدة. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. أنواع التخطيط الأخرى غير مدعومة الآن: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | اسم لتخطيط جديد. إذا كان الاسم الممرّر مستخدمًا بالفعل سيتم إلقاء استثناء ArgumentException. إذا تم تمرير معامل null فسيتم إنشاء الاسم تلقائيًا بناءً على نوع التخطيط الممرّر (على سبيل المثال "Title Slide" أو "1_Title Slide", "2_..", إلخ). |

### قيمة الإرجاع

شريحة مضافة.

## ملاحظات

1) تم إضافة تخطيط للقيمة [SlideLayoutType::Custom](../../slidelayouttype/) من *layoutType* ولا يحتوي على أي عناصر نائب ولا أشكال. 2) النسخة المماثلة لهذه الطريقة هي الطريقة [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) التي يتم الوصول إليها عبر خاصية [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## انظر أيضًا

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [String](../../../system/string/)
* فئة [IMasterLayoutSlideCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)