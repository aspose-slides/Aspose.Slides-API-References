---
title: WriteAsEmf()
second_title: Aspose.Slides untuk Referensi API C++
description: Menyimpan gambar SVG sebagai file EMF.
type: docs
weight: 53
url: /id/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metode

Menyimpan gambar SVG sebagai file EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Target stream |
## Keterangan

Contoh berikut menunjukkan cara menyimpan gambar SVG ke dalam metafile. 
```cpp
// Membuat gambar SVG baru
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Menyimpan gambar SVG sebagai metafile
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Contoh ini menunjukkan cara menambahkan gambar SVG sebagai metafile ke dalam koleksi gambar presentasi. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Membuat gambar SVG baru
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Menyimpan gambar SVG sebagai metafile
svgImage->WriteAsEmf(memStream);
// Menambahkan metafile ke koleksi gambar
pres->get_Images()->AddImage(memStream->ToArray());
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [ISvgImage](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)