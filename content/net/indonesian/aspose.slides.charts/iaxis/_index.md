---
title: IAxis
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mengkapsulkan objek yang mewakili sumbu grafik.
type: docs
weight: 1720
url: /id/aspose.slides.charts/iaxis/
---
## IAxis antarmuka

Mengkapsulkan objek yang mewakili sumbu grafik.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Properti

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Menentukan unit mayor aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Menentukan skala unit mayor aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Menentukan nilai maksimum aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Menentukan unit minor aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Menentukan skala unit minor aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Menentukan nilai minimum aktual pada sumbu. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Mewakili tipe agregasi sumbu kategori (pembinningan). Diterapkan pada kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Mengizinkan untuk mendapatkan antarmuka dasar IFormattedTextContainer. Baca-saja [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Mewakili apakah sumbu nilai melintasi sumbu kategori di antara kategori. Properti ini hanya berlaku untuk sumbu kategori, dan tidak berlaku untuk grafik 3-D. Baca/tulis Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Menentukan unit waktu terkecil yang direpresentasikan pada sumbu tanggal. Baca/tulis [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Menentukan lebar bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByBinWidth. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Menentukan tipe sumbu kategori. Baca/tulis [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Mewakili titik pada sumbu di mana sumbu tegak lurus melintasinya. Baca/tulis Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Mewakili CrossType pada sumbu yang ditentukan di mana sumbu lain melintasinya. Baca/tulis [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Menentukan nilai skala unit tampilan untuk sumbu nilai. Baca/tulis [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Mewakili format sumbu. Baca-saja [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Menentukan apakah sumbu memiliki judul yang terlihat. Baca/tulis Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Menunjukkan apakah unit mayor sumbu secara otomatis ditetapkan. Baca/tulis Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Menunjukkan apakah nilai maksimum secara otomatis ditetapkan. Baca/tulis Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Menunjukkan apakah unit minor sumbu secara otomatis ditetapkan. Baca/tulis Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Menunjukkan apakah nilai minimum secara otomatis ditetapkan. Baca/tulis Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Menentukan nilai bin overflow otomatis. Jika false: gunakan properti OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Menentukan nilai jarak spasi label tick otomatis. Jika false: gunakan properti TickLabelSpacing. Baca/tulis Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Menentukan nilai jarak spasi tanda tick otomatis. Jika false: gunakan properti TickMarksSpacing. Baca/tulis Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Menentukan nilai bin underflow otomatis. Jika false: gunakan properti UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Mewakili apakah tipe skala sumbu nilai logaritmik atau tidak. Baca/tulis Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Menunjukkan apakah format tersebut terhubung ke data sumber. Baca/tulis Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Menentukan apakah bin overflow diterapkan. Gunakan IsAutomaticOverflowBin dan OverflowBin untuk menyesuaikan nilai bin overflow. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Mewakili apakah MS PowerPoint memplot titik data dari akhir ke awal. Baca/tulis Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Menentukan apakah bin underflow diterapkan. Gunakan IsAutomaticUnderflowBin dan UnderflowBin untuk menyesuaikan nilai bin underflow. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Mewakili apakah sumbu terlihat. Baca/tulis Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Menentukan jarak label dari sumbu. Diterapkan pada sumbu kategori atau tanggal. Nilai harus antara 0% dan 1000%. Baca/tulis UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Mewakili basis logaritmik. Nilai default adalah 10. Baca/tulis Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Mewakili format garis kisi mayor pada sumbu grafik. Baca-saja [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Mewakili tipe tanda tick mayor untuk sumbu yang ditentukan. Baca/tulis [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Mewakili unit mayor untuk sumbu tanggal atau nilai. Baca/tulis Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Mewakili skala unit mayor untuk sumbu tanggal. Baca/tulis [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Mewakili nilai maksimum pada sumbu nilai. Baca/tulis Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Mewakili format garis kisi minor pada sumbu grafik. Baca-saja [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Mewakili tipe tanda tick minor untuk sumbu yang ditentukan. Baca/tulis [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Mewakili unit minor untuk sumbu tanggal atau nilai. Baca/tulis Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Mewakili skala unit mayor untuk sumbu tanggal. Baca/tulis [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Mewakili nilai minimum pada sumbu nilai. Baca/tulis Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Mewakili string format untuk Label Sumbu. Baca/tulis String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Menentukan jumlah bin ketika nilai properti AggregationType diatur ke AxisAggregationType.ByNumberOfBins. Diterapkan pada sumbu kategori. Hanya digunakan dengan seri Histogram atau HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Menentukan nilai khusus bin overflow. Diterapkan ketika properti IsAutomaticOverflowBin diatur ke false dan properti IsOverflowBin bernilai true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Mewakili posisi sumbu. Baca/tulis [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Mewakili apakah garis kisi mayor ditampilkan. Baca-saja Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Mewakili apakah garis kisi minor ditampilkan. Baca-saja Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Mewakili posisi label tanda tick pada sumbu yang ditentukan. Baca/tulis [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Mewakili sudut rotasi label tick. Baca/tulis Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Menentukan berapa banyak label tick yang dilewati antara label yang digambar. Baca/tulis UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Menentukan berapa banyak tanda tick yang harus dilewati sebelum yang berikutnya digambar. Diterapkan pada sumbu kategori atau seri. Baca/tulis UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Mengambil judul sumbu. Baca-saja [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Menentukan nilai khusus bin underflow. Diterapkan ketika properti IsAutomaticUnderflowBin diatur ke false dan properti IsUnderflowBin bernilai true. |

## Metode

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Mengatur properti IAxis.CategoryAxisType dengan nilai yang secara otomatis ditentukan berdasarkan data sumbu. |

### Lihat Juga

* antarmuka [IFormattedTextContainer](../iformattedtextcontainer)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->