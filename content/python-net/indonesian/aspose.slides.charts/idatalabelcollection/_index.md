---
title: IDataLabelCollection class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection kelas

Mewakili label seri.

Tipe IDataLabelCollection mengekspos anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Mengembalikan format default semua label data dalam koleksi.<br/>            Hanya-baca [`IDataLabelFormat`](/slides/python-net/id/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Mewakili format garis pemimpin label data.<br/>             Hanya-baca [`IChartLinesFormat`](/slides/python-net/id/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/is_visible/) | False berarti bahwa label data tidak terlihat secara default (dan sehingga semua <br/>            Show*-flags (ShowValue, ...) dari properti DefaultDataLabelFormat adalah false).<br/>            Hanya-baca **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Mendapatkan jumlah label data yang terlihat dalam koleksi.<br/>            Hanya-baca **int**. |
| [`count`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/count/) | Mendapatkan jumlah semua label data dalam koleksi.<br/>            Hanya-baca **int**. |
| [`parent_series`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/parent_series/) | Mengembalikan seri grafik induk.<br/>            Hanya-baca [`IChartSeries`](/slides/python-net/id/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Mendapatkan atau mengatur tipe bentuk default untuk label data.<br/>             Mengembalikan [`ShapeType.NOT_DEFINED`](/slides/python-net/id/aspose.slides/shapetype/NOT_DEFINED) jika tidak ada bentuk yang ditentukan. |
| [`chart`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Mendapatkan label data untuk titik data dengan indeks yang ditentukan.

## Pengindeks

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`hide(self)`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/hide/#) | Membuat label data tersembunyi secara default dengan mengatur semua Show*-flags (ShowValue, ...) dari <br/>            properti DefaultDataLabelFormat ke keadaan false.<br/>            IsVisible akan menjadi false setelah ini. |
| [`index_of(self, value)`](/slides/python-net/id/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Mengembalikan indeks dari DataLabel yang ditentukan dalam koleksi. |

### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)