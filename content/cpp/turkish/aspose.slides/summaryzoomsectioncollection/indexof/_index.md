---
title: IndexOf()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen SummaryZoomSection nesnesinin dizinini döndürür.
type: docs
weight: 66
url: /tr/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) method

Belirtilen [SummaryZoomSection](../../summaryzoomsection/) nesnesinin dizinini döndürür.

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) nesnesi [ISummaryZoomSection](../../isummaryzoomsection/) bulmak için. |

### Dönüş Değeri

[SummaryZoomSection](../../summaryzoomsection/) nesnesinin dizini ya da koleksiyona ait olmayan [SummaryZoomSection](../../summaryzoomsection/) nesnesi için -1.

## Açıklamalar

Örnek, Summary Zoom [Section](../../section/) öğesini dizinle almayı gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomSection](../../isummaryzoomsection/)
* Sınıf [SummaryZoomSectionCollection](../)
* İsim Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)