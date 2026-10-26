---
title: MasterSlide class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/masterslide/
---
## MasterSlide kelas

Mewakili slide master dalam presentasi.

**Inheritance:**[`MasterSlide`](/slides/python-net/id/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)

Tipe MasterSlide mengekspos anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`shapes`](/slides/python-net/id/aspose.slides/masterslide/shapes/) | Mengembalikan bentuk slide.<br/>            Baca-saja [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/id/aspose.slides/masterslide/controls/) | Mengembalikan koleksi kontrol ActiveX pada slide.<br/>            Baca-saja [`IControlCollection`](/slides/python-net/id/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/id/aspose.slides/masterslide/name/) | Mengembalikan atau mengatur nama slide master.<br/>            Baca/tulis **str**. |
| [`slide_id`](/slides/python-net/id/aspose.slides/masterslide/slide_id/) | Mengembalikan ID slide.<br/>            Baca-saja **int**. |
| [`custom_data`](/slides/python-net/id/aspose.slides/masterslide/custom_data/) | Mengembalikan data khusus slide.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/id/aspose.slides/masterslide/timeline/) | Mengembalikan objek timeline animasi.<br/>            Baca-saja [`IAnimationTimeLine`](/slides/python-net/id/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/masterslide/slide_show_transition/) | Mengembalikan objek Transition yang berisi informasi tentang<br/>            bagaimana slide yang ditentukan maju selama pertunjukan slide.<br/>            Baca-saja [`ISlideShowTransition`](/slides/python-net/id/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/id/aspose.slides/masterslide/background/) | Mengembalikan latar belakang slide.<br/>            Baca-saja [`IBackground`](/slides/python-net/id/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/masterslide/hyperlink_queries/) | Memberikan akses mudah ke hyperlink yang terkandung.<br/>            Baca-saja [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/masterslide/show_master_shapes/) | Menentukan apakah shape pada slide master harus ditampilkan pada slide atau tidak.<br/>            Untuk slide master itu sendiri properti ini selalu mengembalikan `false`.<br/>            Baca/tulis **bool**. |
| [`presentation`](/slides/python-net/id/aspose.slides/masterslide/presentation/) | Mengembalikan antarmuka IPresentation.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/id/aspose.slides/masterslide/header_footer_manager/) | Mengembalikan manajer HeaderFooter slide master.<br/>            Baca-saja [`IMasterSlideHeaderFooterManager`](/slides/python-net/id/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/id/aspose.slides/masterslide/title_style/) | Mengembalikan gaya teks judul.<br/>            Baca-saja [`ITextStyle`](/slides/python-net/id/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/id/aspose.slides/masterslide/body_style/) | Mengembalikan gaya teks isi.<br/>            Baca-saja [`ITextStyle`](/slides/python-net/id/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/id/aspose.slides/masterslide/other_style/) | Mengembalikan gaya teks lainnya.<br/>            Baca-saja [`ITextStyle`](/slides/python-net/id/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/id/aspose.slides/masterslide/layout_slides/) | Mengembalikan koleksi slide layout anak untuk slide master ini.<br/>            Baca-saja [`IMasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/id/aspose.slides/masterslide/preserve/) | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master itu dihapus.<br/>            Catatan: Aspose.Slides tidak akan pernah menghapus master yang tidak terpakai secara otomatis, untuk benar-benar menghapus master yang tidak terpakai panggil **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Baca/tulis **bool**. |
| [`has_depending_slides`](/slides/python-net/id/aspose.slides/masterslide/has_depending_slides/) | Mengembalikan true jika ada setidaknya satu slide yang bergantung pada slide master ini.<br/>            Baca-saja **bool**. |
| [`theme_manager`](/slides/python-net/id/aspose.slides/masterslide/theme_manager/) | Mengembalikan manajer tema.<br/>            Baca-saja [`IMasterThemeManager`](/slides/python-net/id/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/id/aspose.slides/masterslide/drawing_guides/) | Mengembalikan koleksi panduan gambar untuk slide master.<br/>            Baca-saja [`IDrawingGuidesCollection`](/slides/python-net/id/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/id/aspose.slides/masterslide/slide/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Menggabungkan run dengan pemformatan yang sama di semua paragraf semua shape yang dapat diterima. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/id/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Menggabungkan run dengan pemformatan yang sama di semua paragraf di semua shape yang dapat diterima. |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/masterslide/equals/#ibaseslide) | Menentukan apakah dua instance IBaseSlide sama.<br/>            Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis.<br/>            Dua slide dianggap sama jika semua shape, gaya, teks, animasi, dan pengaturan lain, dll. sama. Perbandingan tidak mempertimbangkan nilai pengidentifikasi unik, misalnya SlideId dan konten dinamis, misalnya nilai tanggal saat ini dalam Placeholder Tanggal. |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/masterslide/create_theme_effective/#) | Mengembalikan tema efektif untuk slide ini. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Menemukan kemunculan pertama shape dengan teks alternatif yang ditentukan. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/id/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Membuat slide master baru berdasarkan yang saat ini, menerapkan tema eksternal padanya <br/>            dan menerapkan slide master yang dibuat ke semua slide yang bergantung. |
| [`get_depending_slides(self)`](/slides/python-net/id/aspose.slides/masterslide/get_depending_slides/#) | Mengembalikan array dengan semua slide yang bergantung pada slide master ini. |

### Lihat Juga
* kelas [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)
* kelas [`MasterSlide`](/slides/python-net/id/aspose.slides/masterslide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)