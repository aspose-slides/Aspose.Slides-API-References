---
title: Add()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: يضيف شريحة تخطيط جديدة إلى العرض التقديمي.
type: docs
weight: 14
url: /ar/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) طريقة

يضيف شريحة تخطيط جديدة إلى العرض التقديمي.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | شريحة رئيسية لتخطيط جديد. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع التخطيط لتخطيط جديد. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. أنواع التخطيط الأخرى غير مدعومة الآن: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | اسم لتخطيط جديد. إذا كان الاسم المُمرّر مُستخدمًا بالفعل، سيتم رمي الاستثناء ArgumentException. إذا تم تمرير معامل فارغ (null) فإن الاسم يُولد تلقائيًا بناءً على نوع التخطيط المُمرّر (مثال: "Title Slide" أو "1_Title Slide" أو "2_.."، إلخ). |

### القيمة المرجعة

شريحة مضافة.

## ملاحظات

1) تم إضافة تخطيط للقيمة [SlideLayoutType::Custom](../../slidelayouttype/) من *layoutType* لا يحتوي على أي عناصر نائبة ولا أشكال. 2) نظير هذه الطريقة هو الطريقة [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) التي يمكن الوصول إليها عبر خاصية [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## انظر أيضًا

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [GlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)