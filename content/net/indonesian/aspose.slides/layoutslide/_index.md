---
title: LayoutSlide
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili slide tata letak.
type: docs
weight: 7640
url: /id/aspose.slides/layoutslide/
---
## LayoutSlide kelas

Mewakili slide tata letak.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Mengembalikan latar belakang slide. Hanya-baca [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Mengembalikan koleksi kontrol ActiveX pada slide. Hanya-baca [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Mengembalikan data khusus slide. Hanya-baca [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Mengembalikan koleksi panduan gambar untuk slide tata letak. Hanya-baca [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Mengembalikan true bila ada setidaknya satu slide yang bergantung pada slide tata letak ini. Hanya-baca Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Mengembalikan pengelola HeaderFooter dari slide tata letak. Hanya-baca [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Menyediakan akses mudah ke tautan hiper yang terkandung. Hanya-baca [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Mengembalikan tipe tata letak slide ini. Hanya-baca [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Mengembalikan atau mengatur slide master untuk tata letak. Baca/tulis [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Mengembalikan atau mengatur nama slide. Baca/tulis String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Mengembalikan pengelola placeholder slide tata letak. Hanya-baca [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Mengembalikan antarmuka IPresentation. Hanya-baca [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Mengembalikan shape slide. Hanya-baca [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Menentukan apakah shape pada slide master harus ditampilkan pada slide atau tidak. Baca/tulis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Mengembalikan ID slide. Hanya-baca UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Mengembalikan objek Transition yang berisi informasi tentang bagaimana slide tertentu beralih selama tayangan slide. Hanya-baca [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Mengembalikan pengelola tema yang menggantikan. Hanya-baca [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Mengembalikan objek timeline animasi. Hanya-baca [`IAnimationTimeLine`](../ianimationtimeline). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Mengembalikan tema efektif untuk slide ini. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Menentukan apakah dua instance IBaseSlide sama. Nilai kembali dihitung berdasarkan struktur slide dan konten statis. Dua slide sama bila semua shape, gaya, teks, animasi, dan pengaturan lain, dll. sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId, serta konten dinamis, misalnya nilai tanggal saat ini dalam Placeholder Tanggal. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Menemukan kemunculan pertama shape dengan teks alternatif yang ditentukan. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Mengembalikan array dengan semua slide yang bergantung pada slide tata letak ini. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Menggabungkan run dengan pemformatan yang sama di semua paragraf semua shape yang dapat diterima. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Menggabungkan run dengan pemformatan yang sama di semua paragraf di semua shape yang dapat diterima. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Menghapus tata letak dari presentasi. |

### Lihat Juga

* kelas [BaseSlide](../baseslide)
* antarmuka [ILayoutSlide](../ilayoutslide)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->