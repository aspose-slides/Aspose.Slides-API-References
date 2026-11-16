---
title: ChartSeries
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili seri diagram.
type: docs
weight: 1450
url: /id/aspose.slides.charts/chartseries/
---
## ChartSeries kelas

Represents a chart series.

```csharp
public class ChartSeries : IChartSeries
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Menentukan bentuk serangkaian pada diagram batang 3-D. Mengubah nilai properti ini dapat menyebabkan otomatis mengubah Tipe serangkaian. Baca/tulis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.BubbleSizeRepresentation baca/tulis untuk mengubah nilai. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 dan 300 persen ukuran default). Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.BubbleSizeScale baca/tulis untuk mengubah nilai. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Mengembalikan diagram induk. Hanya-baca [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Mengembalikan koleksi titik data dari serangkaian ini. Hanya-baca [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Menentukan ukuran lubang pada diagram donat (dapat antara 10 dan 90 persen ukuran area plot). Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.DoughnutHoleSize baca/tulis untuk mengubah nilai. Hanya-baca Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Mewakili ErrorBars serangkaian dengan arah X. ErrorBars dengan arah X tersedia untuk serangkaian tipe area, bar, scatter dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai kustom gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Hanya-baca [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Mewakili ErrorBars serangkaian dengan arah Y. ErrorBars dengan arah Y tersedia untuk serangkaian tipe area, bar, line, scatter dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai kustom gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Hanya-baca [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Jarak sebuah irisan pai terbuka dari pusat diagram pai diekspresikan sebagai persentase diameter pai. Baca/tulis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Menentukan sudut irisan pertama pada diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.FirstSliceAngle baca/tulis untuk mengubah nilai. Hanya-baca UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Mengembalikan format serangkaian. Hanya-baca [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara serangkaian data dalam diagram 3D. Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.GapDepth baca/tulis untuk mengubah nilai. Hanya-baca Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Menentukan ruang antara kelompok batang atau kolom, sebagai persentase lebar batang atau kolom. Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.GapWidth baca/tulis untuk mengubah nilai. Hanya-baca Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Menentukan apakah ada garis serangkaian untuk serangkaian ini dan serangkaian terkait. Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.HasSeriesLines baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.SeriesLinesFormat untuk format garis serangkaian. Hanya-baca Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Menentukan apakah diagram Garis atau Saham memiliki batang naik/turun. Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.UpDownBars.HasUpDownBars baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.UpDownBars untuk format batang naik/turun. Hanya-baca Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Menentukan warna padat terbalik untuk serangkaian. Untuk menerapkan pengaturan warna, atur format serangkaian FillType menjadi FillType.Solid. Baca/tulis [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Menentukan batang, kolom, atau serangkaian gelembung harus membalik warnanya jika nilai negatif. Baca/tulis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Menentukan bahwa setiap penanda data dalam serangkaian memiliki warna yang berbeda. Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.IsColorVaried baca/tulis untuk mengubah nilai. Hanya-baca Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Mengembalikan Labels dari serangkaian. Hanya-baca [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Penanda. Hanya-baca [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Mengembalikan nama serangkaian. Hanya-baca [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Baca/tulis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Baca/tulis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Baca/tulis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Baca/tulis String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Mengembalikan urutan serangkaian. Baca/tulis Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Menentukan berapa banyak batang dan kolom tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk. Ini merupakan proyeksi properti yang sesuai di grup serangkaian induk, sehingga properti ini hanya-baca. Untuk mengubah nilai, gunakan properti !:ParentSeriesGroup.Overlap baca/tulis. Hanya-baca SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Mewakili tata letak label kategori induk. Hanya berlaku untuk diagram Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Hanya-baca [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.PieSplitBy baca/tulis untuk mengubah nilai. Hanya-baca [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Informasi pembagian khusus untuk diagram pai-dalam-pai atau batang-dalam-pai dengan pembagian khusus. Berisi titik data yang harus digambar pada pai atau batang kedua dalam diagram pai-dalam-pai atau batang-dalam-pai. Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Hanya-baca [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Menentukan nilai yang digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. Digunakan bersama properti PieSplitBy. Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.PieSplitPosition baca/tulis untuk mengubah nilai. Hanya-baca Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Menentukan apakah serangkaian ini dipetakan pada sumbu sekunder. Baca/tulis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Mewakili metode kuartil. Hanya berlaku untuk diagram BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Mewakili entri legenda yang terkait dengan serangkaian ini. Hanya-baca [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Menentukan ukuran pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai, sebagai persentase ukuran pai pertama (dapat antara 5 dan 200 persen). Properti ini bukan hanya milik serangkaian ini tetapi semua serangkaian dalam grup serangkaian induk – ini merupakan proyeksi properti grup yang sesuai. Oleh karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup serangkaian induk. Gunakan properti ParentSeriesGroup.SecondPieSize baca/tulis untuk mengubah nilai. Hanya-baca UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Mewakili garis penghubung. Hanya berlaku untuk diagram Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Mewakili titik dalam. True jika titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Mewakili garis rata-rata. True jika garis rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Mewakili penanda rata-rata. True jika penanda rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Mewakili titik pencilan. True jika titik pencilan ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Mewakili penghalusan kurva. True jika penghalusan kurva diaktifkan untuk diagram garis atau diagram sebar yang terhubung oleh garis. Hanya berlaku untuk diagram garis dan sebar yang terhubung oleh garis. Baca/tulis Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Koleksi garis tren serangkaian. Hanya-baca [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Mengembalikan tipe serangkaian ini. Baca/tulis [`ChartType`](../charttype). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Mengembalikan warna otomatis serangkaian berdasarkan indeks serangkaian dan gaya diagram. Warna ini digunakan secara default jika FillType bernilai NotDefined. |

### Lihat Juga

* antarmuka [IChartSeries](../ichartseries)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->