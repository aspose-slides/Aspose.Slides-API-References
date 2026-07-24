---
title: IndexOf()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen SummaryZoomSection nesnesinin bir dizinini döndürür.
type: docs
weight: 53
url: /tr/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metodu


Belirtilen [SummaryZoomSection](../../summaryzoomsection/) nesnesinin bir dizinini döndürür.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) nesnesi [ISummaryZoomSection](../../isummaryzoomsection/) bulmak için. |

### Dönüş Değeri

[SummaryZoomSection](../../summaryzoomsection/) nesnesinin dizini veya bu koleksiyondan olmayan [SummaryZoomSection](../../summaryzoomsection/) nesnesi için -1.

## Açıklamalar



Örnek, Summary Zoom [Section](../../section/) öğesini dizine göre almayı göstermektedir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomSection](../../isummaryzoomsection/)
* Sınıf [ISummaryZoomSectionCollection](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)