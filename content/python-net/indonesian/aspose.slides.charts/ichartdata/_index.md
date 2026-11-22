---
title: IChartData class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartdata/
---
## IChartData kelas

Mewakili data yang digunakan untuk memplot diagram.

Tipe IChartData mengekspos anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/id/aspose.slides.charts/ichartdata/chart_data_workbook/) | Mendapatkan pabrik sel untuk membuat sel yang digunakan pada seri atau kategori grafik.<br/>            Hanya-baca [`IChartDataWorkbook`](/slides/python-net/id/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/id/aspose.slides.charts/ichartdata/series/) | Mendapatkan seri.<br/>            Hanya-baca [`IChartSeriesCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/id/aspose.slides.charts/ichartdata/series_groups/) | Mendapatkan grup seri.<br/>            Hanya-baca [`IChartSeriesGroupCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/categories/) | Mendapatkan kategori utama (atau kategori utama dan sekunder <br/>            bila properti [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) bernilai false).<br/>            Hanya-baca [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories/) | Jika false maka properti [`IChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/secondary_categories) mengembalikan None dan data <br/>            pada properti [`IChartData.categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/categories) digunakan untuk seri utama dan sekunder.<br/>            Jika true maka data pada properti [`IChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/secondary_categories) digunakan untuk seri sekunder dan data <br/>            pada properti [`IChartData.categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/categories) digunakan untuk seri utama.<br/>            Baca/tulis **bool**. |
| [`secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/secondary_categories/) | Mendapatkan kategori sekunder bila properti [`IChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/ichartdata/use_secondary_categories) bernilai true.<br/>            Hanya-baca [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/id/aspose.slides.charts/ichartdata/data_source_type/) | Mewakili sumber data diagram |
| [`external_workbook_path`](/slides/python-net/id/aspose.slides.charts/ichartdata/external_workbook_path/) | Mewakili jalur buku kerja eksternal jika sumber data bersifat eksternal, None bila tidak |
| [`embedded_workbook_type`](/slides/python-net/id/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Mendapatkan tipe buku kerja tersemat.<br/>            Mengembalikan [`WorkbookType.NOT_DEFINED`](/slides/python-net/id/aspose.slides.charts/workbooktype/NOT_DEFINED) bila [`IChartData.data_source_type`](/slides/python-net/id/aspose.slides.charts/ichartdata/data_source_type) adalah <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/id/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Hanya-baca [`WorkbookType`](/slides/python-net/id/aspose.slides.charts/workbooktype). |

## Metode

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/id/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Mengatur buku kerja eksternal sebagai sumber data untuk diagram. Data diagram akan diperbarui dari buku kerja target. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/id/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Mengatur buku kerja eksternal sebagai sumber data untuk diagram. |
| [`read_workbook_stream(self)`](/slides/python-net/id/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Menulis buku kerja Excel yang terkandung secara internal ke dalam aliran memori. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/id/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Menginisialisasi buku kerja Excel yang terkandung secara internal dengan nilai yang ditentukan pengguna. |
| [`set_range(self, formula)`](/slides/python-net/id/aspose.slides.charts/ichartdata/set_range/#str) | Mengatur rentang data diagram. Seri dan kategori akan diperbarui berdasarkan rentang data baru.<br/>            Jika jumlah seri dalam rentang data lebih besar daripada jumlah seri dalam data diagram, maka seri tambahan dengan tipe yang sama<br/>            dengan seri terakhir dalam koleksi saat ini akan ditambahkan ke akhir koleksi. |
| [`get_range(self)`](/slides/python-net/id/aspose.slides.charts/ichartdata/get_range/#) | Mendapatkan rentang data diagram. |
| [`switch_row_column(self)`](/slides/python-net/id/aspose.slides.charts/ichartdata/switch_row_column/#) | Menukar data pada sumbu.<br/>            Data yang dipetakan pada sumbu X akan dipindahkan ke sumbu Y dan sebaliknya. |
| [`refresh_data(self)`](/slides/python-net/id/aspose.slides.charts/ichartdata/refresh_data/#) | Menyegarkan data diagram dengan memuat ulangnya dari buku kerja sumber. |


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)