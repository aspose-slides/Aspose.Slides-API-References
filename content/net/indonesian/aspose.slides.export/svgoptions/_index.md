---
title: SVGOptions
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili opsi SVG.
type: docs
weight: 4410
url: /id/aspose.slides.export/svgoptions/
---
## Kelas SVGOptions

Mewakili opsi SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Menginisialisasi instance baru dari kelas SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Menginisialisasi instance baru dari kelas SVGOptions dengan menentukan objek kontroler penanaman tautan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Mengembalikan pengaturan default. Hanya-baca [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Mengembalikan pengaturan untuk pembuatan file SVG yang paling sederhana dan terkecil. Hanya-baca [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Mengembalikan pengaturan untuk pembuatan file SVG yang paling akurat. Hanya-baca [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Mengembalikan atau mengatur font yang digunakan jika font sumber tidak ditemukan. Baca-tulis String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Bendera boolean yang menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. Jika true bagian yang dipotong akan dihapus, jika false mereka akan diserialkan dalam dokumen (yang dapat menyebabkan ukuran file lebih besar). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Menentukan apakah teks 3D dinonaktifkan dalam SVG. Baca-tulis Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Mengambil atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke `true`, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Menonaktifkan pemisahan gradien FromCornerX dan FromCenter. Baca-tulis Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda. Mesin penulisan SVG Aspose.Slides memiliki solusi untuk masalah tersebut: memotong ujung garis dengan panah, sehingga garis tidak tumpang tindih dengan penanda. Opsi ini mematikan perilaku tersebut. Baca-tulis Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Menentukan cara penanganan font yang dimuat secara eksternal. Baca-tulis [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Mengembalikan atau mengatur gaya visual gradien. Baca-tulis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Hanya-baca [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Menentukan kualitas enkoding JPEG. Baca-tulis Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Mengembalikan atau mengatur batas resolusi rendah untuk rasterisasi metafile. Baca-tulis Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Mewakili tingkat kompresi gambar |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Mewakili objek callback untuk pembaruan kemajuan penyimpanan dalam persentase. Lihat [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Mengembalikan dan mengatur antarmuka callback yang memungkinkan pengguna mengontrol konversi bentuk. Baca-tulis [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Baca-tulis Boolean. Nilai defaultnya adalah **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat merender atau tidak. Baca-tulis Boolean. Nilai defaultnya adalah true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Menentukan apakah bingkai teks akan disertakan dalam area render atau tidak. Baca-tulis Boolean. Nilai defaultnya adalah false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Menentukan apakah teks pada slide akan disimpan sebagai grafik. Baca-tulis Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca-tulis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Lihat Juga

* kelas [SaveOptions](../saveoptions)
* antarmuka [ISVGOptions](../isvgoptions)
* ruang nama [Aspose.Slides.Export](../../aspose.slides.export)
* perakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->