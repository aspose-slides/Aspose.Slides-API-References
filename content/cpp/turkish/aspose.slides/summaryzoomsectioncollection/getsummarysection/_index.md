---
title: GetSummarySection()
second_title: Aspose.Slides için C++ API Referansı
description: Verilen bölüm için Summary Zoom Section öğesini döndürür.
type: docs
weight: 92
url: /tr/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metot

Verilen bölüm için Summary Zoom [Section](../../section/) öğesini döndürür.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) bulmak için [ISection](../../isection/) |

### Dönüş Değeri

[ISummaryZoomSection](../../isummaryzoomsection/) veya koleksiyon bölüm için öğe içermiyorsa null.

## Açıklamalar

Örnek, Summary Zoom [Section](../../section/) öğesini indeksle almayı gösterir:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## İlgili Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomSection](../../isummaryzoomsection/)
* Sınıf [ISection](../../isection/)
* Sınıf [SummaryZoomSectionCollection](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)