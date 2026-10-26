---
title: IPresentation
second_title: Referensi API Aspose.Sildes untuk .NET
description: Dokumen presentasi
type: docs
weight: 6750
url: /id/aspose.slides/ipresentation/
---
## IPresentation antarmuka

Dokumen presentasi

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Mengembalikan semua bagian data khusus dalam presentasi. Hanya-baca [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Mengembalikan antarmuka IDisposable. Hanya-baca IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Memungkinkan mendapatkan antarmuka IPresentationComponent dasar. Hanya-baca [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Mengembalikan koleksi semua file audio tersemat dalam presentasi. Hanya-baca [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Mengembalikan koleksi penulis komentar. Hanya-baca [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. Waktu pembuatan objek Presentation ini secara default. Baca/tulis DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Mengembalikan data khusus presentasi. Hanya-baca [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Mengembalikan gaya teks default untuk bentuk. Hanya-baca [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Mengembalikan koleksi tanda tangan yang digunakan untuk menandatangani presentasi. Hanya-baca [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Mengembalikan objek DocumentProperties yang berisi properti dokumen standar dan khusus. Hanya-baca [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Mewakili nomor slide pertama dalam presentasi. Baca/tulis Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Mengembalikan pengelola font. Hanya-baca [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Mengembalikan pengelola HeaderFooter presentasi. Hanya-baca [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Memberikan akses mudah ke semua hyperlink yang terdapat dalam semua slide presentasi (tidak termasuk slide master, layout, catatan). Hanya-baca [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Mengembalikan koleksi semua gambar dalam presentasi. Hanya-baca [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Mengembalikan daftar semua slide layout yang didefinisikan dalam presentasi. Hanya-baca [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Mengembalikan pengelola handout master. Hanya-baca [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Mengembalikan pengelola notes master. Hanya-baca [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Mengembalikan daftar semua slide master yang didefinisikan dalam presentasi. Hanya-baca [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Mengembalikan tema master presentasi. Hanya-baca [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Mengembalikan objek ukuran slide catatan. Hanya-baca [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Mengembalikan pengelola izin untuk presentasi ini. Hanya-baca [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Mengembalikan daftar semua bagian slide yang didefinisikan dalam presentasi. Hanya-baca [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi. Hanya-baca [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Mengembalikan daftar semua slide yang didefinisikan dalam presentasi. Hanya-baca [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Mengembalikan objek ukuran slide. Hanya-baca [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Mengembalikan informasi tentang format mana presentasi dimuat. Hanya-baca [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Mendapatkan proyek VBA dengan makro presentasi. Baca/tulis [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Mengembalikan koleksi semua file video tersemat dalam presentasi. Hanya-baca [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Mendapatkan properti tampilan lebar presentasi. Hanya-baca [`IViewProperties`](../iviewproperties). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Mengembalikan objek Gambar Thumbnail untuk semua slide dalam satu presentasi. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Mengembalikan objek Bitmap Thumbnail untuk slide tertentu dalam presentasi. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Mengembalikan objek Gambar Thumbnail untuk semua slide dalam presentasi dengan ukuran yang ditentukan. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Mengembalikan objek Gambar Thumbnail untuk semua slide dalam presentasi dengan skala khusus. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Mengembalikan objek Gambar Thumbnail untuk slide tertentu dalam presentasi dengan ukuran yang ditentukan. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Mengembalikan objek Gambar Thumbnail untuk slide tertentu dalam presentasi dengan skala khusus. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Mengembalikan Slide, MasterSlide, atau LayoutSlide berdasarkan Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Menggabungkan run dengan pemformatan yang sama dalam semua paragraf di semua bentuk yang dapat diterima di semua slide. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Menyimpan semua slide presentasi ke sekumpulan file yang mewakili markup XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Menyimpan semua slide presentasi ke stream dalam format yang ditentukan. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Menyimpan semua slide presentasi ke file dengan format yang ditentukan. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Menyimpan slide tertentu dari presentasi ke stream dalam format yang ditentukan. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Menyimpan semua slide presentasi ke stream dalam format yang ditentukan dengan opsi tambahan. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Menyimpan slide tertentu dari presentasi ke file dengan format yang ditentukan. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Menyimpan semua slide presentasi ke file dengan format yang ditentukan dan opsi tambahan. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Menyimpan slide tertentu dari presentasi ke stream dalam format yang ditentukan. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Menyimpan slide tertentu dari presentasi ke file dengan format yang ditentukan. |

### Lihat Juga

* antarmuka [IPresentationComponent](../ipresentationcomponent)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->