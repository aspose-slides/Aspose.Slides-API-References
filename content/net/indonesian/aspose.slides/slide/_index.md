---
title: Slide
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili slide dalam presentasi.
type: docs
weight: 9960
url: /id/aspose.slides/slide/
---
## Kelas Slide

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Properti

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Mengembalikan latar belakang slide. Hanya-baca [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Mengembalikan koleksi kontrol ActiveX pada slide. Hanya-baca [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Mengembalikan data khusus slide. Hanya-baca [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Mengembalikan pengelola HeaderFooter slide. Hanya-baca [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide. Baca/tulis Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Memberikan akses mudah ke hyperlink yang terkandung. Hanya-baca [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Mengembalikan atau mengatur slide tata letak untuk slide saat ini. Baca/tulis [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Mengembalikan atau mengatur nama slide. Baca/tulis String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Memungkinkan mengakses slide catatan, menambah dan menghapusnya. Hanya-baca [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Mengembalikan antarmuka IPresentation. Hanya-baca [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Mengembalikan bentuk-bentuk slide. Hanya-baca [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. Baca/tulis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Mengembalikan ID slide. Hanya-baca UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Mengembalikan nomor slide. Indeks slide dalam koleksi [`Slides`](../presentation/slides) selalu sama dengan SlideNumber - Presentation.FirstSlideNumber. Baca/tulis Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Mengembalikan objek Transition yang berisi informasi tentang bagaimana slide yang ditentukan berpindah selama pertunjukan slide. Hanya-baca [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Mengembalikan pengelola tema yang menggantikan. Hanya-baca [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Mengembalikan objek garis waktu animasi. Hanya-baca [`IAnimationTimeLine`](../ianimationtimeline). |

## Metode

| Name | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Mengembalikan tema efektif untuk slide ini. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Menentukan apakah dua instance IBaseSlide sama. Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis. Dua slide dianggap sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll., sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId dan konten dinamis, misalnya nilai tanggal saat ini dalam Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Menemukan kemunculan pertama dari sebuah bentuk dengan teks alternatif yang ditentukan. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Mengembalikan objek Gambar Thumbnail (20% dari ukuran sebenarnya). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Mengembalikan objek Gambar Thumbnail. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Mengembalikan objek gambar tiff Thumbnail dengan parameter yang ditentukan. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Mengembalikan objek Gambar Thumbnail dengan ukuran yang ditentukan. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Mengembalikan objek Gambar Thumbnail dengan skala khusus. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Mengembalikan objek Gambar Thumbnail dengan ukuran yang ditentukan. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Mengembalikan objek Gambar Thumbnail dengan skala khusus. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Menggabungkan run dengan format yang sama di semua paragraf dalam semua bentuk yang dapat diterima. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Menggabungkan run dengan format yang sama di semua paragraf dalam semua bentuk yang dapat diterima. |
| [Remove](../../aspose.slides/slide/remove)() | Menghapus slide dari presentasi. |
| [Reset](../../aspose.slides/slide/reset)() | Mengatur ulang posisi, ukuran, dan format setiap bentuk yang memiliki prototipe pada LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Menyimpan konten slide sebagai berkas EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Menyimpan konten slide sebagai berkas SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Menyimpan konten slide sebagai berkas SVG. |

### Lihat Juga

* kelas [BaseSlide](../baseslide)
* antarmuka [ISlide](../islide)
* ruang nama [Aspose.Slides](../../aspose.slides)
* perakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->