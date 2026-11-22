---
title: DataLabelCollection class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection kelas

Mewakili label seri.

Tipe DataLabelCollection mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`chart`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/chart/) | Mengembalikan chart induk.<br/>            Baca-saja [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/is_visible/) | False berarti label data tidak terlihat secara default (and so all <br/>            Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false).<br/>            Baca-saja **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Mendapatkan jumlah label data yang terlihat dalam koleksi.<br/>            Baca-saja **int**. |
| [`count`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/count/) | Mendapatkan jumlah semua label data dalam koleksi.<br/>            Baca-saja **int**. |
| [`default_data_label_format`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Mendapatkan format label data default.<br/>            Baca-saja [`IDataLabelFormat`](/slides/python-net/id/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Mewakili format garis pemimpin label data.<br/>             Baca-saja [`IChartLinesFormat`](/slides/python-net/id/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/parent_series/) | Mendapatkan seri induk.<br/>            Baca-saja [`IChartSeries`](/slides/python-net/id/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | Mendapatkan atau mengatur tipe bentuk default untuk label data.<br/>             Mengembalikan [`ShapeType.NOT_DEFINED`](/slides/python-net/id/aspose.slides/shapetype/NOT_DEFINED) jika tidak ada bentuk yang didefinisikan. |
| [`slide`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/presentation/) |  |

Mendapatkan label data untuk titik data dengan indeks yang ditentukan.

## Pengindeks

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`hide(self)`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/hide/#) | Membuat label data tersembunyi secara default dengan mengatur semua Show*-flags (ShowValue, ...) of the <br/>            DefaultDataLabelFormat property to false state.<br/>            IsVisible akan menjadi false setelah ini. |
| [`index_of(self, value)`](/slides/python-net/id/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Mengembalikan indeks dari DataLabel yang ditentukan dalam koleksi. |


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)