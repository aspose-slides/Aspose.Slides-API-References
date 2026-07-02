---
title: Presentation
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili presentasi Microsoft PowerPoint.
type: docs
weight: 9570
url: /id/aspose.slides/presentation/
---
## Presentation kelas

Mewakili presentasi Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Presentation](presentation#constructor)() | Konstruktor ini membuat presentasi baru dari awal. Presentasi yang dibuat memiliki satu slide kosong. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Konstruktor ini membuat presentasi baru dari awal. Presentasi yang dibuat memiliki satu slide kosong. |
| [Presentation](presentation#constructor_2)(Stream) | Konstruktor ini merupakan mekanisme utama untuk membaca Presentation yang ada. |
| [Presentation](presentation#constructor_4)(string) | Konstruktor ini mengambil jalur file sumber dari mana isi Presentation dibaca. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Konstruktor ini merupakan mekanisme utama untuk membaca Presentation yang ada. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Konstruktor ini mengambil jalur file sumber dari mana isi Presentation dibaca. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Mengembalikan semua bagian data khusus dalam presentasi. Baca-saja [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Mengembalikan koleksi semua file audio yang disematkan dalam presentasi. Baca-saja [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Mengembalikan koleksi penulis komentar. Baca-saja [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. Waktu pembuatan objek Presentation ini secara bawaan. Baca/tulis DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Mengembalikan data khusus presentasi. Baca-saja [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Mengembalikan gaya teks default untuk shape. Baca-saja [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Mengembalikan koleksi tanda tangan yang digunakan untuk menandatangani presentasi. Baca-saja [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Mengembalikan objek DocumentProperties yang berisi properti dokumen standar dan khusus. Baca-saja [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Menyatakan nomor slide pertama dalam presentasi |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Mengembalikan pengelola font. Baca-saja [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Mengembalikan pengelola HeaderFooter aktual. Baca-saja [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Menyediakan akses mudah ke semua hyperlink yang terdapat dalam semua slide presentasi (tidak termasuk master, layout, slide catatan). Baca-saja [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Mengembalikan koleksi semua gambar dalam presentasi. Baca-saja [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Mengembalikan daftar semua slide layout yang didefinisikan dalam presentasi. Baca-saja [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Mengembalikan pengelola handout master. Baca-saja [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Mengembalikan pengelola notes master. Baca-saja [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Mengembalikan daftar semua master slide yang didefinisikan dalam presentasi. Baca-saja [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Mengembalikan tema master. Baca-saja [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Mengembalikan objek ukuran slide catatan. Baca-saja [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Mengambil pengelola izin untuk presentasi ini. Baca-saja [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Mengembalikan daftar semua bagian slide yang didefinisikan dalam presentasi. Baca-saja [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi. Baca-saja [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Mengembalikan daftar semua slide yang didefinisikan dalam presentasi. Baca-saja [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Mengembalikan pengaturan pertunjukan slide untuk presentasi. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Mengembalikan objek ukuran slide. Baca-saja [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Mengembalikan informasi tentang format mana presentasi dimuat. Baca-saja [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Mengambil atau mengatur proyek VBA dengan makro presentasi. Baca/tulis [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Mengembalikan koleksi semua file video yang disematkan dalam presentasi. Baca-saja [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Mengambil properti tampilan seluruh presentasi. Baca-saja [`IViewProperties`](../iviewproperties). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Membebaskan semua sumber daya yang digunakan oleh objek Presentation ini. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Mengembalikan objek Image untuk semua slide dalam sebuah presentasi. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Mengembalikan objek Thumbnail Image untuk slide tertentu dalam sebuah presentasi. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Mengembalikan objek Thumbnail Image untuk semua slide dalam sebuah presentasi dengan ukuran tertentu. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Mengembalikan objek Thumbnail Image untuk semua slide dalam sebuah presentasi dengan skala khusus. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Mengembalikan objek Thumbnail Image untuk slide tertentu dalam sebuah presentasi dengan ukuran tertentu. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Mengembalikan objek Thumbnail Image untuk slide tertentu dalam sebuah presentasi dengan skala khusus. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Mengembalikan Slide, MasterSlide, atau LayoutSlide berdasarkan Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Menyoroti semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Menyoroti semua kecocokan teks contoh dengan warna yang ditentukan. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Menyoroti semua kecocokan teks contoh dengan warna yang ditentukan. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Menggabungkan run dengan format yang sama dalam semua paragraf di semua shape yang dapat diterima di semua slide. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Menyimpan semua slide dalam sebuah presentasi ke sekumpulan file yang mewakili markup XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Menyimpan semua slide dalam sebuah presentasi ke stream dalam format yang ditentukan. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Menyimpan semua slide dalam sebuah presentasi ke file dengan format yang ditentukan. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Menyimpan slide tertentu dalam sebuah presentasi ke stream dalam format yang ditentukan dengan mempertahankan nomor halaman. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Menyimpan semua slide dalam sebuah presentasi ke stream dalam format yang ditentukan dan dengan opsi tambahan. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Menyimpan slide tertentu dalam sebuah presentasi ke file dengan format yang ditentukan dengan mempertahankan nomor halaman. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Menyimpan slide tertentu dalam sebuah presentasi ke stream dalam format yang ditentukan dengan mempertahankan nomor halaman. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Menyimpan slide tertentu dalam sebuah presentasi ke file dengan format yang ditentukan dengan mempertahankan nomor halaman. |

### Contoh

Contoh berikut menunjukkan cara membuat PowerPoint Presentation.

```csharp
[C#]
// Membuat objek Presentation yang mewakili file presentasi
    // Ambil slide pertama
    // Tambahkan autoshape tipe garis
	// Simpan file presentasi.
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

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->