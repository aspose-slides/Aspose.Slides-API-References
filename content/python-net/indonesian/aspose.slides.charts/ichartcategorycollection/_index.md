---
title: IChartCategoryCollection class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection kelas

Mewakili koleksi [`IChartCategory`](/slides/python-net/id/aspose.slides.charts/ichartcategory)

Tipe IChartCategoryCollection mengekspos anggota-anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`use_cells`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection/use_cells/) | Jika true maka worksheet digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level).<br/>            Jika false maka worksheet TIDAK digunakan untuk menyimpan nilai (dan kasus ini tidak mendukung <br/>            kategori multi-level).<br/>            Baca/tulis **bool**. |
| [`grouping_level_count`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Mengembalikan jumlah tingkat pengelompokan kategori yang digunakan.<br/>            Lebih dari satu untuk kategori multi-level.<br/>            Baca-saja **int**. |

Mendapatkan elemen pada indeks yang ditentukan.

## Pengindeks

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Metode

| Method | Description |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Jika kategori ada dalam koleksi, kembalikan. Jika tidak, buat kategori chart baru dari [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell) dan tambahkan ke koleksi. |
| [`add(self, value)`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection/add/#any) | Membuat [`IChartCategory`](/slides/python-net/id/aspose.slides.charts/ichartcategory) baru dari nilai dan menambahkannya ke koleksi. |
| [`index_of(self, value)`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Mencari [`IChartCategory`](/slides/python-net/id/aspose.slides.charts/ichartcategory) yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama dalam seluruh Collection |
| [`remove(self, value)`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Menghapus nilai yang ditentukan. |
| [`remove_at(self, index)`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Menghapus elemen pada indeks yang diberikan. |
| [`clear(self)`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection/clear/#) | Menghapus semua elemen dari koleksi. |


### Lihat Juga
* kelas [`IChartCategory`](/slides/python-net/id/aspose.slides.charts/ichartcategory)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)