---
title: AddSummaryZoomSection()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek Summary Zoom Section baru dan menambahkannya ke koleksi
type: docs
weight: 53
url: /id/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metode

Membuat objek Summary Zoom [Section](../../section/) baru dan menambahkannya ke koleksi

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) untuk elemen Summary Zoom [Section](../../section/) baru [ISection](../../isection/) |

### Nilai Kembali

Elemen [ISummaryZoomFrame](../../isummaryzoomframe/) ditambahkan

## Catatan

Jika elemen untuk bagian ini sudah ada di dalam koleksi, elemen yang ada akan dikembalikan.

Contoh ini menunjukkan cara mendapatkan elemen Summary Zoom [Section](../../section/) berdasarkan indeks:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISummaryZoomSection](../../isummaryzoomsection/)
* Kelas [ISection](../../isection/)
* Kelas [SummaryZoomSectionCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)