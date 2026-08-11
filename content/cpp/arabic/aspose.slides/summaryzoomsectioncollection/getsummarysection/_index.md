---
title: GetSummarySection()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: يعيد عنصر قسم ملخص التكبير للقسم المحدد.
type: docs
weight: 92
url: /ar/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) طريقة

ترجع عنصر [Section](../../section/) ملخص التكبير للقسم المعطى.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```


### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) للعثور على [ISection](../../isection/) |

### قيمة الإرجاع

[ISummaryZoomSection](../../isummaryzoomsection/) أو null إذا لم تتضمن المجموعة عنصراً للقسم.

## ملاحظات



المثال يوضح الحصول على عنصر [Section](../../section/) ملخص التكبير حسب الفهرس: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISummaryZoomSection](../../isummaryzoomsection/)
* فئة [ISection](../../isection/)
* فئة [SummaryZoomSectionCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)