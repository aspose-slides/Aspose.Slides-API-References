---
title: IBaseSlide class
second_title: Aspose.Slides untuk Python melalui Referensi API .NET
description: 
type: docs
url: /id/aspose.slides/ibaseslide/
---
## IBaseSlide kelas

Mewakili data umum untuk semua tipe slide.

Tipe IBaseSlide mengekspos anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/id/aspose.slides/ibaseslide/shapes/) | Mengembalikan shapes dari slide.<br/>            Baca-saja [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/id/aspose.slides/ibaseslide/controls/) | Mengembalikan koleksi kontrol ActiveX pada slide.<br/>            Baca-saja [`IControlCollection`](/slides/python-net/id/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/id/aspose.slides/ibaseslide/name/) | Mengembalikan atau mengatur nama slide.<br/>            Baca/tulis **str**. |
| [`slide_id`](/slides/python-net/id/aspose.slides/ibaseslide/slide_id/) | Mengembalikan ID slide.<br/>            Baca-saja **int**. |
| [`custom_data`](/slides/python-net/id/aspose.slides/ibaseslide/custom_data/) | Mengembalikan data khusus slide.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/id/aspose.slides/ibaseslide/timeline/) | Mengembalikan objek timeline animasi.<br/>            Baca-saja [`IAnimationTimeLine`](/slides/python-net/id/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/ibaseslide/slide_show_transition/) | Mengembalikan objek TransitionEx yang berisi informasi tentang<br/>            bagaimana slide yang ditentukan maju selama pertunjukan slide.<br/>            Baca-saja [`ISlideShowTransition`](/slides/python-net/id/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/id/aspose.slides/ibaseslide/background/) | Mengembalikan latar belakang slide.<br/>            Baca-saja [`IBackground`](/slides/python-net/id/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/ibaseslide/hyperlink_queries/) | Menyediakan akses mudah ke hyperlink yang terdapat.<br/>            Baca-saja [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/ibaseslide/show_master_shapes/) | Menentukan apakah shapes pada master slide harus ditampilkan pada slide atau tidak.<br/>            Untuk master slide itu sendiri properti ini selalu mengembalikan `false`.<br/>            Baca/tulis **bool**. |
| [`slide`](/slides/python-net/id/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/ibaseslide/presentation/) |  |

## Metode

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Menemukan kemunculan pertama dari shape dengan teks alternatif yang ditentukan. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Menggabungkan run dengan format yang sama di semua paragraf dalam semua shape yang dapat diterima. |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/ibaseslide/equals/#ibaseslide) | Menentukan apakah dua instance IBaseSlide sama.<br/>            Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis.<br/>            Dua slide dianggap sama jika semua shape, gaya, teks, animasi, dan pengaturan lainnya, dll. sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId dan konten dinamis, misalnya nilai tanggal saat ini dalam Placeholder Tanggal. |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)