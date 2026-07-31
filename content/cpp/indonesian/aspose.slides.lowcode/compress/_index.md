---
title: Compress
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sekumpulan metode yang dimaksudkan untuk mengompresi Presentation.
type: docs
weight: 14
url: /id/aspose.slides.lowcode/compress/
---
## Compress kelas


Mewakili sekumpulan metode yang dimaksudkan untuk mengompresi [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Melakukan kompresi [Presentation](../../aspose.slides/presentation/) dengan menghapus karakter yang tidak terpakai dari font yang disematkan. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Melakukan kompresi [Presentation](../../aspose.slides/presentation/) dengan menghapus slide tata letak yang tidak terpakai. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Melakukan kompresi [Presentation](../../aspose.slides/presentation/) dengan menghapus master slide yang tidak terpakai. |
## Catatan


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Ruang nama [Aspose::Slides::LowCode](../)
* Pustaka [Aspose.Slides](../../)