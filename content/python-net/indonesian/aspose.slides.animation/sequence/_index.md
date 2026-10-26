---
title: Sequence class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.animation/sequence/
---
## Kelas Sequence

Mewakili urutan (koleksi efek).

Tipe Sequence mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`count`](/slides/python-net/id/aspose.slides.animation/sequence/count/) | Mengembalikan jumlah efek dalam sebuah urutan.<br/>            Baca-saja **int**. |
| [`trigger_shape`](/slides/python-net/id/aspose.slides.animation/sequence/trigger_shape/) | Mengembalikan atau mengatur target shape untuk urutan INTERACTIVE.<br/>            Jika urutan tidak interaktif maka mengembalikan None.<br/>            Baca/tulis [`IShape`](/slides/python-net/id/aspose.slides/ishape). |

Mengembalikan efek pada indeks yang ditentukan.

## Pengindeks

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides.animation/sequence/__getitem__/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/id/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Menambahkan efek baru ke akhir urutan. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/id/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Menambahkan efek animasi baru untuk paragraf ke akhir urutan. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/id/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Menambahkan efek animasi diagram baru untuk kategori atau seri ke akhir urutan. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/id/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Menambahkan efek animasi diagram baru untuk elemen dalam kategori atau seri ke akhir urutan. |
| [`remove(self, item)`](/slides/python-net/id/aspose.slides.animation/sequence/remove/#ieffect) | Menghapus efek yang ditentukan dari koleksi. |
| [`remove_at(self, index)`](/slides/python-net/id/aspose.slides.animation/sequence/remove_at/#int) | Menghapus sebuah efek dari koleksi. |
| [`clear(self)`](/slides/python-net/id/aspose.slides.animation/sequence/clear/#) | Menghapus semua efek dari koleksi. |
| [`remove_by_shape(self, shape)`](/slides/python-net/id/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Menghapus efek untuk shape yang ditentukan. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/id/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Mengembalikan array efek untuk shape yang ditentukan. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/id/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Mengembalikan array efek untuk paragraf yang ditentukan. |
| [`get_count(self, shape)`](/slides/python-net/id/aspose.slides.animation/sequence/get_count/#ishape) | Mengembalikan jumlah efek untuk shape yang ditentukan. |


### Lihat Juga
* modul [`aspose.slides.animation`](/slides/python-net/id/aspose.slides.animation)
* pustaka [`Aspose.Slides`](/slides/python-net)