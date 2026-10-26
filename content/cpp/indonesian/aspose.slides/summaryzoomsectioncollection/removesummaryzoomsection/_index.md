---
title: RemoveSummaryZoomSection()
second_title: Referensi API Aspose.Slides untuk C++
description: Hapus objek Summary Zoom Section dari koleksi.
type: docs
weight: 79
url: /id/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metode

Hapus objek Summary Zoom [Section](../../section/) dari koleksi.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) untuk mana elemen Summary Zoom [Section](../../section/) akan dihapus [ISection](../../isection/). |

## Keterangan



Contoh ini menunjukkan cara memperoleh elemen Summary Zoom [Section](../../section/) berdasarkan indeks:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISection](../../isection/)
* Kelas [SummaryZoomSectionCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)