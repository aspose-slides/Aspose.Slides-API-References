---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides için C++ API Referansı
description: Koleksiyondan Summary Zoom Section nesnesini kaldırın.
type: docs
weight: 79
url: /tr/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metot

Koleksiyondan Summary Zoom [Section](../../section/) nesnesini kaldırın.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) için Summary Zoom [Section](../../section/) öğesinin [ISection](../../isection/) kaldırılması gerekir. |

## Açıklamalar

Örnek, Summary Zoom [Section](../../section/) öğesini dizinle almayı göstermektedir:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISection](../../isection/)
* Sınıf [SummaryZoomSectionCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)