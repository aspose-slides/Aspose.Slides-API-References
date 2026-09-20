---
title: IMasterSlide class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/imasterslide/
---
## IMasterSlide kelas

Mewakili slide master dalam sebuah presentasi.

Tipe IMasterSlide mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/id/aspose.slides/imasterslide/header_footer_manager/) | Mengembalikan manajer HeaderFooter dari slide master.<br/>            Hanya-baca [`IMasterSlideHeaderFooterManager`](/slides/python-net/id/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/id/aspose.slides/imasterslide/title_style/) | Mengembalikan gaya teks judul.<br/>            Hanya-baca [`ITextStyle`](/slides/python-net/id/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/id/aspose.slides/imasterslide/body_style/) | Mengembalikan gaya teks badan.<br/>            Hanya-baca [`ITextStyle`](/slides/python-net/id/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/id/aspose.slides/imasterslide/other_style/) | Mengembalikan gaya teks lain.<br/>            Hanya-baca [`ITextStyle`](/slides/python-net/id/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/id/aspose.slides/imasterslide/layout_slides/) | Mengembalikan koleksi slide tata letak anak untuk slide master ini.<br/>            Hanya-baca [`IMasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/id/aspose.slides/imasterslide/preserve/) | Menentukan apakah master yang bersangkutan dihapus ketika semua <br/>            slide yang mengikuti master tersebut dihapus.<br/>            Catatan: Aspose.Slides tidak akan pernah menghapus master yang tidak terpakai secara otomatis, <br/>            untuk benar-benar menghapus master yang tidak terpakai panggil **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Baca/tulis **bool**. |
| [`has_depending_slides`](/slides/python-net/id/aspose.slides/imasterslide/has_depending_slides/) | Mengembalikan true jika terdapat setidaknya satu slide yang bergantung pada slide master ini.<br/>            Hanya-baca **bool**. |
| [`drawing_guides`](/slides/python-net/id/aspose.slides/imasterslide/drawing_guides/) | Mengembalikan koleksi panduan gambar untuk slide master.<br/>            Hanya-baca [`IDrawingGuidesCollection`](/slides/python-net/id/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/id/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/id/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/id/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/id/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/id/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/id/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/id/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/id/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/id/aspose.slides/imasterslide/theme_manager/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/id/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Membuat slide master baru berdasarkan slide saat ini, menerapkan tema eksternal padanya <br/>            dan menerapkan slide master yang dibuat ke semua slide yang bergantung. |
| [`get_depending_slides(self)`](/slides/python-net/id/aspose.slides/imasterslide/get_depending_slides/#) | Mengembalikan array berisi semua slide yang bergantung pada slide master ini. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/imasterslide/create_theme_effective/#) |  |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)