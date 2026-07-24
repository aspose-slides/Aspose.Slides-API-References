---
title: AddSummaryZoomSection()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni Summary Zoom Section nesnesi oluşturur ve koleksiyona ekler
type: docs
weight: 53
url: /tr/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metodu


Yeni Summary Zoom [Section](../../section/) nesnesi oluşturur ve koleksiyona ekler

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) yeni bir Summary Zoom [Section](../../section/) öğesi [ISection](../../isection/) |

### Dönüş Değeri

Eklenen [ISummaryZoomFrame](../../isummaryzoomframe/) öğe
## Açıklamalar



Eğer bu bölüm için koleksiyonda zaten bir öğe varsa, mevcut öğe döndürülür. 


Örnek, indeks ile Summary Zoom [Section](../../section/) öğesini almayı gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomSection](../../isummaryzoomsection/)
* Sınıf [ISection](../../isection/)
* Sınıf [SummaryZoomSectionCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)