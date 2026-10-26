---
title: NotesSlide class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/notesslide/
---
## NotesSlide kelas

Mewakili slide catatan dalam sebuah presentasi.

**Inheritance:**[`NotesSlide`](/slides/python-net/id/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)

Tipe NotesSlide mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`shapes`](/slides/python-net/id/aspose.slides/notesslide/shapes/) | Mengembalikan bentuk-bentuk slide.<br/>            Baca-saja [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/id/aspose.slides/notesslide/controls/) | Mengembalikan koleksi kontrol ActiveX pada slide.<br/>            Baca-saja [`IControlCollection`](/slides/python-net/id/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/id/aspose.slides/notesslide/name/) | Mengembalikan atau mengatur nama slide.<br/>            Baca/tulis **str**. |
| [`slide_id`](/slides/python-net/id/aspose.slides/notesslide/slide_id/) | Mengembalikan ID slide.<br/>            Baca-saja **int**. |
| [`custom_data`](/slides/python-net/id/aspose.slides/notesslide/custom_data/) | Mengembalikan data khusus slide.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/id/aspose.slides/notesslide/timeline/) | Mengembalikan objek timeline animasi.<br/>            Baca-saja [`IAnimationTimeLine`](/slides/python-net/id/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/notesslide/slide_show_transition/) | Mengembalikan objek Transition yang berisi informasi tentang<br/>            bagaimana slide yang ditentukan maju selama pertunjukan slide.<br/>            Baca-saja [`ISlideShowTransition`](/slides/python-net/id/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/id/aspose.slides/notesslide/background/) | Mengembalikan latar belakang slide.<br/>            Baca-saja [`IBackground`](/slides/python-net/id/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/notesslide/hyperlink_queries/) | Menyediakan akses mudah ke hyperlink yang terkandung.<br/>            Baca-saja [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/notesslide/show_master_shapes/) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak.<br/>            Baca/tulis **bool**. |
| [`presentation`](/slides/python-net/id/aspose.slides/notesslide/presentation/) | Mengembalikan antarmuka IPresentation.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/id/aspose.slides/notesslide/header_footer_manager/) | Mengembalikan manajer HeaderFooter dari slide catatan.<br/>            Baca-saja [`INotesSlideHeaderFooterManager`](/slides/python-net/id/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/id/aspose.slides/notesslide/notes_text_frame/) | Mengembalikan TextFrame dengan teks catatan jika ada.<br/>            Baca-saja [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/id/aspose.slides/notesslide/theme_manager/) | Mengembalikan manajer tema yang menimpa.<br/>            Baca-saja [`IOverrideThemeManager`](/slides/python-net/id/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/id/aspose.slides/notesslide/parent_slide/) | Mengembalikan slide induk.<br/>            Baca-saja [`ISlide`](/slides/python-net/id/aspose.slides/islide). |
| [`slide`](/slides/python-net/id/aspose.slides/notesslide/slide/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Menggabungkan run dengan format yang sama di semua paragraf semua shape yang dapat diterima. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/id/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Menggabungkan run dengan format yang sama di semua paragraf di semua shape yang dapat diterima. |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/notesslide/equals/#ibaseslide) | Menentukan apakah dua instance IBaseSlide sama.<br/>            Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis.<br/>            Dua slide dianggap sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll., sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId, serta konten dinamis, misalnya nilai tanggal saat ini dalam Placeholder Tanggal. |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/notesslide/create_theme_effective/#) | Mengembalikan tema efektif untuk slide ini. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Menemukan kemunculan pertama shape dengan teks alternatif yang ditentukan. |

### Lihat Juga
* kelas [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)
* kelas [`NotesSlide`](/slides/python-net/id/aspose.slides/notesslide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)