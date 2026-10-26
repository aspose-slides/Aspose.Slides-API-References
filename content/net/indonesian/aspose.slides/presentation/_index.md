---
title: Presentation
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili presentasi Microsoft PowerPoint.
type: docs
weight: 9590
url: /id/aspose.slides/presentation/
---
## Kelas Presentation

Mewakili presentasi Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Presentation](presentation#constructor)() | Konstruktor ini membuat presentasi baru dari awal. Presentasi yang dibuat memiliki satu slide kosong. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Konstruktor ini membuat presentasi baru dari awal. Presentasi yang dibuat memiliki satu slide kosong. |
| [Presentation](presentation#constructor_2)(Stream) | Konstruktor ini merupakan mekanisme utama untuk membaca sebuah Presentation yang ada. |
| [Presentation](presentation#constructor_4)(string) | Konstruktor ini mengambil jalur file sumber dari mana isi Presentation dibaca. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Konstruktor ini merupakan mekanisme utama untuk membaca sebuah Presentation yang ada. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Konstruktor ini mengambil jalur file sumber dari mana isi Presentation dibaca. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Mengembalikan semua bagian data kustom dalam presentasi. Hanya-baca [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Mengembalikan koleksi semua file audio tertanam dalam presentasi. Hanya-baca [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Mengembalikan koleksi penulis komentar. Hanya-baca [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. Waktu pembuatan objek Presentation ini secara default. Baca/tulis DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Mengembalikan data kustom presentasi. Hanya-baca [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Mengembalikan gaya teks default untuk shape. Hanya-baca [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Mengembalikan koleksi tanda tangan yang digunakan untuk menandatangani presentasi. Hanya-baca [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Mengembalikan objek DocumentProperties yang berisi properti dokumen standar dan kustom. Hanya-baca [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Mewakili nomor slide pertama dalam presentasi |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Mengembalikan manajer font. Hanya-baca [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Mengembalikan manajer HeaderFooter aktual. Hanya-baca [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Memberikan akses mudah ke semua hyperlink yang terdapat dalam semua slide presentasi (tidak termasuk master, layout, slide catatan). Hanya-baca [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Mengembalikan koleksi semua gambar dalam presentasi. Hanya-baca [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Mengembalikan daftar semua slide layout yang didefinisikan dalam presentasi. Hanya-baca [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Mengembalikan manajer master handout. Hanya-baca [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Mengembalikan manajer master catatan. Hanya-baca [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Mengembalikan daftar semua slide master yang didefinisikan dalam presentasi. Hanya-baca [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Mengembalikan tema master. Hanya-baca [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Mengembalikan objek ukuran slide catatan. Hanya-baca [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Mendapatkan manajer izin untuk presentasi ini. Hanya-baca [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Mengembalikan daftar semua bagian slide yang didefinisikan dalam presentasi. Hanya-baca [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi. Hanya-baca [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Mengembalikan daftar semua slide yang didefinisikan dalam presentasi. Hanya-baca [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Mengembalikan pengaturan pertunjukan slide untuk presentasi. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Mengembalikan objek ukuran slide. Hanya-baca [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Mengembalikan informasi tentang format dari mana presentasi dimuat. Hanya-baca [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Mendapatkan atau mengatur proyek VBA dengan makro presentasi. Baca/tulis [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Mengembalikan koleksi semua file video tertanam dalam presentasi. Hanya-baca [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Mendapatkan properti tampilan seluruh presentasi. Hanya-baca [`IViewProperties`](../iviewproperties). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Melepaskan semua sumber daya yang digunakan oleh objek Presentation ini. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Mengembalikan objek Image untuk semua slide dalam sebuah presentasi. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Mengembalikan objek Thumbnail Image untuk slide tertentu dalam sebuah presentasi. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Mengembalikan objek Thumbnail Image untuk semua slide dalam sebuah presentasi dengan ukuran yang ditentukan. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Mengembalikan objek Thumbnail Image untuk semua slide dalam sebuah presentasi dengan skala khusus. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Mengembalikan objek Thumbnail Image untuk slide tertentu dalam sebuah presentasi dengan ukuran yang ditentukan. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Mengembalikan objek Thumbnail Image untuk slide tertentu dalam sebuah presentasi dengan skala khusus. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Mengembalikan Slide, MasterSlide, atau LayoutSlide berdasarkan Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Menggabungkan run dengan format yang sama di semua paragraf dalam semua shape yang dapat diakses di semua slide. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Menyimpan semua slide dalam sebuah presentasi ke sekumpulan file yang mewakili markup XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Menyimpan semua slide dalam sebuah presentasi ke stream dengan format yang ditentukan. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Menyimpan semua slide dalam sebuah presentasi ke file dengan format yang ditentukan. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Menyimpan slide tertentu dalam sebuah presentasi ke stream dengan format yang ditentukan sambil mempertahankan nomor halaman. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Menyimpan semua slide dalam sebuah presentasi ke stream dengan format yang ditentukan dan opsi tambahan. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Menyimpan slide tertentu dalam sebuah presentasi ke file dengan format yang ditentukan sambil mempertahankan nomor halaman. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Menyimpan slide tertentu dalam sebuah presentasi ke stream dengan format yang ditentukan dan opsi tambahan sambil mempertahankan nomor halaman. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Menyimpan slide tertentu dalam sebuah presentasi ke file dengan format yang ditentukan dan opsi tambahan sambil mempertahankan nomor halaman. |

### Contoh

Contoh berikut menunjukkan cara membuat PowerPoint Presentation.

```csharp
[C#]
// Membuat objek Presentation yang mewakili file presentasi
using (Presentation presentation = new Presentation())
{
    // Dapatkan slide pertama
    ISlide slide = presentation.Slides[0];
    // Tambahkan autoshape tipe garis
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Simpan file presentasi.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Contoh berikut menunjukkan cara membuka dan menyimpan Presentation.

```csharp
[C#]
// Muat file yang didukung apa pun dalam Presentation, misalnya ppt, pptx, odp, dll.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Simpan file presentasi.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Lihat Juga

* antarmuka [IPresentation](../ipresentation)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->