---
title: ChartDataPoint
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili titik data seri.
type: docs
weight: 1330
url: /id/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint kelas

Mewakili titik data seri.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Menentukan tinggi aktual elemen bagan. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. Baca Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Menentukan lebar aktual elemen bagan. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. Baca Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Menentukan lokasi x aktual (kiri) elemen bagan relatif terhadap sudut kiri atas bagan. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. Baca Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Menentukan posisi atas aktual elemen bagan relatif terhadap sudut kiri atas bagan. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai aktual. Baca Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Mengembalikan nilai warna titik data bagan. Digunakan dengan bagan Peta. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Mengembalikan wadah tingkat titik data. Diterapkan untuk seri Treeamp dan Sunburst. Pengindeksan tingkat titik data dimulai dari nol. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Mewakili nilai batang kesalahan seri bila tipe nilai Custom. Baca-saja [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Menentukan jumlah pergeseran titik data dari pusat diagram lingkaran. Baca/tulis Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Mewakili properti pemformatan. Baca/tulis [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Menentukan titik data akan membalikkan warnanya jika nilai negatif. Baca/tulis Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan. Baca/tulis Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Baca-saja [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Menentukan penanda data. Baca-saja [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Properti entri legenda yang bersesuaian bila tipe bagan dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Baca-saja [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Menetapkan titik data sebagai total. Hanya diterapkan untuk tipe seri Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Mengembalikan nilai ukuran titik data bagan. Digunakan dengan bagan Treemap dan Sunburst. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Baca-saja [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried, dan gaya bagan. Warna ini digunakan secara default jika FillType bernilai NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Menghapus DataPoint dari seri bagan. |

### Lihat Juga

* antarmuka [IChartDataPoint](../ichartdatapoint)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->