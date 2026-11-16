---
title: SwfOptions
second_title: Aspose.Sildes untuk Referensi API .NET
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format Swf.
type: docs
weight: 4550
url: /id/aspose.slides.export/swfoptions/
---
## Kelas SwfOptions

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
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Mengembalikan atau mengatur font yang digunakan bila font sumber tidak ditemukan. Baca-tulis String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Mengaktifkan/menonaktifkan menu konteks. Default adalah true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Mengembalikan atau mengatur gaya visual gradien. Baca/tulis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Menentukan kualitas gambar JPEG. Default adalah 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Gambar yang akan ditampilkan sebagai logo di sudut kanan atas viewer. Gambar harus berukuran 32x64 piksel PNG, jika tidak logo dapat ditampilkan tidak semestinya. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Mengambil atau mengatur alamat hyperlink lengkap untuk logo. Berpengaruh hanya bila [`LogoImageBytes`](./logoimagebytes) ditentukan. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Mewakili objek callback untuk pembaruan kemajuan penyimpanan dalam persentase. Lihat [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Menampilkan/menyembunyikan panel bawah. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Menampilkan/menyembunyikan tombol layar penuh. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Menampilkan/menyembunyikan panel kiri. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Menentukan apakah batas di sekitar halaman harus ditampilkan. Default adalah true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Menampilkan/menyembunyikan pager stepper. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Menampilkan/menyembunyikan bagian pencarian. Dapat ditimpa dalam flashvars. Default adalah true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Menampilkan/menyembunyikan seluruh panel atas. Dapat ditimpa dalam flashvars. Default adalah true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Baca/tulis Boolean. Nilai default adalah **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Mengambil atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](../islideslayoutoptions). Properti ini tidak mendukung penetapan objek bertipe [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Mulai dengan panel kiri terbuka. Dapat ditimpa dalam flashvars. Default adalah false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Menentukan apakah dokumen SWF yang dihasilkan harus menyertakan penampil dokumen terintegrasi atau tidak. Default adalah `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca/tulis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

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
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->