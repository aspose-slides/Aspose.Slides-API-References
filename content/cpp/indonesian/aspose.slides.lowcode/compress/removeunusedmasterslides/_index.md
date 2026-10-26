---
title: RemoveUnusedMasterSlides()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan kompresi Presentation dengan menghapus master slide yang tidak terpakai.
type: docs
weight: 1
url: /id/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) metode

Melakukan kompresi [Presentation](../../../aspose.slides/presentation/) dengan menghapus master slide yang tidak terpakai.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Instansi presentasi |
## Catatan

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Presentation](../../../aspose.slides/presentation/)
* Kelas [Compress](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Perpustakaan [Aspose.Slides](../../../)