---
title: MasterSlide
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili slide master dalam sebuah presentasi.
type: docs
weight: 8030
url: /id/aspose.slides/masterslide/
---
## MasterSlide kelas

Represents a master slide in a presentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Properti

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Mengembalikan latar belakang slide. Hanya-baca [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Mengembalikan gaya teks badan. Hanya-baca [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Mengembalikan koleksi kontrol ActiveX pada slide. Hanya-baca [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Mengembalikan data khusus slide. Hanya-baca [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Mengembalikan koleksi panduan gambar untuk master slide. Hanya-baca [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Mengembalikan true jika ada setidaknya satu slide yang bergantung pada master slide ini. Hanya-baca Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Mengembalikan manajer HeaderFooter dari master slide. Hanya-baca [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Menyediakan akses mudah ke hyperlink yang terkandung. Hanya-baca [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Mengembalikan koleksi slide tata letak anak untuk master slide ini. Hanya-baca [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Mengembalikan atau mengatur nama master slide. Baca/tulis String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Mengembalikan gaya teks lain. Hanya-baca [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Mengembalikan antarmuka IPresentation. Hanya-baca [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. Catatan: Aspose.Slides tidak akan pernah menghapus master yang tidak terpakai secara otomatis; untuk benar-benar menghapus master yang tidak terpakai panggil [`RemoveUnused`](../masterslidecollection/removeunused). Baca/tulis Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Mengembalikan shapes slide. Hanya-baca [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Menentukan apakah shapes pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide itu sendiri properti ini selalu mengembalikan `false`. Baca/tulis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Mengembalikan ID slide. Hanya-baca UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Mengembalikan objek Transition yang berisi informasi tentang bagaimana slide yang ditentukan maju selama pertunjukan slide. Hanya-baca [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Mengembalikan manajer tema. Hanya-baca [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Mengembalikan objek timeline animasi. Hanya-baca [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Mengembalikan gaya teks judul. Hanya-baca [`ITextStyle`](../itextstyle). |

## Metode

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Membuat master slide baru berdasarkan yang saat ini, menerapkan tema eksternal padanya, dan menerapkan master slide yang dibuat ke semua slide yang bergantung. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Mengembalikan tema efektif untuk slide ini. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Menentukan apakah dua instance IBaseSlide sama. Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis. Dua slide dianggap sama jika semua shapes, gaya, teks, animasi, dan pengaturan lainnya, dll., sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId, serta konten dinamis, misalnya nilai tanggal saat ini dalam Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Menemukan kemunculan pertama shape dengan teks alternatif yang ditentukan. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Mengembalikan array dengan semua slide yang bergantung pada master slide ini. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Menggabungkan run dengan format yang sama di semua paragraf pada semua shape yang dapat diterima. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Menggabungkan run dengan format yang sama di semua paragraf pada semua shape yang dapat diterima. |

### Lihat Juga

* kelas [BaseSlide](../baseslide)
* antarmuka [IMasterSlide](../imasterslide)
* ruang nama [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->