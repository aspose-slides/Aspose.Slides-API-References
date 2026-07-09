---
title: IChartSeries
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili seri diagram.
type: docs
weight: 1930
url: /id/aspose.slides.charts/ichartseries/
---
## IChartSeries antarmuka

Mewakili seri diagram.

```csharp
public interface IChartSeries : IChartComponent
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Memungkinkan mendapatkan antarmuka dasar IChartComponent. Hanya-baca [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Menentukan bentuk seri pada diagram batang 3-D. Mengubah nilai properti ini dapat menyebabkan secara otomatis mengubah Tipe seri. Baca/tulis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeRepresentation baca/tulis untuk mengubah nilai. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 dan 300 persen ukuran default). Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeScale baca/tulis untuk mengubah nilai. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Mengembalikan koleksi titik data dari seri ini. Hanya-baca [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Menentukan ukuran lubang pada diagram donat (dapat antara 10 dan 90 persen ukuran area plot). Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.DoughnutHoleSize baca/tulis untuk mengubah nilai. Hanya-baca Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Mewakili ErrorBars seri dengan arah X. ErrorBars dengan arah X tersedia untuk seri tipe area, bar, scatter, dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Hanya-baca [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Mewakili ErrorBars seri dengan arah Y. ErrorBars dengan arah Y tersedia untuk seri tipe area, bar, line, scatter, dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Hanya-baca [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Jarak sebuah irisan pai terbuka dari pusat diagram pai dinyatakan sebagai persentase diameter pai. Baca/tulis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Menentukan sudut irisan pertama pada diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.FirstSliceAngle baca/tulis untuk mengubah nilai. Hanya-baca UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Mengembalikan format sebuah seri. Hanya-baca [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapDepth baca/tulis untuk mengubah nilai. Hanya-baca Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Menentukan ruang antara kumpulan bar atau kolom, sebagai persentase lebar bar atau kolom. Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapWidth baca/tulis untuk mengubah nilai. Hanya-baca Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Menentukan apakah terdapat garis seri untuk seri ini dan seri terkait. Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.HasSeriesLines baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.SeriesLinesFormat untuk format garis seri. Hanya-baca Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Menentukan apakah diagram Garis atau Stok memiliki batang naik/turun. Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.UpDownBars.HasUpDownBars baca/tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.UpDownBars untuk format batang naik/turun. Hanya-baca Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Menentukan warna padat terbalik untuk seri. Untuk menerapkan pengaturan warna, atur FillType format seri ke FillType.Solid. Baca/tulis [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Menentukan apakah seri bar, kolom, atau gelembung harus membalikkan warnanya bila nilai negatif. Baca/tulis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.IsColorVaried baca/tulis untuk mengubah nilai. Hanya-baca Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Mengembalikan Labels sebuah seri. Hanya-baca [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Mengembalikan penanda seri. Hanya-baca [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Mengembalikan nama seri. Hanya-baca [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Mengembalikan atau mengatur format angka untuk ukuran gelembung seri. Baca/tulis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Mengembalikan atau mengatur format angka untuk nilai seri. Baca/tulis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Mengembalikan atau mengatur format angka untuk nilai x seri. Baca/tulis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Mengembalikan atau mengatur format angka untuk nilai y seri. Baca/tulis String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Mengembalikan urutan sebuah seri. Baca/tulis Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Menentukan berapa banyak bar dan kolom tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk. Ini adalah proyeksi properti yang sesuai dalam grup seri induk, sehingga properti ini hanya-baca. Untuk mengubah nilai, gunakan properti ParentSeriesGroup.Overlap baca/tulis. Hanya-baca SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Mewakili tata letak label kategori induk. Hanya berlaku untuk diagram Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Mengembalikan grup seri induk. Hanya-baca [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Menentukan cara menentukan titik data mana yang berada di pai atau bar kedua pada diagram pie-of-pie atau bar-of-pie. Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitBy baca/tulis untuk mengubah nilai. Hanya-baca [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Informasi pemisahan khusus untuk diagram pie-of-pie atau bar-of-pie dengan pemisahan khusus. Berisi titik data yang akan digambar pada pai atau bar kedua dalam diagram pie-of-pie atau bar-of-pie. Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Hanya-baca [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau bar kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitPosition baca/tulis untuk mengubah nilai. Hanya-baca Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Menunjukkan apakah seri ini diplot pada sumbu nilai kedua. Baca/tulis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Mewakili metode kuartil. Hanya berlaku untuk diagram BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Mewakili entri legenda yang terkait dengan seri ini. Hanya-baca [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Menentukan ukuran pai atau bar kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (dapat antara 5 dan 200 persen). Properti ini bukan hanya milik seri ini tetapi semua seri pada grup seri induk — ini adalah proyeksi properti grup yang sesuai. Karena itu properti ini hanya-baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.SecondPieSize baca/tulis untuk mengubah nilai. Hanya-baca UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Mewakili garis penghubung. Hanya berlaku untuk diagram Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Mewakili titik dalam. Benar jika titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Mewakili penanda rata-rata. Benar jika garis rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Mewakili penanda rata-rata. Benar jika penanda rata-rata ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Mewakili titik outlier. Benar jika titik outlier ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/tulis Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Mewakili pelunakan kurva. Benar jika pelunakan kurva diaktifkan untuk diagram garis atau scatter. Hanya berlaku untuk diagram garis dan scatter yang terhubung dengan garis. Baca/tulis Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Koleksi garis tren seri. Hanya-baca [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Mengembalikan tipe seri ini. Baca/tulis [`ChartType`](../charttype). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Mengembalikan warna otomatis untuk seri berdasarkan indeks seri dan gaya diagram. Warna ini digunakan secara default jika FillType sama dengan NotDefined. |

### Lihat Juga

* antarmuka [IChartComponent](../ichartcomponent)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->