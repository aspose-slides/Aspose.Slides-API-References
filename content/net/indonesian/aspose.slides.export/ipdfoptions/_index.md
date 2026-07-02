---
title: IPdfOptions
second_title: Aspose.Sildes untuk Referensi API .NET
description: Menyediakan opsi yang mengontrol cara presentasi disimpan dalam format Pdf.
type: docs
weight: 3980
url: /id/aspose.slides.export/ipdfoptions/
---
## Antarmuka IPdfOptions

Menyediakan opsi yang mengontrol cara presentasi disimpan dalam format Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Properti

| Name | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna. Lihat [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Mengembalikan atau menetapkan array nama keluarga font yang ditentukan pengguna yang harus dianggap umum oleh Aspose.Slides. Baca/tulis String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Menerapkan warna transparan yang ditentukan pada gambar jika `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Mengembalikan antarmuka ISaveOptions. Baca-saja [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Menunjukkan apakah kompresi paling efektif (bukan yang default) untuk setiap gambar harus dipilih secara otomatis. Jika disetel ke Boolean.true, untuk setiap gambar dalam presentasi algoritma kompresi yang paling tepat akan dipilih, yang akan menghasilkan ukuran dokumen PDF yang lebih kecil. Pemilihan rasio kompresi gambar terbaik membutuhkan banyak komputasi dan memori tambahan, dan opsi ini secara default adalah Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Tingkat kepatuhan yang diinginkan untuk dokumen PDF yang dihasilkan. Baca/tulis [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True untuk menggambar bingkai hitam di sekitar setiap slide. Baca/tulis Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Menentukan apakah semua karakter font harus disematkan atau hanya subset yang digunakan. Baca/tulis Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True untuk menyematkan font TrueType untuk karakter ASCII 32-127. Font untuk kode karakter lebih dari 127 selalu disematkan. Baca/tulis Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Mengambil atau menetapkan warna transparan gambar. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True untuk mengonversi semua data OLE dari presentasi menjadi berkas yang disematkan dalam PDF yang dihasilkan. Baca/tulis Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Baca-saja [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Mengembalikan atau menetapkan nilai yang menentukan kualitas gambar JPEG di dalam dokumen PDF. Baca/tulis Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Mengatur kata sandi pengguna untuk melindungi dokumen PDF. Baca/tulis String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Menunjukkan apakah teks harus dirasterisasi menjadi bitmap dan disimpan ke PDF ketika font tidak mendukung gaya tebal. Pendekatan ini dapat meningkatkan kualitas teks dalam PDF yang dihasilkan untuk font tertentu. Baca/tulis Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca/tulis Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Mengambil atau menetapkan mode penempatan slide pada halaman saat mengekspor presentasi [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Mengembalikan atau menetapkan nilai yang menentukan resolusi gambar di dalam dokumen PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Menentukan jenis kompresi yang akan digunakan untuk semua konten teks dalam dokumen. Baca/tulis [`PdfTextCompression`](../pdftextcompression). |

### Lihat Juga

* antarmuka [ISaveOptions](../isaveoptions)
* ruang nama [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->