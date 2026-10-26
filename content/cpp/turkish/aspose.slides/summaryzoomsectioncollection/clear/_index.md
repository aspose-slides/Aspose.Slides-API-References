---
title: Clear()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondaki tüm SummaryZoomSection nesnelerini kaldırır.
type: docs
weight: 105
url: /tr/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() metot

Koleksiyondaki tüm [SummaryZoomSection](../../summaryzoomsection/) nesnelerini kaldırır.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Açıklamalar

Örnek, Summary Zoom [Section](../../section/) öğesini indeksle elde etmeyi gösterir:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## İlgili

* Sınıf [SummaryZoomSectionCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)