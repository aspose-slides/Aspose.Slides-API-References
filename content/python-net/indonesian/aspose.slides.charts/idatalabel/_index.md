---
title: IDataLabel class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/idatalabel/
---
## IDataLabel kelas

Mewakili label seri.

Tipe IDataLabel mengungkapkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_visible`](/slides/python-net/id/aspose.slides.charts/idatalabel/is_visible/) | False berarti label data tidak terlihat (dan sehingga semua Show*-flags (ShowValue, ...) menjadi false).<br/>            Read-only **bool**. |
| [`data_label_format`](/slides/python-net/id/aspose.slides.charts/idatalabel/data_label_format/) | Mengembalikan format label data.<br/>            Read-only [`IDataLabelFormat`](/slides/python-net/id/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/id/aspose.slides.charts/idatalabel/value_from_cell/) | Mendapatkan atau mengatur sel data buku kerja. Diterapkan jika IDataLabelFormat.ShowLabelValueFromCell properti bernilai true. |
| [`label_shape_type`](/slides/python-net/id/aspose.slides.charts/idatalabel/label_shape_type/) | Mendapatkan atau mengatur tipe bentuk label data.<br/>            Mengembalikan [`ShapeType.NOT_DEFINED`](/slides/python-net/id/aspose.slides/shapetype/NOT_DEFINED) jika tidak ada bentuk yang ditentukan. |
| [`x`](/slides/python-net/id/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/id/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/id/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/id/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/id/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/id/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/id/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/id/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/id/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/id/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/id/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/id/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/id/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/id/aspose.slides.charts/idatalabel/actual_height/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`hide(self)`](/slides/python-net/id/aspose.slides.charts/idatalabel/hide/#) | Menyembunyikan label data dengan mengatur semua Show*-flags (ShowValue, ...) ke keadaan false.<br/>            IsVisible akan menjadi false setelah ini. |
| [`get_actual_label_text(self)`](/slides/python-net/id/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Mengembalikan teks label aktual berdasarkan pengaturan DataLabelFormat atau nilai TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/id/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)