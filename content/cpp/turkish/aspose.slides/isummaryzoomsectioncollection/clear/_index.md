---
title: Clear()
second_title: Aspose.Slides C++ API Referansı
description: Koleksiyondaki tüm SummaryZoomSection nesnelerini kaldırır.
type: docs
weight: 66
url: /tr/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() yöntemi


Koleksiyondaki tüm [SummaryZoomSection](../../summaryzoomsection/) nesnelerini kaldırır.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## Açıklamalar


Örnek, Summary Zoom [Section](../../section/) öğesini dizine göre almayı gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Bakınız

* Sınıf [ISummaryZoomSectionCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)