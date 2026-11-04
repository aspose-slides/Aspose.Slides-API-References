---
title: LayoutSlide
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mewakili sebuah layout slide.
type: docs
weight: 7660
url: /id/aspose.slides/layoutslide/
---
## LayoutSlide kelas

Mewakili sebuah layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Mengembalikan latar belakang slide. Baca-saja [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Mengembalikan koleksi kontrol ActiveX pada slide. Baca-saja [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Mengembalikan data khusus slide. Baca-saja [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Mengembalikan koleksi panduan gambar untuk layout slide. Baca-saja [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Mengembalikan true jika terdapat setidaknya satu slide yang bergantung pada layout slide ini. Baca-saja Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Mengembalikan manajer HeaderFooter dari layout slide. Baca-saja [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Menyediakan akses mudah ke hyperlink yang terdapat. Baca-saja [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Mengembalikan tipe layout dari layout slide ini. Baca-saja [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Mengembalikan atau mengatur slide master untuk layout. Baca/tulis [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Mengembalikan atau mengatur nama slide. Baca/tulis String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Mengembalikan manajer placeholder dari layout slide. Baca-saja [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Mengembalikan antarmuka IPresentation. Baca-saja [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Mengembalikan bentuk-bentuk slide. Baca-saja [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. Baca/tulis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Mengembalikan ID slide. Baca-saja UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Mengembalikan objek Transition yang berisi informasi tentang bagaimana slide yang ditentukan maju selama presentasi slide. Baca-saja [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Mengembalikan manajer tema yang menimpa. Baca-saja [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Mengembalikan objek timeline animasi. Baca-saja [`IAnimationTimeLine`](../ianimationtimeline). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Mengembalikan tema efektif untuk slide ini. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Menentukan apakah dua instance IBaseSlide sama. Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis. Dua slide dianggap sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll., sama. Perbandingan tidak memperhitungkan nilai pengenal unik, misalnya SlideId dan konten dinamis, misalnya nilai tanggal saat ini dalam Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Menemukan kemunculan pertama dari bentuk dengan teks alternatif yang ditentukan. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Mengembalikan array dengan semua slide yang bergantung pada layout slide ini. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Menggabungkan run dengan format yang sama dalam semua paragraf dan semua bentuk yang dapat diterima. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Menggabungkan run dengan format yang sama dalam semua paragraf pada semua bentuk yang dapat diterima. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Menghapus layout dari presentasi. |

### Lihat Juga

* kelas [BaseSlide](../baseslide)
* antarmuka [ILayoutSlide](../ilayoutslide)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->