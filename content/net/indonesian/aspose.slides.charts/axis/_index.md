---
title: Axis
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mengenkapsulkan objek yang mewakili sumbu diagram.
type: docs
weight: 1180
url: /id/aspose.slides.charts/axis/
---
## Axis kelas

Encapsulates the object that represents a chart's axis.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Menentukan satuan utama aktual sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Menentukan skala satuan utama aktual sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Menentukan nilai maksimum aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Menentukan satuan minor aktual sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Menentukan skala satuan minor aktual sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Menentukan nilai minimum aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Mewakili tipe agregasi sumbu kategori (pengelompokan). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk diagram 3-D. Baca/tulis Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Menentukan satuan waktu terkecil yang direpresentasikan pada sumbu tanggal. Baca/tulis [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Menentukan lebar bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByBinWidth. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Menentukan tipe sumbu kategori. Baca/tulis [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Mengembalikan chart induk. Hanya baca [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Mewakili titik pada sumbu dimana sumbu tegak lurus melintasinya. Baca/tulis Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Mewakili CrossType pada sumbu yang ditentukan dimana sumbu lain melintasinya. Baca/tulis [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Menentukan nilai skala satuan tampilan untuk sumbu nilai. Baca/tulis [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Mewakili format sumbu. Hanya baca [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Menentukan apakah sumbu memiliki judul yang terlihat. Baca/tulis Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Menunjukkan apakah satuan utama sumbu ditetapkan secara otomatis. Baca/tulis Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Menunjukkan apakah nilai maksimum ditetapkan secara otomatis. Baca/tulis Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Menunjukkan apakah satuan minor sumbu ditetapkan secara otomatis. Baca/tulis Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Menunjukkan apakah nilai minimum ditetapkan secara otomatis. Baca/tulis Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Menentukan nilai spasi label tick otomatis. Jika false: gunakan properti TickLabelSpacing. Baca/tulis Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Menentukan nilai spasi tanda centang otomatis. Jika false: gunakan properti TickMarksSpacing. Baca/tulis Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. Baca/tulis Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Menunjukkan apakah format terhubung ke data sumber. Baca/tulis Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Mewakili apakah MS PowerPoint memplot titik data dari terakhir ke pertama. Baca/tulis Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Mewakili apakah sumbu terlihat. Baca/tulis Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca/tulis UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Mewakili basis logaritma. Nilai default adalah 10. Baca/tulis Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Mewakili format garis kisi utama pada sumbu chart. Hanya baca [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Mewakili tipe tanda centang utama untuk sumbu yang ditentukan. Baca/tulis [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Mewakili satuan utama untuk sumbu tanggal atau nilai. Baca/tulis Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Mewakili skala satuan utama untuk sumbu tanggal. Baca/tulis [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Mewakili nilai maksimum pada sumbu nilai. Baca/tulis Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Mewakili format garis kisi minor pada sumbu chart. Hanya baca [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Mewakili tipe tanda centang minor untuk sumbu yang ditentukan. Baca/tulis [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Mewakili satuan minor untuk sumbu tanggal atau nilai. Baca/tulis Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Mewakili skala satuan utama untuk sumbu tanggal. Baca/tulis [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Mewakili nilai minimum pada sumbu nilai. Baca/tulis Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Mewakili string format untuk Label Sumbu. Baca/tulis String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Menentukan jumlah bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByNumberOfBins. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Menentukan nilai khusus bin overflow. Diterapkan ketika properti IsAutomaticOverflowBin diatur ke false dan properti IsOverflowBin bernilai true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Mewakili posisi sumbu. Baca/tulis [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Untuk menyembunyikan garis kisi utama, atur MajorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. Hanya baca Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Untuk menyembunyikan garis kisi minor, atur MinorGridLinesFormat.Line.FillFormat.FillType ke FillType.NoFill. Hanya baca Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Mewakili format teks. Hanya baca [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Mewakili posisi label tanda centang pada sumbu yang ditentukan. Baca/tulis [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Mewakili sudut rotasi label tick. Baca/tulis Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Menentukan berapa banyak label tick yang dilewati di antara label yang digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Menentukan berapa banyak tanda centang yang harus dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Mendapatkan judul sumbu. Hanya baca [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Menentukan nilai khusus bin underflow. Diterapkan ketika properti IsAutomaticUnderflowBin diatur ke false dan properti IsUnderflowBin bernilai true. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Mengatur properti IAxis.CategoryAxisType dengan nilai yang ditentukan secara otomatis berdasarkan data sumbu. |

### Lihat Juga

* kelas [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* kelas [AxesManager](../axesmanager)
* antarmuka [IAxis](../iaxis)
* ruangnama [Aspose.Slides.Charts](../../aspose.slides.charts)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->