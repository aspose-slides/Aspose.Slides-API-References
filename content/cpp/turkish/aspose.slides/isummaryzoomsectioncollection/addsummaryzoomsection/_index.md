---
title: AddSummaryZoomSection()
second_title: C++ için Aspose.Slides API Referansı
description: Yeni bir Summary Zoom Section nesnesi oluşturur ve koleksiyona ekler
type: docs
weight: 14
url: /tr/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metodu

Yeni bir Summary Zoom [Section](../../section/) nesnesi oluşturur ve koleksiyona ekler

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) yeni bir Summary Zoom [Section](../../section/) öğesi [ISection](../../isection/) için |

### Dönüş Değeri

Eklenen [ISummaryZoomFrame](../../isummaryzoomframe/) öğesi

## Açıklamalar

Eğer bu bölüm için koleksiyonda zaten bir öğe varsa, mevcut öğe döndürülür. 

Örnek, Summary Zoom [Section](../../section/) öğesini dizine göre almayı göstermektedir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Diğer Bağlantılar

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomSection](../../isummaryzoomsection/)
* Sınıf [ISection](../../isection/)
* Sınıf [ISummaryZoomSectionCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)