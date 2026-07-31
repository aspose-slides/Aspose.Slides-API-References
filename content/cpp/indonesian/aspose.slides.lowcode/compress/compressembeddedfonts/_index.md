---
title: CompressEmbeddedFonts()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan kompresi Presentasi dengan menghapus karakter yang tidak terpakai dari font yang disematkan.
type: docs
weight: 27
url: /id/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) metode

Melakukan kompresi [Presentation](../../../aspose.slides/presentation/) dengan menghapus karakter yang tidak terpakai dari font yang disematkan.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Instance presentasi |

## Catatan

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Presentation](../../../aspose.slides/presentation/)
* Kelas [Compress](../)
* Ruang Nama [Aspose::Slides::LowCode](../../)
* Perpustakaan [Aspose.Slides](../../../)