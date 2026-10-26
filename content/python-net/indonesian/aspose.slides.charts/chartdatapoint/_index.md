---
title: ChartDataPoint class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint kelas

Mewakili titik data seri.

Tipe ChartDataPoint menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`x_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Hanya baca [`IStringOrDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/size_value/) | Mengembalikan nilai ukuran titik data diagram.<br/>            Digunakan dengan diagram Treemap dan Sunburst.<br/>            Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/color_value/) | Mengembalikan nilai warna titik data diagram.<br/>            Digunakan dengan diagram Peta.<br/>            Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Mewakili nilai batang kesalahan seri dalam kasus tipe nilai Custom.<br/>            Hanya baca [`IErrorBarsCustomValues`](/slides/python-net/id/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Hanya baca [`IDataLabel`](/slides/python-net/id/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan pada mereka.<br/>            Baca/tulis **bool**. |
| [`explosion`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/explosion/) | Menentukan jumlah pergeseran titik data dari pusat pai.<br/>            Baca/tulis **int**. |
| [`format`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/format/) | Mewakili properti pemformatan.<br/>            Baca/tulis [`IFormat`](/slides/python-net/id/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/marker/) | Menentukan penanda data.<br/>            Hanya baca [`IMarker`](/slides/python-net/id/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/set_as_total/) | Menetapkan titik data sebagai total. Hanya diterapkan untuk tipe seri Waterfall. |
| [`related_legend_entry`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Properti entri legenda yang sesuai dalam kasus tipe diagram dari daftar berikut:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Hanya baca [`ILegendEntryProperties`](/slides/python-net/id/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/data_point_levels/) | Mengembalikan kontainer level titik data. Diterapkan untuk seri Treeamp dan Sunburst.<br/>            Pengindeksan level titik data dimulai dari nol. |
| [`index`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Menentukan bahwa titik data harus membalikkan warnanya jika nilai negatif.<br/>            Baca/tulis **bool**. |
| [`actual_x`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/actual_x/) | Menentukan lokasi x aktual (kiri) elemen diagram relatif terhadap sudut kiri atas diagram.<br/>            Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual.<br/>            Baca **float**. |
| [`actual_y`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/actual_y/) | Menentukan bagian atas aktual elemen diagram relatif terhadap sudut kiri atas diagram.<br/>            Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual.<br/>            Baca **float**. |
| [`actual_width`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/actual_width/) | Menentukan lebar aktual elemen diagram. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual.<br/>            Baca **float**. |
| [`actual_height`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/actual_height/) | Menentukan tinggi aktual elemen diagram. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual.<br/>            Baca **float**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`remove(self)`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/remove/#) | Menghapus DataPoint dari seri diagram. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/id/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried dan gaya diagram.<br/>            Warna ini digunakan secara default jika FillType sama dengan NotDefined. |


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)