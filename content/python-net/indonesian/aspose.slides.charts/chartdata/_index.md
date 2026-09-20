---
title: ChartData class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdata/
---
## ChartData kelas

Mewakili data yang digunakan untuk memplot bagan.

Tipe ChartData menyediakan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/id/aspose.slides.charts/chartdata/chart_data_workbook/) | Mendapatkan pabrik sel untuk membuat sel yang digunakan untuk seri atau kategori bagan.<br/>            Baca-saja [`IChartDataWorkbook`](/slides/python-net/id/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/id/aspose.slides.charts/chartdata/series/) | Mendapatkan seri.<br/>            Baca-saja [`IChartSeriesCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/id/aspose.slides.charts/chartdata/series_groups/) | Mendapatkan grup seri.<br/>            Baca-saja [`IChartSeriesGroupCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories/) | Mendapatkan kategori utama (atau baik kategori utama maupun sekunder <br/>            jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai false).<br/>            Baca-saja [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories/) | Jika false maka properti [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) mengembalikan None dan data <br/>            di properti [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) digunakan baik untuk seri utama maupun sekunder.<br/>            Jika true maka data di properti [`ChartData.secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories) digunakan untuk seri sekunder dan data <br/>            di properti [`ChartData.categories`](/slides/python-net/id/aspose.slides.charts/chartdata/categories) digunakan untuk seri utama.<br/>            Baca/tulis **bool**. |
| [`secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/secondary_categories/) | Mendapatkan kategori sekunder jika properti [`ChartData.use_secondary_categories`](/slides/python-net/id/aspose.slides.charts/chartdata/use_secondary_categories) bernilai true.<br/>            Baca-saja [`IChartCategoryCollection`](/slides/python-net/id/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/id/aspose.slides.charts/chartdata/data_source_type/) | Mewakili jalur buku kerja eksternal jika sumber data eksternal, None jika tidak. |
| [`external_workbook_path`](/slides/python-net/id/aspose.slides.charts/chartdata/external_workbook_path/) | Mewakili sumber data bagan. |
| [`embedded_workbook_type`](/slides/python-net/id/aspose.slides.charts/chartdata/embedded_workbook_type/) | Mendapatkan tipe buku kerja yang disematkan.<br/>            Mengembalikan [`WorkbookType.NOT_DEFINED`](/slides/python-net/id/aspose.slides.charts/workbooktype/NOT_DEFINED) jika [`ChartData.data_source_type`](/slides/python-net/id/aspose.slides.charts/chartdata/data_source_type) adalah <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/id/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Baca-saja [`WorkbookType`](/slides/python-net/id/aspose.slides.charts/workbooktype). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/id/aspose.slides.charts/chartdata/set_external_workbook/#str) | Mengatur buku kerja eksternal sebagai sumber data untuk bagan. Data bagan akan diperbarui dari buku kerja target. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/id/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Mengatur buku kerja eksternal sebagai sumber data untuk bagan. |
| [`read_workbook_stream(self)`](/slides/python-net/id/aspose.slides.charts/chartdata/read_workbook_stream/#) | Menulis buku kerja Excel yang tersimpan secara internal ke dalam aliran. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/id/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Menginisialisasi buku kerja Excel yang tersimpan secara internal dengan nilai yang ditentukan pengguna. |
| [`get_range(self)`](/slides/python-net/id/aspose.slides.charts/chartdata/get_range/#) | Mendapatkan rentang data bagan. |
| [`set_range(self, formula)`](/slides/python-net/id/aspose.slides.charts/chartdata/set_range/#str) | Mengatur rentang data bagan. Seri dan kategori akan diperbarui berdasarkan rentang data baru.<br/>            Jika jumlah seri dalam rentang data lebih besar daripada jumlah seri dalam data bagan maka seri tambahan dengan tipe yang sama<br/>            seperti seri terakhir dalam koleksi saat ini akan ditambahkan ke akhir koleksi. |
| [`switch_row_column(self)`](/slides/python-net/id/aspose.slides.charts/chartdata/switch_row_column/#) | Menukar data pada sumbu.<br/>            Data yang dipetakan pada sumbu X akan dipindahkan ke sumbu Y dan sebaliknya. |

### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)