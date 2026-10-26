---
title: MasterHandoutSlide class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide kelas

Mewakili master slide untuk handout.

**Inheritance:**[`MasterHandoutSlide`](/slides/python-net/id/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)

tipe MasterHandoutSlide menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`shapes`](/slides/python-net/id/aspose.slides/masterhandoutslide/shapes/) | Mengembalikan bentuk slide.<br/>            Hanya-baca [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/id/aspose.slides/masterhandoutslide/controls/) | Mengembalikan koleksi kontrol ActiveX pada slide.<br/>            Hanya-baca [`IControlCollection`](/slides/python-net/id/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/id/aspose.slides/masterhandoutslide/name/) | Mengembalikan atau mengatur nama slide.<br/>            Baca/tulis **str**. |
| [`slide_id`](/slides/python-net/id/aspose.slides/masterhandoutslide/slide_id/) | Mengembalikan ID slide.<br/>            Hanya-baca **int**. |
| [`custom_data`](/slides/python-net/id/aspose.slides/masterhandoutslide/custom_data/) | Mengembalikan data khusus slide.<br/>            Hanya-baca [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/id/aspose.slides/masterhandoutslide/timeline/) | Mengembalikan objek timeline animasi.<br/>            Hanya-baca [`IAnimationTimeLine`](/slides/python-net/id/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/masterhandoutslide/slide_show_transition/) | Mengembalikan objek Transition yang berisi informasi tentang<br/>            bagaimana slide yang ditentukan maju selama pertunjukan slide.<br/>            Hanya-baca [`ISlideShowTransition`](/slides/python-net/id/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/id/aspose.slides/masterhandoutslide/background/) | Mengembalikan latar belakang slide.<br/>            Hanya-baca [`IBackground`](/slides/python-net/id/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/masterhandoutslide/hyperlink_queries/) | Menyediakan akses mudah ke hyperlink yang terkandung.<br/>            Hanya-baca [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/masterhandoutslide/show_master_shapes/) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak.<br/>            Untuk master slide itu sendiri properti ini selalu mengembalikan `false`.<br/>            Baca/tulis **bool**. |
| [`presentation`](/slides/python-net/id/aspose.slides/masterhandoutslide/presentation/) | Mengembalikan antarmuka IPresentation.<br/>            Hanya-baca [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/id/aspose.slides/masterhandoutslide/header_footer_manager/) | Mengembalikan manajer HeaderFooter dari master handout slide.<br/>            Hanya-baca [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/id/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/id/aspose.slides/masterhandoutslide/theme_manager/) | Mengembalikan manajer tema.<br/>            Hanya-baca [`IMasterThemeManager`](/slides/python-net/id/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/id/aspose.slides/masterhandoutslide/drawing_guides/) | Mengembalikan koleksi panduan menggambar untuk master handout slide.<br/>            Hanya-baca [`IDrawingGuidesCollection`](/slides/python-net/id/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/id/aspose.slides/masterhandoutslide/slide/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Menggabungkan run dengan format yang sama di semua paragraf semua shape yang dapat diterima. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/id/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Menggabungkan run dengan format yang sama di semua paragraf di semua shape yang dapat diterima. |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Menentukan apakah dua instance IBaseSlide sama.<br/>            Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis.<br/>            Dua slide dianggap sama jika semua shape, gaya, teks, animasi, dan pengaturan lainnya, dll. sama. Perbandingan tidak memperhitungkan nilai pengenal unik, misalnya SlideId dan konten dinamis, misalnya nilai tanggal saat ini dalam Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/masterhandoutslide/create_theme_effective/#) | Mengembalikan tema efektif untuk slide ini. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Menemukan kemunculan pertama shape dengan teks alternatif yang ditentukan. |

### Lihat Juga
* kelas [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)
* kelas [`MasterHandoutSlide`](/slides/python-net/id/aspose.slides/masterhandoutslide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)