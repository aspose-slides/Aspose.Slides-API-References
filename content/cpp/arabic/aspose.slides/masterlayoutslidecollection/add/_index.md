---
title: Add()
second_title: Aspose.Slides للـ C++ مرجع API
description: يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) طريقة


يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```


### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع التخطيط لشريحة جديدة. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. أنواع التخطيط الأخرى غير مدعومة حاليًا: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | اسم لتخطيط جديد. إذا كان الاسم الممرّر مستخدمًا بالفعل سيتم رفع استثناء ArgumentException. إذا تم تمرير قيمة فارغة (null) فإن الاسم يُولد تلقائيًا اعتمادًا على نوع التخطيط الممرّر (على سبيل المثال "Title Slide" أو "1_Title Slide", "2_..", إلخ). |

### قيمة الإرجاع

تمت إضافة الشريحة.

## ملاحظات



1) تم إضافة تخطيط للقيمة [SlideLayoutType::Custom](../../slidelayouttype/) من *layoutType* لا يحتوي على أي عناصر نائبة ولا أشكال. 2) النسخة المقابلة لهذه الطريقة هي الطريقة [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) التي يتم الوصول إليها عبر الخاصية [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 

## انظر أيضًا

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [String](../../../system/string/)
* فئة [MasterLayoutSlideCollection](../)
* مساحة اسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)