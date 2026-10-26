---
title: IndexOf()
second_title: Aspose.Slides لـ C++ مرجع API
description: تُرجِع فهرسًا للعنصر SummaryZoomSection المحدد.
type: docs
weight: 53
url: /ar/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) طريقة

تُعيد فهرسًا للعنصر [SummaryZoomSection](../../summaryzoomsection/) المحدد.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) عنصر للعثور على [ISummaryZoomSection](../../isummaryzoomsection/). |

### قيمة الإرجاع

فهرس عنصر [SummaryZoomSection](../../summaryzoomsection/) أو -1 إذا كان عنصر [SummaryZoomSection](../../summaryzoomsection/) ليس من هذه المجموعة.

## ملاحظات

يوضح المثال كيفية الحصول على عنصر Summary Zoom [Section](../../section/) باستخدام الفهرس:
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
* فئة [ISummaryZoomSectionCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)