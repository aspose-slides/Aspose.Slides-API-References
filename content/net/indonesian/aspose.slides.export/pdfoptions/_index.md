---
title: PdfOptions
second_title: Referensi API Aspose.Sildes untuk .NET
description: Menyediakan opsi yang mengontrol bagaimana sebuah presentasi disimpan dalam format Pdf.
type: docs
weight: 4350
url: /id/aspose.slides.export/pdfoptions/
---
## kelas PdfOptions

Menyediakan opsi yang mengontrol bagaimana sebuah presentasi disimpan dalam format Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfOptions](pdfoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka dengan akses pengguna. Lihat [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Mengembalikan atau mengatur array nama keluarga font yang didefinisikan pengguna yang harus dianggap umum oleh Aspose.Slides. Baca/tulis String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Menerapkan warna transparan yang ditentukan pada gambar jika `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. Jika diatur ke Boolean.true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran PDF yang lebih kecil. Pemilihan rasio kompresi gambar terbaik memerlukan komputasi yang mahal dan memakan RAM tambahan, dan opsi ini bernilai Boolean.false secara default. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. Baca/tulis [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Mengembalikan atau mengatur font yang digunakan bila font sumber tidak ditemukan. Baca/tulis String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True untuk menggambar bingkai hitam di sekitar setiap slide. Baca/tulis Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. Baca/tulis Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Menentukan apakah Aspose.Slides akan menyematkan font umum untuk teks ASCII (rentang kode 33..127). Font untuk kode karakter lebih dari 127 selalu disematkan. Daftar font umum mencakup 14 font dasar PDF dan font tambahan yang ditentukan pengguna. Baca/tulis Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Mengembalikan atau mengatur gaya visual dari gradien. Baca/tulis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Mengambil atau mengatur warna transparan gambar. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True untuk mengonversi semua data OLE dari presentasi menjadi berkas tersemat dalam PDF yang dihasilkan. Baca/tulis Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Baca-saja [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. Baca/tulis Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Mengatur kata sandi pengguna untuk melindungi dokumen PDF. Baca/tulis String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Mewakili objek callback untuk pembaruan kemajuan penyimpanan dalam persentase. Lihat [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Menunjukkan apakah teks harus dirasterkan sebagai bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu. Baca/tulis Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca/tulis Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Nilai default adalah `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Menentukan apakah hyperlink dengan panggilan JavaScript harus dilewati saat menyimpan presentasi. Baca/tulis Boolean. Nilai default adalah **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Mengambil atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Mengembalikan atau mengatur nilai yang menentukan resolusi gambar dalam dokumen PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. Baca/tulis [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dihentikan. Baca/tulis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Contoh

Contoh berikut menunjukkan cara mengonversi PowerPoint ke PDF dengan opsi khusus.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Menginstansiasi kelas PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Menetapkan kualitas Jpeg
	pdfOptions.JpegQuality = 90;
	// Menetapkan perilaku untuk metafile
	pdfOptions.SaveMetafilesAsPng = true;
	// Menetapkan tingkat kompresi teks
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Mendefinisikan standar PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Menyimpan presentasi sebagai PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Contoh berikut menunjukkan cara mengonversi PowerPoint ke PDF dengan slide tersembunyi.

```csharp
[C#]
// Menginstansiasi kelas Presentation yang mewakili file PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Menginstansiasi kelas PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Menambahkan slide tersembunyi
	pdfOptions.ShowHiddenSlides = true;
	// Menyimpan presentasi sebagai PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Contoh berikut menunjukkan cara mengonversi PowerPoint ke PDF yang dilindungi kata sandi.

```csharp
[C#]
// Menginstansiasi objek Presentation yang mewakili file PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Menginstansiasi kelas PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Menetapkan kata sandi PDF dan izin akses
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Menyimpan presentasi sebagai PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Contoh berikut menunjukkan cara mengonversi PowerPoint ke PDF dengan catatan.

```csharp
[C#]
// Menginstansiasi objek Presentation yang mewakili file presentasi
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Mengatur Tipe dan Ukuran Slide
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Lihat Juga

* kelas [SaveOptions](../saveoptions)
* antarmuka [IPdfOptions](../ipdfoptions)
* ruang nama [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->