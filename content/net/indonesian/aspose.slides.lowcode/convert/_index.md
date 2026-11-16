---
title: Convert
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili sekumpulan metode yang ditujukan untuk mengonversi Presentation../aspose.slides/presentation.
type: docs
weight: 7900
url: /id/aspose.slides.lowcode/convert/
---
## Kelas Convert

Mewakili sekumpulan metode yang ditujukan untuk mengonversi [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menggunakan ekstensi jalur output yang diberikan untuk menentukan format ekspor yang diperlukan. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Mengonversi presentasi input menjadi sekumpulan gambar format JPEG. Jika nama file output diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.jpeg", dimana N adalah nomor slide. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Mengonversi presentasi input menjadi sekumpulan gambar format JPEG. Jika nama file output diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.jpeg", dimana N adalah nomor slide. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Mengonversi presentasi input menjadi sekumpulan gambar format JPEG. Jika nama file output diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.jpeg", dimana N adalah nomor slide. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Mengonversi [`Presentation`](../../aspose.slides/presentation) ke PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Mengonversi [`Presentation`](../../aspose.slides/presentation) ke PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Mengonversi [`Presentation`](../../aspose.slides/presentation) ke PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Mengonversi [`Presentation`](../../aspose.slides/presentation) ke PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Mengonversi presentasi input menjadi sekumpulan gambar format PNG. Jika nama file output diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.png", dimana N adalah nomor slide. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Mengonversi presentasi input menjadi sekumpulan gambar format PNG. Jika nama file output diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.png", dimana N adalah nomor slide. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Mengonversi presentasi input menjadi sekumpulan gambar format PNG. Jika nama file output diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.png", dimana N adalah nomor slide. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Mengonversi [`Presentation`](../../aspose.slides/presentation) ke SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Mengonversi [`Presentation`](../../aspose.slides/presentation) ke SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Mengonversi [`Presentation`](../../aspose.slides/presentation) ke SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Mengonversi [`Presentation`](../../aspose.slides/presentation) ke SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Mengonversi [`Presentation`](../../aspose.slides/presentation) ke SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Mengonversi presentasi input menjadi sekumpulan gambar format TIFF. Jika nama file output diberikan sebagai "myPath/myFilename.tiff", hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.tiff", dimana N adalah nomor slide. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Mengonversi presentasi input ke format TIFF dengan opsi khusus. Jika nama file output diberikan sebagai "myPath/myFilename.tiff" dan *multipage* adalah `false`, hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.tiff", dimana N adalah nomor slide. Jika *multipage* adalah `true`, hasilnya akan menjadi dokumen multi-halaman "myPath/myFilename.tiff". |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Callback yang akan dipanggil untuk setiap [`Slide`](../../aspose.slides/slide), jalur output diharapkan dikembalikan. |

### Contoh

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Lihat Juga

* ruang nama [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->