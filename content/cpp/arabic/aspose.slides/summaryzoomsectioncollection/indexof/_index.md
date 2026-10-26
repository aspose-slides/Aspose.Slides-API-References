---
title: IndexOf()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع فهرسًا للكائن SummaryZoomSection المحدد.
type: docs
weight: 66
url: /ar/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) طريقة

يرجع فهرسًا للكائن [SummaryZoomSection](../../summaryzoomsection/) المحدد.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) كائن للعثور على [ISummaryZoomSection](../../isummaryzoomsection/). |

### قيمة الإرجاع

فهرس كائن [SummaryZoomSection](../../summaryzoomsection/) أو -1 إذا كان كائن [SummaryZoomSection](../../summaryzoomsection/) ليس من هذه المجموعة.

## ملاحظات

يوضح المثال الحصول على عنصر Summary Zoom [Section](../../section/) حسب الفهرس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISummaryZoomSection](../../isummaryzoomsection/)
* فئة [SummaryZoomSectionCollection](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)