---
title: IChartSeries
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mewakili sebuah seri diagram.
type: docs
weight: 1910
url: /id/aspose.slides.charts/ichartseries/
---
## IChartSeries antarmuka

Mewakili satu seri diagram.

```csharp
public interface IChartSeries : IChartComponent
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Memungkinkan untuk mendapatkan antarmuka IChartComponent dasar. Hanya Baca [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Menentukan bentuk seri pada diagram batang 3-D. Mengubah nilai properti ini dapat menyebabkan tipe seri berubah secara otomatis. Baca/Tulis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeRepresentation Baca/Tulis untuk mengubah nilai. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 hingga 300 persen dari ukuran default). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.BubbleSizeScale Baca/Tulis untuk mengubah nilai. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Mengembalikan koleksi titik data pada seri ini. Hanya Baca [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Menentukan ukuran lubang pada diagram donat (dapat antara 10 hingga 90 persen dari ukuran area plot). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.DoughnutHoleSize Baca/Tulis untuk mengubah nilai. Hanya Baca Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Mewakili ErrorBars seri dengan arah X. ErrorBars dengan arah X tersedia untuk seri tipe area, bar, scatter, dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai khusus gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Hanya Baca [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Mewakili ErrorBars seri dengan arah Y. ErrorBars dengan arah Y tersedia untuk seri tipe area, bar, line, scatter, dan bubble. Untuk tipe diagram lain properti ini mengembalikan null (termasuk diagram 3D). Jika menggunakan nilai khusus gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Hanya Baca [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Jarak irisan pai terbuka dari pusat diagram pai diekspresikan sebagai persentase dari diameter pai. Baca/Tulis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Menentukan sudut irisan pertama pada diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 sampai 360 derajat). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.FirstSliceAngle Baca/Tulis untuk mengubah nilai. Hanya Baca UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Mengembalikan format seri. Hanya Baca [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antar data seri dalam diagram 3D. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapDepth Baca/Tulis untuk mengubah nilai. Hanya Baca Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Menentukan ruang antara kelompok batang atau kolom, sebagai persentase lebar batang atau kolom. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.GapWidth Baca/Tulis untuk mengubah nilai. Hanya Baca Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Menentukan apakah ada garis seri untuk seri ini dan seri terkait. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.HasSeriesLines Baca/Tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.SeriesLinesFormat untuk format garis seri. Hanya Baca Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Menentukan apakah diagram Garis atau Stok memiliki bar naik/turun. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.UpDownBars.HasUpDownBars Baca/Tulis untuk mengubah nilai. Gunakan properti ParentSeriesGroup.UpDownBars untuk format bar naik/turun. Hanya Baca Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Menentukan warna solid terbalik untuk seri. Untuk menerapkan pengaturan warna atur FillType format seri menjadi FillType.Solid. Baca/Tulis [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Menentukan apakah seri batang, kolom, atau gelembung harus membalik warnanya jika nilainya negatif. Baca/Tulis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – ini merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.IsColorVaried Baca/Tulis untuk mengubah nilai. Hanya Baca Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Mengembalikan Labels suatu seri. Hanya Baca [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Mengembalikan penanda seri. Hanya Baca [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Mengembalikan nama seri. Hanya Baca [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Mengembalikan atau mengatur format angka untuk ukuran gelembung seri. Baca/Tulis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Mengembalikan atau mengatur format angka untuk nilai seri. Baca/Tulis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Mengembalikan atau mengatur format angka untuk nilai x seri. Baca/Tulis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Mengembalikan atau mengatur format angka untuk nilai y seri. Baca/Tulis String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Mengembalikan urutan seri. Baca/Tulis Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Menentukan seberapa banyak batang dan kolom saling tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – merupakan proyeksi properti grup yang sesuai, sehingga properti ini Hanya Baca. Untuk mengubah nilai, gunakan properti ParentSeriesGroup.Overlap Baca/Tulis. Hanya Baca SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Mewakili tata letak label kategori induk. Hanya berlaku untuk diagram Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Mengembalikan grup seri induk. Hanya Baca [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitBy Baca/Tulis untuk mengubah nilai. Hanya Baca [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Informasi pemisahan khusus untuk diagram pie-of-pie atau bar-of-pie dengan pemisahan khusus. Berisi titik data yang akan digambar pada pai atau batang kedua dalam diagram tersebut. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – merupakan proyeksi properti grup yang sesuai. Hanya Baca [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Menentukan nilai yang digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.PieSplitPosition Baca/Tulis untuk mengubah nilai. Hanya Baca Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Menunjukkan apakah seri ini diplot pada sumbu nilai kedua. Baca/Tulis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Mewakili metode kuartil. Hanya berlaku untuk diagram BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Mewakili entri legenda yang terkait dengan seri ini. Hanya Baca [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (dapat antara 5 hingga 200 persen). Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk – merupakan proyeksi properti grup yang sesuai. Sehingga properti ini Hanya Baca. Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk. Gunakan properti ParentSeriesGroup.SecondPieSize Baca/Tulis untuk mengubah nilai. Hanya Baca UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Mewakili garis konektor. Hanya berlaku untuk diagram Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Mewakili titik dalam. True jika titik dalam ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/Tulis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Mewakili penanda mean. True jika garis mean ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/Tulis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Mewakili penanda mean. True jika penanda mean ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/Tulis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Mewakili titik outlier. True jika titik outlier ditampilkan pada diagram BoxAndWhisker. Hanya berlaku untuk diagram BoxAndWhisker. Baca/Tulis Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Mewakili penghalusan kurva. True jika penghalusan kurva diaktifkan untuk diagram garis atau scatter. Hanya berlaku untuk diagram garis dan scatter yang terhubung oleh garis. Baca/Tulis Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Koleksi garis tren seri. Hanya Baca [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Mengembalikan tipe seri ini. Baca/Tulis [`ChartType`](../charttype). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Mengembalikan warna otomatis untuk seri berdasarkan indeks seri dan gaya diagram. Warna ini digunakan secara default jika FillType bernilai NotDefined. |

### Lihat Juga

* antarmuka [IChartComponent](../ichartcomponent)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->