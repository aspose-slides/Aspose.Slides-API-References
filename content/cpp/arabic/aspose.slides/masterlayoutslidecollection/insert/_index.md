---
title: Insert()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يدرج شريحة تخطيط جديدة في الموضع المحدد من المجموعة.
type: docs
weight: 40
url: /ar/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) الطريقة

يدرج شريحة تخطيط جديدة في الموضع المحدد من المجموعة.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | Index of new slide. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example \"Title Slide\" or \"1_Title Slide\", \"2_..\", etc.). |

### قيمة الإرجاع

الشريحة المدخلة.

## ملاحظات

تم إدراج تخطيط للقيمة [SlideLayoutType::Custom](../../slidelayouttype/) من *layoutType* لا يحتوي على placeholders ولا على أشكال. 

## انظر أيضًا

* تعداد [SlideLayoutType](../../slidelayouttype/)
* تعريف_نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [String](../../../system/string/)
* فئة [MasterLayoutSlideCollection](../)
* مساحة_اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)