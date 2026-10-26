---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++ المرجعية
description: إزالة كائن Summary Zoom Section من المجموعة.
type: docs
weight: 79
url: /ar/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) طريقة

إزالة كائن Summary Zoom [Section](../../section/) من المجموعة.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) التي يجب إزالة عنصر Summary Zoom [Section](../../section/) [ISection](../../isection/) منها. |

## ملاحظات

يوضح المثال الحصول على عنصر Summary Zoom [Section](../../section/) حسب الفهرس:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISection](../../isection/)
* فئة [SummaryZoomSectionCollection](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)