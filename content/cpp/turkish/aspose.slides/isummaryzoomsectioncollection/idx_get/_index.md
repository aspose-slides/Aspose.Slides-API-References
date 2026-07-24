---
title: idx_get()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen indeksteki öğeyi alır. Salt okunur ISummaryZoomSection.
type: docs
weight: 1
url: /tr/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) method


Belirtilen indeksteki öğeyi alır. Salt okunur [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## Açıklamalar


Örnek, Summary Zoom [Section](../../section/) öğesini indeksle almayı göstermektedir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## İlgili

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomSection](../../isummaryzoomsection/)
* Sınıf [ISummaryZoomSectionCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)