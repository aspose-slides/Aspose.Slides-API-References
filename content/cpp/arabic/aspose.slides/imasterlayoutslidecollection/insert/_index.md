---
title: Insert()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يدخل شريحة تخطيط جديدة في الموضع المحدد ضمن المجموعة.
type: docs
weight: 40
url: /ar/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) طريقة

يدخل شريحة تخطيط جديدة في الموضع المحدد في المجموعة.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | نوع التخطيط لتخطيط جديد. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. أنواع التخطيط الأخرى غير مدعومة حالياً: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | اسم لتخطيط جديد. إذا كان الاسم الممرّر مستخدماً مسبقاً سيتم رمي ArgumentException. إذا تم تمرير معلمة فارغة (null) فإن الاسم يتم توليده تلقائياً وفقاً لنوع التخطيط الممرّر (مثال "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

### قيمة الإرجاع

شريحة مُدخلة.

## ملاحظات

التخطيط المُدرج للقيمة [SlideLayoutType::Custom](../../slidelayouttype/) من *layoutType* لا يحتوي على نائبات ولا أشكال. 

## انظر أيضاً

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [String](../../../system/string/)
* فئة [IMasterLayoutSlideCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)