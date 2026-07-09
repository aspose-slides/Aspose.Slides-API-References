---
title: Convert
second_title: Aspose.Sildes untuk .NET Referensi API
description: Mewakili sekelompok metode yang dimaksudkan untuk mengonversi Presentation../aspose.slides/presentation.
type: docs
weight: 7880
url: /id/aspose.slides.lowcode/convert/
---
## Kelas Convert

Mewakili sekelompok metode yang dimaksudkan untuk mengonversi [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menggunakan ekstensi jalur output yang diberikan untuk menentukan format ekspor yang diperlukan. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG. Jika nama berkas output diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG. Jika nama berkas output diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG. Jika nama berkas output diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menjadi PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menjadi PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menjadi PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menjadi PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Mengonversi presentasi input menjadi sekumpulan gambar berformat PNG. Jika nama berkas output diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.png", di mana N adalah nomor slide. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Mengonversi presentasi input menjadi sekumpulan gambar berformat PNG. Jika nama berkas output diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.png", di mana N adalah nomor slide. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Mengonversi presentasi input menjadi sekumpulan gambar berformat PNG. Jika nama berkas output diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.png", di mana N adalah nomor slide. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menjadi SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menjadi SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menjadi SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menjadi SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Mengonversi [`Presentation`](../../aspose.slides/presentation) menjadi SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Mengonversi presentasi input menjadi sekumpulan gambar berformat TIFF. Jika nama berkas output diberikan sebagai "myPath/myFilename.tiff", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.tiff", di mana N adalah nomor slide. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Mengonversi presentasi input ke format TIFF dengan opsi khusus. Jika nama berkas output diberikan sebagai "myPath/myFilename.tiff" dan *multipage* bernilai `false`, hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.tiff", di mana N adalah nomor slide. Jika *multipage* bernilai `true`, hasilnya akan menjadi dokumen "myPath/myFilename.tiff" multi-halaman. |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Callback yang akan dipanggil untuk setiap [`Slide`](../../aspose.slides/slide), jalur output diharapkan dikembalikan. |

### Contoh

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Lihat Juga

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->