---
title: ChartCategory class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartcategory/
---
## ChartCategory kelas

Mewakili kategori diagram.

Tipe ChartCategory mengekspos anggota-anggota berikut:

## Properti

| Property | Deskripsi |
| :- | :- |
| [`use_cell`](/slides/python-net/id/aspose.slides.charts/chartcategory/use_cell/) | If true then AsCell property is actual. In other words, worksheet is used for <br/>            storing category (this case supports a multi-level category).<br/>            If false then AsLiteral property is actual. In other words, worksheet is NOT used <br/>            for storing category (and this case doesn't support a multi-level categories).<br/>            Baca-saja **bool**. |
| [`as_cell`](/slides/python-net/id/aspose.slides.charts/chartcategory/as_cell/) | Mengembalikan atau mengatur objek IChartDataCell.<br/>            Jika kategori multi-level maka menggunakan objek IChartDataCell untuk level "0".<br/>            Baca/tulis [`IChartDataCell`](/slides/python-net/id/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/id/aspose.slides.charts/chartcategory/as_literal/) | Mengembalikan atau mengatur objek AsLiteral.<br/>            Baca/tulis **any**. |
| [`value`](/slides/python-net/id/aspose.slides.charts/chartcategory/value/) | Jika UseCell true maka properti ini mewakili properti AsCell.Value.<br/>            Jika UseCell false maka properti ini mewakili properti AsLiteral.<br/>            Baca/tulis **any**. |
| [`grouping_levels`](/slides/python-net/id/aspose.slides.charts/chartcategory/grouping_levels/) | Kontainer yang dikelola dari nilai-nilai level pengelompokan kategori diagram.<br/>            Kategori multi-level berisi lebih dari satu level pengelompokan.<br/>            Pengindeksan level pengelompokan berbasis nol.<br/>            Baca-saja [`IChartCategoryLevelsManager`](/slides/python-net/id/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/id/aspose.slides.charts/chartcategory/cached_value/) | Mendapatkan nilai cache dari kategori diagram.<br/>            Baca-saja [`ICachedChartValue`](/slides/python-net/id/aspose.slides.charts/icachedchartvalue). |

## Metode

| Method | Deskripsi |
| :- | :- |
| [`remove(self)`](/slides/python-net/id/aspose.slides.charts/chartcategory/remove/#) | Menghapus kategori dari diagram. |


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)