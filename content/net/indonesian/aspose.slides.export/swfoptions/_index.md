---
title: SwfOptions
second_title: Aspose.Sildes untuk Referensi API .NET
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Swf.
type: docs
weight: 4530
url: /id/aspose.slides.export/swfoptions/
---
## SwfOptions kelas

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SwfOptions](swfoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Menentukan apakah dokumen SWF yang dihasilkan harus dikompresi atau tidak. Default adalah `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Mengembalikan atau mengatur font yang digunakan jika font sumber tidak ditemukan. String baca/tulis. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Aktifkan/nonaktifkan menu konteks. Default adalah true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Mengembalikan atau mengatur gaya visual gradasi. Baca/tulis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Menentukan kualitas gambar JPEG. Default adalah 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Gambar yang akan ditampilkan sebagai logo di pojok kanan atas viewer. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak benar. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Mengambil atau mengatur alamat hyperlink lengkap untuk logo. Hanya berpengaruh jika [`LogoImageBytes`](./logoimagebytes) ditentukan. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Mewakili objek callback untuk pembaruan kemajuan penyimpanan dalam persentase. Lihat [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Tampilkan/sembunyikan panel bawah. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Tampilkan/sembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Tampilkan/sembunyikan panel kiri. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Menentukan apakah batas di sekitar halaman harus ditampilkan. Default adalah true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Tampilkan/sembunyikan pengatur halaman. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Tampilkan/sembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Tampilkan/sembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Default adalah true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Menentukan apakah akan melewati hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Boolean baca/tulis. Nilai default adalah **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Mengambil atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](../islideslayoutoptions). Properti ini tidak mendukung penugasan objek tipe [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Default adalah false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan viewer dokumen terintegrasi atau tidak. Default adalah `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) baca/tulis. |

### Contoh

Contoh berikut menunjukkan cara mengonversi PowerPoint ke SWF Flash.

```csharp
[C#]
// Membuat objek Presentation yang mewakili file presentasi
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Menyimpan presentasi dan halaman catatan
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Lihat Juga

* kelas [SaveOptions](../saveoptions)
* antarmuka [ISwfOptions](../iswfoptions)
* ruang nama [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->