---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: إزالة كائن Summary Zoom Section من المجموعة.
type: docs
weight: 40
url: /ar/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) طريقة

إزالة كائن Summary Zoom [Section](../../section/) من المجموعة.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) الذي يتم حذف عنصر Summary Zoom [Section](../../section/) منه [ISection](../../isection/). |

## ملاحظات



يوضح المثال طريقة الحصول على عنصر Summary Zoom [Section](../../section/) عبر الفهرس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISection](../../isection/)
* فئة [ISummaryZoomSectionCollection](../)
* مساحة أسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)