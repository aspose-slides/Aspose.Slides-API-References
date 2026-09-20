---
title: BaseSlide class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/baseslide/
---
## BaseSlide kelas

Represents common data for all slide types.

The BaseSlide type exposes the following members:

## Properti

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/id/aspose.slides/baseslide/shapes/) | Mengembalikan bentuk slide.<br/>            Baca-saja [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/id/aspose.slides/baseslide/controls/) | Mengembalikan koleksi kontrol ActiveX pada slide.<br/>            Baca-saja [`IControlCollection`](/slides/python-net/id/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/id/aspose.slides/baseslide/name/) | Mengembalikan atau mengatur nama slide.<br/>            Baca/tulis **str**. |
| [`slide_id`](/slides/python-net/id/aspose.slides/baseslide/slide_id/) | Mengembalikan ID slide.<br/>            Baca-saja **int**. |
| [`custom_data`](/slides/python-net/id/aspose.slides/baseslide/custom_data/) | Mengembalikan data khusus slide.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/id/aspose.slides/baseslide/timeline/) | Mengembalikan objek timeline animasi.<br/>            Baca-saja [`IAnimationTimeLine`](/slides/python-net/id/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/baseslide/slide_show_transition/) | Mengembalikan objek Transition yang berisi informasi tentang<br/>            cara slide yang ditentukan maju selama pertunjukan slide.<br/>            Baca-saja [`ISlideShowTransition`](/slides/python-net/id/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/id/aspose.slides/baseslide/background/) | Mengembalikan latar belakang slide.<br/>            Baca-saja [`IBackground`](/slides/python-net/id/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/baseslide/hyperlink_queries/) | Menyediakan akses mudah ke hyperlink yang terkandung.<br/>            Baca-saja [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/baseslide/show_master_shapes/) | Menentukan apakah shapes pada master slide harus ditampilkan pada slide atau tidak.<br/>            Untuk master slide sendiri properti ini selalu mengembalikan `false`.<br/>            Baca/tulis **bool**. |
| [`presentation`](/slides/python-net/id/aspose.slides/baseslide/presentation/) | Mengembalikan antarmuka IPresentation.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/id/aspose.slides/baseslide/slide/) |  |

## Metode

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Menggabungkan run dengan pemformatan yang sama di semua paragraf pada semua shape yang dapat diterima. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/id/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Menggabungkan run dengan pemformatan yang sama di semua paragraf pada semua shape yang dapat diterima. |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/baseslide/equals/#ibaseslide) | Menentukan apakah dua instance IBaseSlide sama.<br/>            Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis.<br/>            Dua slide dianggap sama jika semua shape, gaya, teks, animasi, dan pengaturan lainnya, dll., sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId, serta konten dinamis, misalnya nilai tanggal saat ini dalam Placeholder Tanggal. |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/baseslide/create_theme_effective/#) | Mengembalikan tema efektif untuk slide ini. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Menemukan kemunculan pertama shape dengan teks alternatif yang ditentukan. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)