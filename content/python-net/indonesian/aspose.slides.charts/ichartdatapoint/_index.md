---
title: IChartDataPoint class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint kelas

Mewakili titik data seri.

Tipe IChartDataPoint menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`x_value`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/x_value/) | Mengembalikan nilai x dari titik data grafik.<br/>Hanya baca [`IStringOrDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/y_value/) | Mengembalikan nilai y dari titik data grafik.<br/>Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/bubble_size/) | Mengembalikan ukuran gelembung dari titik data grafik.<br/>Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/value/) | Mengembalikan nilai dari titik data grafik.<br/>Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/size_value/) | Mengembalikan nilai ukuran dari titik data grafik.<br/>Digunakan dengan grafik Treemap dan Sunburst.<br/>Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/color_value/) | Mengembalikan nilai warna dari titik data grafik.<br/>Digunakan dengan grafik Peta.<br/>Hanya baca [`IDoubleChartValue`](/slides/python-net/id/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Mewakili nilai batang error seri dalam kasus tipe nilai Custom.<br/>Hanya baca [`IErrorBarsCustomValues`](/slides/python-net/id/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/label/) | Mewakili label titik data grafik.<br/>Hanya baca [`IDataLabel`](/slides/python-net/id/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan.<br/>Baca/tulis **bool**. |
| [`explosion`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/explosion/) | Menentukan jumlah pergeseran titik data dari pusat pai.<br/>Baca/tulis **int**. |
| [`format`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/format/) | Mewakili properti pemformatan.<br/>Baca/tulis [`IFormat`](/slides/python-net/id/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/marker/) | Menentukan penanda data.<br/>Hanya baca [`IMarker`](/slides/python-net/id/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Properti entri legenda yang bersesuaian dalam kasus tipe grafik dari daftar berikut:<br/>ChartType.BarOfPie,<br/>ChartType.ExplodedPie,<br/>ChartType.ExplodedPie3D,<br/>ChartType.Pie,<br/>ChartType.Pie3D,<br/>ChartType.PieOfPie.<br/>Hanya baca [`ILegendEntryProperties`](/slides/python-net/id/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/set_as_total/) | Menetapkan titik data sebagai total. Hanya diterapkan untuk tipe seri Waterfall. |
| [`invert_if_negative`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Menentukan titik data akan membalikkan warnanya jika nilai negatif.<br/>Baca/tulis **bool**. |
| [`data_point_levels`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Mengembalikan kontainer level titik data. Diterapkan untuk seri TreeMap dan Sunburst.<br/>Pengindeksan level titik data berbasis nol. |
| [`index`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/index/) | Menentukan koleksi anak orang tua mana yang berlaku untuk titik data ini.<br/>Baca **int**. |
| [`actual_x`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`remove(self)`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/remove/#) | Menghapus DataPoint dari seri grafik. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/id/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried, dan gaya grafik.<br/>Warna ini digunakan secara default jika FillType bernilai NotDefined. |


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)