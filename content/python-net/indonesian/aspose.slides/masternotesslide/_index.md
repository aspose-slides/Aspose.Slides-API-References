---
title: MasterNotesSlide class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/masternotesslide/
---
## MasterNotesSlide kelas

Mewakili slide master untuk catatan.

**Pewarisan:**[`MasterNotesSlide`](/slides/python-net/id/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)

The MasterNotesSlide type exposes the following members:

## Properti

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/id/aspose.slides/masternotesslide/shapes/) | Mengembalikan bentuk-bentuk slide.<br/>            Read-only [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/id/aspose.slides/masternotesslide/controls/) | Mengembalikan koleksi kontrol ActiveX pada slide.<br/>            Read-only [`IControlCollection`](/slides/python-net/id/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/id/aspose.slides/masternotesslide/name/) | Mengembalikan atau mengatur nama slide.<br/>            Read/write **str**. |
| [`slide_id`](/slides/python-net/id/aspose.slides/masternotesslide/slide_id/) | Mengembalikan ID slide.<br/>            Read-only **int**. |
| [`custom_data`](/slides/python-net/id/aspose.slides/masternotesslide/custom_data/) | Mengembalikan data khusus slide.<br/>            Read-only [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/id/aspose.slides/masternotesslide/timeline/) | Mengembalikan objek garis waktu animasi.<br/>            Read-only [`IAnimationTimeLine`](/slides/python-net/id/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/masternotesslide/slide_show_transition/) | Mengembalikan objek Transition yang berisi informasi tentang<br/>            bagaimana slide yang ditentukan maju selama pertunjukan slide.<br/>            Read-only [`ISlideShowTransition`](/slides/python-net/id/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/id/aspose.slides/masternotesslide/background/) | Mengembalikan latar belakang slide.<br/>            Read-only [`IBackground`](/slides/python-net/id/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/masternotesslide/hyperlink_queries/) | Memberikan akses mudah ke tautan hiperteks yang terkandung.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/masternotesslide/show_master_shapes/) | Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak.<br/>            Untuk slide master sendiri properti ini selalu mengembalikan `false`.<br/>            Read/write **bool**. |
| [`presentation`](/slides/python-net/id/aspose.slides/masternotesslide/presentation/) | Mengembalikan antarmuka IPresentation.<br/>            Read-only [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/id/aspose.slides/masternotesslide/header_footer_manager/) | Mengembalikan manajer HeaderFooter dari slide catatan master.<br/>            Read-only [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/id/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/id/aspose.slides/masternotesslide/theme_manager/) | Mengembalikan manajer tema.<br/>            Read-only [`IMasterThemeManager`](/slides/python-net/id/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/id/aspose.slides/masternotesslide/notes_style/) | Mengembalikan gaya teks catatan.<br/>            Read-only [`ITextStyle`](/slides/python-net/id/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/id/aspose.slides/masternotesslide/drawing_guides/) | Mengembalikan koleksi panduan gambar untuk slide catatan master.<br/>            Read-only [`IDrawingGuidesCollection`](/slides/python-net/id/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/id/aspose.slides/masternotesslide/slide/) |  |

## Metode

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Menggabungkan run dengan format yang sama di semua paragraf pada semua bentuk yang dapat diterima. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/id/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Menggabungkan run dengan format yang sama di semua paragraf pada semua bentuk yang dapat diterima. |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/masternotesslide/equals/#ibaseslide) | Menentukan apakah dua instance IBaseSlide sama.<br/>            Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis.<br/>            Dua slide dianggap sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll. sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId, dan konten dinamis, misalnya nilai tanggal saat ini dalam Placeholder Tanggal. |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/masternotesslide/create_theme_effective/#) | Mengembalikan tema efektif untuk slide ini. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Menemukan kemunculan pertama bentuk dengan teks alternatif yang ditentukan. |


### Lihat Juga
* kelas [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)
* kelas [`MasterNotesSlide`](/slides/python-net/id/aspose.slides/masternotesslide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)