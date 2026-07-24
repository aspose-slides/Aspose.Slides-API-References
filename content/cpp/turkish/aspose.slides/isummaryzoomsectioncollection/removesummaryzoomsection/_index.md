---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondan Özet Yakınlaştırma Bölüm nesnesini kaldır.
type: docs
weight: 40
url: /tr/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) method


Koleksiyondan Özet Yakınlaştırma [Section](../../section/) nesnesini kaldır.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) için Özet Yakınlaştırma [Section](../../section/) öğesinin kaldırılması [ISection](../../isection/). |
## Açıklamalar



Bu örnek, indeksle Özet Yakınlaştırma [Section](../../section/) öğesinin alınmasını gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)