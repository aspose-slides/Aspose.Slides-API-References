---
title: GetSummarySection()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bölüm için Summary Zoom Section öğesini döndürür.
type: docs
weight: 27
url: /tr/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) yöntemi

Belirtilen bölüm için Summary Zoom [Section](../../section/) öğesini döndürür.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) öğesini [ISection](../../isection/) bulmak için |

### Dönüş Değeri

[ISummaryZoomSection](../../isummaryzoomsection/) veya koleksiyon bölüm için öğe içermiyorsa null.

## Açıklamalar

Örnek, Summary Zoom [Section](../../section/) öğesini indeks ile almayı gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomSection](../../isummaryzoomsection/)
* Sınıf [ISection](../../isection/)
* Sınıf [ISummaryZoomSectionCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)