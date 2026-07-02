---
title: TiffOptions
second_title: Aspose.Sildes untuk Referensi API .NET
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format TIFF.
type: docs
weight: 4550
url: /id/aspose.slides.export/tiffoptions/
---
## Kelas TiffOptions

Menyediakan opsi yang mengontrol bagaimana sebuah presentasi disimpan dalam format TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TiffOptions](tiffoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Menentukan algoritma untuk mengonversi gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika [`CompressionType`](./compressiontype) diatur ke CCITT4 atau CCITT3 Baca/tulis [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Default adalah Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Menentukan jenis kompresi. Baca/tulis [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Mengembalikan atau mengatur font yang digunakan jika font sumber tidak ditemukan. Baca-tulis String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Menentukan resolusi horizontal dalam dot per inci. Baca/tulis UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Menentukan resolusi vertikal dalam dot per inci. Baca/tulis UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Mengembalikan atau mengatur gaya visual gradien. Baca/tulis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Menentukan ukuran gambar TIFF yang dihasilkan. Nilai default adalah 0x0, yang berarti ukuran gambar yang dihasilkan akan dihitung berdasarkan nilai ukuran slide presentasi. Baca/tulis Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Baca-saja [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Menentukan format piksel untuk gambar yang dihasilkan. Baca/tulis [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Mewakili objek panggilan balik untuk pembaruan kemajuan penyimpanan dalam persentase. Lihat [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Menentukan apakah harus melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Baca/tulis Boolean. Nilai default adalah **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Mengambil atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau akan dibatalkan. Baca/tulis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Contoh

Contoh berikut menunjukkan cara mengonversi PowerPoint ke TIFF dengan ukuran default.

```csharp
[C#]
// Membuat objek Presentation yang mewakili file presentasi
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Menyimpan presentasi ke dokumen TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Contoh berikut menunjukkan cara mengonversi PowerPoint ke TIFF dengan ukuran khusus.

```csharp
[C#]
// Membuat objek Presentation yang mewakili file Presentasi
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Membuat objek kelas TiffOptions
    TiffOptions opts = new TiffOptions();
    // Mengatur jenis kompresi
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Jenis Kompresi
    // Default - Menentukan skema kompresi default (LZW).
    // None - Menentukan tidak ada kompresi.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Kedalaman tergantung pada jenis kompresi dan tidak dapat diatur secara manual.
    // Unit resolusi selalu sama dengan “2” (dot per inci)
    // Mengatur DPI gambar
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Mengatur Ukuran Gambar
    opts.ImageSize = new Size(1728, 1078);
    // Save the presentation to TIFF with specified image size
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Contoh berikut menunjukkan cara mengonversi PowerPoint ke TIFF dengan format piksel gambar khusus.

```csharp
[C#]
// Membuat objek Presentation yang mewakili file Presentasi
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat berisi nilai-nilai berikut (seperti dapat dilihat dari dokumentasi):
    Format1bppIndexed; // 1 bit per piksel, terindeks.
    Format4bppIndexed; // 4 bit per piksel, terindeks.
    Format8bppIndexed; // 8 bit per piksel, terindeks.
    Format24bppRgb; // 24 bit per piksel, RGB.
    Format32bppArgb; // 32 bit per piksel, ARGB.
    */
    // Simpan presentasi ke TIFF dengan ukuran gambar yang ditentukan
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Lihat Juga

* kelas [SaveOptions](../saveoptions)
* antarmuka [ITiffOptions](../itiffoptions)
* ruang nama [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->