---
title: GetSummarySection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan elemen Summary Zoom Section untuk bagian yang diberikan.
type: docs
weight: 27
url: /id/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) method


Mengembalikan elemen Summary Zoom [Section](../../section/) untuk bagian yang diberikan.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) untuk menemukan [ISection](../../isection/) |

### Nilai Kembali

[ISummaryZoomSection](../../isummaryzoomsection/) atau null jika koleksi tidak berisi elemen untuk bagian tersebut.
## Catatan



Contoh ini menunjukkan cara mendapatkan elemen Summary Zoom [Section](../../section/) berdasarkan indeks: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISummaryZoomSection](../../isummaryzoomsection/)
* Kelas [ISection](../../isection/)
* Kelas [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)