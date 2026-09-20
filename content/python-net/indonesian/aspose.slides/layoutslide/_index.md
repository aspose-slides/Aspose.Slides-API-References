---
title: LayoutSlide class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/layoutslide/
---
## LayoutSlide kelas

Mewakili slide tata letak.

**Warisan:**[`LayoutSlide`](/slides/python-net/id/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)

Tipe LayoutSlide mengekspor anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`shapes`](/slides/python-net/id/aspose.slides/layoutslide/shapes/) | Mengembalikan bentuk-bentuk slide.<br/>            Hanya-baca [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/id/aspose.slides/layoutslide/controls/) | Mengembalikan koleksi kontrol ActiveX pada slide.<br/>            Hanya-baca [`IControlCollection`](/slides/python-net/id/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/id/aspose.slides/layoutslide/name/) | Mengembalikan atau mengatur nama slide.<br/>            Baca/tulis **str**. |
| [`slide_id`](/slides/python-net/id/aspose.slides/layoutslide/slide_id/) | Mengembalikan ID slide.<br/>            Hanya-baca **int**. |
| [`custom_data`](/slides/python-net/id/aspose.slides/layoutslide/custom_data/) | Mengembalikan data khusus slide.<br/>            Hanya-baca [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/id/aspose.slides/layoutslide/timeline/) | Mengembalikan objek timeline animasi.<br/>            Hanya-baca [`IAnimationTimeLine`](/slides/python-net/id/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/layoutslide/slide_show_transition/) | Mengembalikan objek Transition yang berisi informasi tentang<br/>            bagaimana slide yang ditentukan maju selama pertunjukan slide.<br/>            Hanya-baca [`ISlideShowTransition`](/slides/python-net/id/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/id/aspose.slides/layoutslide/background/) | Mengembalikan latar belakang slide.<br/>            Hanya-baca [`IBackground`](/slides/python-net/id/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/layoutslide/hyperlink_queries/) | Memberikan akses mudah ke hyperlink yang terkandung.<br/>            Hanya-baca [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/layoutslide/show_master_shapes/) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak.<br/>            Baca/tulis **bool**. |
| [`presentation`](/slides/python-net/id/aspose.slides/layoutslide/presentation/) | Mengembalikan antarmuka IPresentation.<br/>            Hanya-baca [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/id/aspose.slides/layoutslide/header_footer_manager/) | Mengembalikan manajer HeaderFooter dari layout slide.<br/>            Hanya-baca [`ILayoutSlideHeaderFooterManager`](/slides/python-net/id/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/id/aspose.slides/layoutslide/placeholder_manager/) | Mengembalikan manajer placeholder dari layout slide.<br/>            Hanya-baca [`ILayoutPlaceholderManager`](/slides/python-net/id/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/id/aspose.slides/layoutslide/master_slide/) | Mengembalikan atau mengatur master slide untuk layout.<br/>            Baca/tulis [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/id/aspose.slides/layoutslide/theme_manager/) | Mengembalikan manajer tema yang menimpa.<br/>            Hanya-baca [`IOverrideThemeManager`](/slides/python-net/id/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/id/aspose.slides/layoutslide/layout_type/) | Mengembalikan tipe layout dari layout slide ini.<br/>            Hanya-baca [`SlideLayoutType`](/slides/python-net/id/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/id/aspose.slides/layoutslide/has_depending_slides/) | Mengembalikan true jika ada setidaknya satu slide yang bergantung pada layout slide ini.<br/>            Hanya-baca **bool**. |
| [`drawing_guides`](/slides/python-net/id/aspose.slides/layoutslide/drawing_guides/) | Mengembalikan koleksi panduan menggambar untuk layout slide.<br/>            Hanya-baca [`IDrawingGuidesCollection`](/slides/python-net/id/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/id/aspose.slides/layoutslide/slide/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Menggabungkan run dengan format yang sama dalam semua paragraf pada semua bentuk yang dapat diterima. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/id/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Menggabungkan run dengan format yang sama dalam semua paragraf pada semua bentuk yang dapat diterima. |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/layoutslide/equals/#ibaseslide) | Menentukan apakah dua instance IBaseSlide sama.<br/>            Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis.<br/>            Dua slide dianggap sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll. sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId dan konten dinamis, misalnya nilai tanggal saat ini dalam Placeholder Tanggal. |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/layoutslide/create_theme_effective/#) | Mengembalikan tema efektif untuk slide ini. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Menemukan kejadian pertama bentuk dengan teks alternatif yang ditentukan. |
| [`remove(self)`](/slides/python-net/id/aspose.slides/layoutslide/remove/#) | Menghapus layout dari presentasi. |
| [`get_depending_slides(self)`](/slides/python-net/id/aspose.slides/layoutslide/get_depending_slides/#) | Mengembalikan array berisi semua slide yang bergantung pada layout slide ini. |


### Lihat Juga
* kelas [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)
* kelas [`LayoutSlide`](/slides/python-net/id/aspose.slides/layoutslide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)