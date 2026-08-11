---
title: AddSummaryZoomSection()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن Summary Zoom Section جديد ويضيفه إلى المجموعة
type: docs
weight: 53
url: /ar/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) طريقة

ينشئ كائن Summary Zoom [Section](../../section/) جديد ويضيفه إلى المجموعة

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) لجديد Summary Zoom [Section](../../section/) عنصر [ISection](../../isection/) |

### قيمة الإرجاع

تمت إضافة عنصر [ISummaryZoomFrame](../../isummaryzoomframe/)

## ملاحظات


إذا كان عنصر لهذا section موجود بالفعل في المجموعة، يتم إرجاع العنصر الموجود. 


يوضح المثال كيفية الحصول على عنصر Summary Zoom [Section](../../section/) حسب الفهرس: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISummaryZoomSection](../../isummaryzoomsection/)
* فئة [ISection](../../isection/)
* فئة [SummaryZoomSectionCollection](../)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)