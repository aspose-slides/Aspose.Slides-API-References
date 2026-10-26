---
title: IChartCategory class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartcategory/
---
## IChartCategory kelas

Mewakili kategori diagram.

Tipe IChartCategory mengekspos anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`use_cell`](/slides/python-net/id/aspose.slides.charts/ichartcategory/use_cell/) | Jika true maka AsCell property yang sebenarnya. Dengan kata lain, worksheet digunakan untuk <br/>            menyimpan kategori (kasus ini mendukung kategori multi-level).<br/>            Jika false maka AsLiteral property yang sebenarnya. Dengan kata lain, worksheet TIDAK digunakan <br/>            untuk menyimpan kategori (dan kasus ini tidak mendukung kategori multi-level).<br/>            Hanya baca **bool**. |
| [`as_cell`](/slides/python-net/id/aspose.slides.charts/ichartcategory/as_cell/) | Mengembalikan atau mengatur objek IChartDataCell.<br/>            Jika kategori multi-level maka menggunakan objek IChartDataCell untuk level "0".<br/>            Baca/tulis [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/id/aspose.slides.charts/ichartcategory/as_literal/) | Mengembalikan atau mengatur AsLiteral jika UseCell false.<br/>            Baca/tulis **any**. |
| [`value`](/slides/python-net/id/aspose.slides.charts/ichartcategory/value/) | Jika UseCell true maka properti ini mewakili AsCell.Value property.<br/>            Jika UseCell false maka properti ini mewakili AsLiteral property.<br/>            Baca/tulis **any**. |
| [`grouping_levels`](/slides/python-net/id/aspose.slides.charts/ichartcategory/grouping_levels/) | Kontainer terkelola dari nilai-nilai level pengelompokan kategori diagram.<br/>            Kategori multi-level berisi lebih dari satu level pengelompokan.<br/>            Pengindeksan level pengelompokan berbasis nol.<br/>            Hanya baca [`IChartCategoryLevelsManager`](/slides/python-net/id/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`remove(self)`](/slides/python-net/id/aspose.slides.charts/ichartcategory/remove/#) | Menghapus kategori dari diagram. |


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)