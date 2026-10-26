---
title: IChartSeriesGroup
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili grup seri.
type: docs
weight: 1950
url: /id/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup antarmuka

Mewakili grup seri.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Mengizinkan untuk mendapatkan antarmuka dasar IChartComponent. Baca-saja [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Baca/tulis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Menentukan faktor skala untuk diagram gelembung (dapat berada antara 0 hingga 300 persen ukuran default). Baca/tulis Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Menentukan ukuran lubang pada diagram donat (dapat berada antara 10 hingga 90 persen ukuran area plot). Baca/tulis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Mendapatkan atau menetapkan sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Baca/tulis UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Mengembalikan atau menetapkan jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Baca/tulis UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Menentukan ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. Baca/tulis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Benar jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie. Baca/tulis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Menentukan format HiLowLines. HiLowLines diterapkan dengan tipe diagram HiLowClose, OpenHiLowClose, VolumeHiLowClose, dan VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Baca/tulis Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Mendapatkan elemen pada indeks yang ditentukan. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Menentukan seberapa banyak batang dan kolom harus saling tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang sepenuhnya terpisah). - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang sepenuhnya tumpang tindih satu sama lain). Properti ini adalah baca/tulis SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Baca/tulis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Informasi pemisahan kustom untuk diagram pie-of-pie atau bar-of-pie dengan pemisahan kustom. Berisi titik data yang akan digambar pada pai atau batang kedua dalam diagram pie-of-pie atau bar-of-pie. Baca-saja [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca/tulis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Menunjukkan apakah seri dalam grup ini dipetakan pada sumbu sekunder. Baca-saja Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (dapat antara 5 hingga 200 persen). Baca/tulis UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Mengembalikan koleksi baca-saja dari seri diagram. Baca-saja [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Mengembalikan tipe grup seri ini. Baca-saja [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Menyediakan akses ke batang naik/turun pada diagram Garis atau Saham. Baca-saja [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Catatan

1) Lihat ringkasan dan catatan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum bagi setiap seri dalam grup ("properti grup seri"). "Properti grup seri" dalam kelas ChartSeriesGroup adalah baca/tulis. Setiap "properti grup seri" dapat memiliki proyeksi baca-saja dalam kelas ChartSeries.

### Lihat Juga

* antarmuka [IChartComponent](../ichartcomponent)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->