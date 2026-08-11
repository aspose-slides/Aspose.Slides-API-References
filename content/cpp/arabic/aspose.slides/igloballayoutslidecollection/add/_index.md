---
title: Add()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف شريحة تخطيط جديدة إلى العرض التقديمي.
type: docs
weight: 14
url: /ar/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method

يضيف شريحة تخطيط جديدة إلى العرض التقديمي.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | شريحة رئيسية لتخطيط جديد. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع التخطيط لتخطيط جديد. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. أنواع التخطيط الأخرى غير مدعومة حالياً: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | اسم لتخطيط جديد. إذا كان الاسم الممرَّر مستخدمًا بالفعل سيتم إلقاء استثناء ArgumentException. إذا تم تمرير معلمة null فسيتم توليد الاسم تلقائيًا وفقًا لنوع التخطيط الممرَّر (على سبيل المثال "Title Slide" أو "1_Title Slide", "2_..", إلخ). |

### قيمة الإرجاع

الشريحة المضافة.

## ملاحظات

1) تم إضافة تخطيط للقيمة [SlideLayoutType::Custom](../../slidelayouttype/) من *layoutType* ولا يحتوي على أي عناصر نائبة ولا أشكال. 2) نظير هذه الطريقة هو الطريقة [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) التي يمكن الوصول إليها عبر خاصية [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## انظر أيضًا

* تعداد [SlideLayoutType](../../slidelayouttype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [IMasterSlide](../../imasterslide/)
* فئة [String](../../../system/string/)
* فئة [IGlobalLayoutSlideCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)