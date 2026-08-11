---
title: GetSummarySection()
second_title: مرجع API Aspose.Slides للغة C++
description: تُرجِع عنصر قسم ملخص التكبير للقطاع المحدد.
type: docs
weight: 27
url: /ar/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) طريقة

تُعيد عنصر ملخص التكبير [Section](../../section/) للقسم المحدد.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) للعثور على [ISection](../../isection/) |

### قيمة الإرجاع

[ISummaryZoomSection](../../isummaryzoomsection/) أو null إذا لم تحتوي المجموعة على عنصر للقسم.

## ملاحظات

يوضح المثال الحصول على عنصر ملخص التكبير [Section](../../section/) بواسطة الفهرس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [ISummaryZoomSection](../../isummaryzoomsection/)
* الفئة [ISection](../../isection/)
* الفئة [ISummaryZoomSectionCollection](../)
* النطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)