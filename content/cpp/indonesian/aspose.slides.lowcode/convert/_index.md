---
title: Convert
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sekelompok metode yang dimaksudkan untuk mengkonversi Presentation.
type: docs
weight: 27
url: /id/aspose.slides.lowcode/convert/
---
## Convert kelas

Mewakili sekelompok metode yang dimaksudkan untuk mengkonversi [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Mengkonversi [Presentation](../../aspose.slides/presentation/) menggunakan ekstensi jalur keluaran yang diberikan untuk menentukan format ekspor yang diperlukan. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Mengkonversi presentasi input menjadi sekumpulan gambar berformat JPEG. 

 Jika nama berkas keluaran diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Mengkonversi presentasi input menjadi sekumpulan gambar berformat JPEG. 

 Jika nama berkas keluaran diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Mengkonversi presentasi input menjadi sekumpulan gambar berformat JPEG. 

 Jika nama berkas keluaran diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Mengkonversi [Presentation](../../aspose.slides/presentation/) ke PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Mengkonversi [Presentation](../../aspose.slides/presentation/) ke PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Mengkonversi [Presentation](../../aspose.slides/presentation/) ke PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Mengkonversi [Presentation](../../aspose.slides/presentation/) ke PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Mengkonversi presentasi input menjadi sekumpulan gambar berformat PNG. 

 Jika nama berkas keluaran diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.png", di mana N adalah nomor slide. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Mengkonversi presentasi input menjadi sekumpulan gambar berformat PNG. 

 Jika nama berkas keluaran diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.png", di mana N adalah nomor slide. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Mengkonversi presentasi input menjadi sekumpulan gambar berformat PNG. 

 Jika nama berkas keluaran diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.png", di mana N adalah nomor slide. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Mengkonversi [Presentation](../../aspose.slides/presentation/) ke SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Mengkonversi [Presentation](../../aspose.slides/presentation/) ke SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Mengkonversi [Presentation](../../aspose.slides/presentation/) ke SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Mengkonversi [Presentation](../../aspose.slides/presentation/) ke SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Mengkonversi [Presentation](../../aspose.slides/presentation/) ke SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Mengkonversi presentasi input menjadi sekumpulan gambar berformat TIFF. 

 Jika nama berkas keluaran diberikan sebagai "myPath/myFilename.tiff", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.tiff", di mana N adalah nomor slide. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Mengkonversi presentasi input ke format TIFF dengan opsi khusus. Jika nama berkas keluaran diberikan sebagai "myPath/myFilename.tiff" dan *multipage*  adalah **false**, hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.tiff", di mana N adalah nomor slide. Jika tidak, jika *multipage*  adalah **true**, hasilnya akan menjadi dokumen multi-halaman "myPath/myFilename.tiff". |

## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Callback yang akan dipanggil untuk setiap [Slide](../../aspose.slides/slide/), jalur keluaran diharapkan dikembalikan. |

## Catatan



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Lihat Juga

* Namespace [Aspose::Slides::LowCode](../)
* Perpustakaan [Aspose.Slides](../../)