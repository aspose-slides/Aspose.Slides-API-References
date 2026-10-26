---
title: ChartCategory class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartcategory/
---
## ChartCategory kelas

Mewakili kategori diagram.

Tipe ChartCategory mengekspos anggota berikut:

## Properti

| Property | Deskripsi |
| :- | :- |
| [`use_cell`](/slides/python-net/id/aspose.slides.charts/chartcategory/use_cell/) | Jika true maka properti AsCell yang sebenarnya. Dengan kata lain, worksheet digunakan untuk <br/> menyimpan kategori (kasus ini mendukung kategori multi-level).<br/> Jika false maka properti AsLiteral yang sebenarnya. Dengan kata lain, worksheet TIDAK digunakan <br/> untuk menyimpan kategori (dan kasus ini tidak mendukung kategori multi-level).<br/> Hanya-baca **bool**. |
| [`as_cell`](/slides/python-net/id/aspose.slides.charts/chartcategory/as_cell/) | Mengembalikan atau mengatur objek IChartDataCell.<br/> Jika kategori multi-level maka menggunakan objek IChartDataCell untuk level "0".<br/> Baca/tulis [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/id/aspose.slides.charts/chartcategory/as_literal/) | Mengembalikan atau mengatur objek AsLiteral.<br/> Baca/tulis **any**. |
| [`value`](/slides/python-net/id/aspose.slides.charts/chartcategory/value/) | Jika UseCell true maka properti ini mewakili properti AsCell.Value.<br/> Jika UseCell false maka properti ini mewakili properti AsLiteral.<br/> Baca/tulis **any**. |
| [`grouping_levels`](/slides/python-net/id/aspose.slides.charts/chartcategory/grouping_levels/) | Kontainer terkelola nilai-nilai tingkat pengelompokan kategori diagram.<br/> Kategori multi-level berisi lebih dari satu tingkat pengelompokan.<br/> Indeks tingkat pengelompokan berbasis nol.<br/> Hanya-baca [`IChartCategoryLevelsManager`](/slides/python-net/id/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`remove(self)`](/slides/python-net/id/aspose.slides.charts/chartcategory/remove/#) | Menghapus kategori dari diagram. |


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)