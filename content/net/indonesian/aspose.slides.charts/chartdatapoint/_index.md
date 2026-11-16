---
title: ChartDataPoint
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili titik data seri.
type: docs
weight: 1340
url: /id/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint kelas

Represents series data point.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Menentukan tinggi sebenarnya dari elemen chart. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Menentukan lebar sebenarnya dari elemen chart. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Menentukan lokasi x sebenarnya (kiri) dari elemen chart relatif terhadap sudut kiri atas chart. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Menentukan posisi atas sebenarnya dari elemen chart relatif terhadap sudut kiri atas chart. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk mendapatkan nilai sebenarnya. Baca Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Hanya-baca [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Mendapatkan ukuran gelembung cache dari titik data chart. Hanya-baca [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Mendapatkan nilai cache dari titik data chart. Hanya-baca [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Mendapatkan nilai X cache dari titik data chart. Hanya-baca [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Mendapatkan nilai Y cache dari titik data chart. Hanya-baca [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Mengembalikan nilai warna dari titik data chart. Digunakan dengan diagram Peta. Hanya-baca [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Mengembalikan kontainer level titik data. Diterapkan untuk seri Treeamp dan Sunburst. Pengindeksan level titik data berbasis nol. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Mewakili nilai batang kesalahan seri dalam kasus tipe nilai Custom. Hanya-baca [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Menentukan jumlah perpindahan titik data dari pusat pai. Baca/tulis Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Mewakili properti pemformatan. Baca/tulis [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Menentukan titik data akan membalikkan warnanya jika nilai negatif. Baca/tulis Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan. Baca/tulis Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Hanya-baca [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Menentukan penanda data. Hanya-baca [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Properti entri legenda yang sesuai dalam kasus tipe chart dari daftar ini: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Hanya-baca [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Menetapkan titik data sebagai total. Diterapkan hanya untuk tipe seri Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Mengembalikan nilai ukuran dari titik data chart. Digunakan dengan diagram Treemap dan Sunburst. Hanya-baca [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Hanya-baca [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Hanya-baca [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Hanya-baca [`IDoubleChartValue`](../idoublechartvalue). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried dan gaya chart. Warna ini digunakan secara default jika FillType sama dengan NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Menghapus DataPoint dari seri chart. |

### Lihat Juga

* antarmuka [IChartDataPoint](../ichartdatapoint)
* ruangnama [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->