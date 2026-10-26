---
title: ChartSeries
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili sebuah seri diagram.
type: docs
weight: 1440
url: /id/aspose.slides.charts/chartseries/
---
## ChartSeries kelas

Mewakili sebuah seri diagram.

```csharp
public class ChartSeries : IChartSeries
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Menentukan bentuk seri pada diagram batang 3-D. Mengubah nilai properti ini dapat menyebabkan perubahan otomatis pada Type seri. Baca/tulis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeRepresentation baca/tulis untuk mengubah nilai. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Menentukan faktor skala untuk diagram gelembung (bisa antara 0 hingga 300 persen ukuran default). Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeScale baca/tulis untuk mengubah nilai. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Mengembalikan diagram induk. Baca-saja [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Mengembalikan koleksi titik data dari seri ini. Baca-saja [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Menentukan ukuran lubang pada diagram donat (bisa antara 10 hingga 90 persen ukuran area plot). Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.DoughnutHoleSize baca/tulis untuk mengubah nilai. Baca-saja Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Mewakili ErrorBars pada seri dengan arah X. ErrorBars dengan arah X tersedia untuk seri tipe area, bar, scatter, dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika nilai khusus gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Baca-saja [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Mewakili ErrorBars pada seri dengan arah Y. ErrorBars dengan arah Y tersedia untuk seri tipe area, bar, line, scatter, dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika nilai khusus gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Baca-saja [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Jarak irisan pai terbuka dari pusat diagram pai dinyatakan sebagai persentase diameter pai. Baca/tulis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Menentukan sudut irisan pertama pada diagram pai atau donat, dalam derajat (searah jarum jam dari atas, 0 hingga 360 derajat). Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.FirstSliceAngle baca/tulis untuk mengubah nilai. Baca-saja UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Mengembalikan format seri. Baca-saja [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapDepth baca/tulis untuk mengubah nilai. Baca-saja Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Menentukan ruang antara klaster batang atau kolom, sebagai persentase lebar batang atau kolom. Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapWidth baca/tulis untuk mengubah nilai. Baca-saja Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Menentukan apakah ada garis seri untuk seri ini dan seri terkait. Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.HasSeriesLines baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.SeriesLinesFormat untuk format garis seri. Baca-saja Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Menentukan apakah diagram Line atau Stock memiliki batang naik/turun. Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.UpDownBars.HasUpDownBars baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.UpDownBars untuk format batang naik/turun. Baca-saja Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Menentukan warna padat terbalik untuk seri. Untuk menerapkan pengaturan warna, set format seri FillType ke FillType.Solid. Baca/tulis [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Menentukan bahwa seri batang, kolom, atau gelembung harus membalik warnanya jika nilai negatif. Baca/tulis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.IsColorVaried baca/tulis untuk mengubah nilai. Baca-saja Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Mengembalikan Labels seri. Baca-saja [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Penanda. Baca-saja [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Mengembalikan nama seri. Baca-saja [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Baca/tulis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Baca/tulis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Baca/tulis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Baca/tulis String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Mengembalikan urutan seri. Baca/tulis Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Menentukan seberapa banyak batang dan kolom tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk. Ini merupakan proyeksi properti yang sesuai dalam grup seri induk, sehingga properti ini baca-saja. Untuk mengubah nilai, gunakan properti !:ParentSeriesGroup.Overlap baca/tulis. Baca-saja SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Mewakili tata letak label kategori induk. Hanya berlaku pada diagram Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Baca-saja [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitBy baca/tulis untuk mengubah nilai. Baca-saja [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Informasi pemisahan khusus untuk diagram pie-of-pie atau bar-of-pie dengan pemisahan khusus. Berisi titik data yang akan digambar pada pai atau batang kedua dalam diagram pie-of-pie atau bar-of-pie. Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Baca-saja [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersamaan dengan properti PieSplitBy. Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitPosition baca/tulis untuk mengubah nilai. Baca-saja Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Menunjukkan apakah seri ini diplot pada sumbu sekunder. Baca/tulis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Mewakili metode kuartil. Hanya berlaku pada diagram BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Mewakili entri legenda yang terkait dengan seri ini. Baca-saja [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Menentukan ukuran pie atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pie pertama (bisa antara 5 hingga 200 persen). Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Karena itu properti ini baca-saja. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.SecondPieSize baca/tulis untuk mengubah nilai. Baca-saja UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Mewakili garis penghubung. Hanya berlaku pada diagram Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Mewakili titik dalam. True jika titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku pada diagram BoxAndWhisker. Baca/tulis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Mewakili garis rata-rata. True jika garis rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku pada diagram BoxAndWhisker. Baca/tulis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Mewakili penanda rata-rata. True jika penanda rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku pada diagram BoxAndWhisker. Baca/tulis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Mewakili titik pencilan. True jika titik pencilan ditampilkan pada diagram BoxAndWhisker. Hanya berlaku pada diagram BoxAndWhisker. Baca/tulis Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Mewakili pelicinan kurva. True jika pelicinan kurva diaktifkan untuk diagram garis atau scatter. Hanya berlaku pada diagram garis dan scatter yang terhubung oleh garis. Baca/tulis Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Koleksi garis tren seri. Baca-saja [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Mengembalikan tipe seri ini. Baca/tulis [`ChartType`](../charttype). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Mengembalikan warna otomatis seri berdasarkan indeks seri dan gaya diagram. Warna ini digunakan secara default jika FillType sama dengan NotDefined. |

### Lihat Juga

* antarmuka [IChartSeries](../ichartseries)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->