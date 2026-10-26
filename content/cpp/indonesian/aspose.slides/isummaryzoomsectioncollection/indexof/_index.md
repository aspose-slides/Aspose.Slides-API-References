---
title: IndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan indeks dari objek SummaryZoomSection yang ditentukan.
type: docs
weight: 53
url: /id/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metode


Mengembalikan indeks dari objek [SummaryZoomSection](../../summaryzoomsection/) yang ditentukan.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) objek untuk menemukan [ISummaryZoomSection](../../isummaryzoomsection/). |

### Nilai Kembalian

Indeks dari objek [SummaryZoomSection](../../summaryzoomsection/) atau -1 jika objek [SummaryZoomSection](../../summaryzoomsection/) tidak berasal dari koleksi ini.
## Catatan



Contoh ini menunjukkan cara mendapatkan elemen Summary Zoom [Section](../../section/) dengan indeks: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISummaryZoomSection](../../isummaryzoomsection/)
* Kelas [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)