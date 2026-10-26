---
title: GetSummarySection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan elemen Summary Zoom Section untuk section yang diberikan.
type: docs
weight: 92
url: /id/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metode

Mengembalikan elemen Summary Zoom [Section](../../section/) untuk section yang diberikan.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) untuk menemukan [ISection](../../isection/) |

### Nilai Kembalian

[ISummaryZoomSection](../../isummaryzoomsection/) atau null jika koleksi tidak berisi elemen untuk section.

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
* Kelas [SummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)