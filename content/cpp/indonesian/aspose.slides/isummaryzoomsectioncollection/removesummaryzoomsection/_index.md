---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides untuk Referensi API C++
description: Hapus objek Summary Zoom Section dari koleksi.
type: docs
weight: 40
url: /id/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) method


Hapus objek Summary Zoom [Section](../../section/) dari koleksi.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) untuk mana elemen Summary Zoom [Section](../../section/) akan dihapus [ISection](../../isection/). |
## Catatan



Contoh ini menunjukkan cara mendapatkan elemen Summary Zoom [Section](../../section/) berdasarkan indeks: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)