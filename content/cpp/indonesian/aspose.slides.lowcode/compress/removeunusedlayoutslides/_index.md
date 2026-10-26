---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides untuk Referensi API C++
description: Melakukan kompresi Presentasi dengan menghapus slide tata letak yang tidak terpakai.
type: docs
weight: 14
url: /id/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) metode

Melakukan kompresi [Presentation](../../../aspose.slides/presentation/) dengan menghapus slide tata letak yang tidak digunakan.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Instance presentasi |
## Catatan

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Presentation](../../../aspose.slides/presentation/)
* Kelas [Compress](../)
* Ruang Nama [Aspose::Slides::LowCode](../../)
* Perpustakaan [Aspose.Slides](../../../)