---
title: IChartDataPoint
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mewakili titik data seri.
type: docs
weight: 1840
url: /id/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint antarmuka

Mewakili titik data seri.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Mengembalikan antarmuka IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Mendapatkan ukuran gelembung dari titik data bagan. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Mendapatkan ukuran gelembung yang di-cache dari titik data bagan. Baca-saja [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Mendapatkan nilai yang di-cache dari titik data bagan. Baca-saja [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Mendapatkan nilai X yang di-cache dari titik data bagan. Baca-saja [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Mendapatkan nilai Y yang di-cache dari titik data bagan. Baca-saja [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Mendapatkan nilai warna dari titik data bagan. Digunakan dengan bagan Peta. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Mengembalikan kontainer tingkat titik data. Diterapkan untuk seri Treeamp dan Sunburst. Pengindeksan tingkat titik data berbasis nol. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Mewakili nilai batang kesalahan seri dalam kasus tipe nilai Kustom. Baca-saja [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Menentukan jumlah pergeseran titik data dari pusat pai. Baca/tulis Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Mewakili properti pemformatan. Baca/tulis [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Menentukan koleksi anak orang tua mana yang berlaku untuk titik data ini. Baca UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Menentukan titik data akan membalikkan warnanya jika nilai negatif. Baca/tulis Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan. Baca/tulis Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Mewakili label titik data bagan. Baca-saja [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Menentukan penanda data. Baca-saja [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Properti entri legenda yang sesuai dalam kasus tipe bagan dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Baca-saja [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Mengatur titik data sebagai total. Hanya diterapkan untuk tipe seri Waterfall. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Mendapatkan nilai ukuran dari titik data bagan. Digunakan dengan bagan Treemap dan Sunburst. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Mendapatkan nilai dari titik data bagan. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Mendapatkan nilai x dari titik data bagan. Baca-saja [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Mendapatkan nilai y dari titik data bagan. Baca-saja [`IDoubleChartValue`](../idoublechartvalue). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried, dan gaya bagan. Warna ini digunakan secara default jika FillType bernilai NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Menghapus DataPoint dari seri bagan. |

### Lihat Juga

* antarmuka [IActualLayout](../iactuallayout)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* perakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->