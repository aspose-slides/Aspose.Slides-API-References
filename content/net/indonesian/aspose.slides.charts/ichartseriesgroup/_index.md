---
title: IChartSeriesGroup
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mewakili grup seri.
type: docs
weight: 1930
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
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Memungkinkan untuk mendapatkan antarmuka IChartComponent dasar. Hanya-baca [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Baca/tulis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 dan 300 persen dari ukuran default). Baca/tulis Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Menentukan ukuran lubang pada diagram donat (dapat antara 10 dan 90 persen dari ukuran area plot). Baca/tulis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Mendapatkan atau mengatur sudut irisan pai atau donat pertama, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Baca/tulis UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D. Baca/tulis UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Menentukan ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. Baca/tulis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Benar jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie. Baca/tulis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Menentukan format HiLowLines. HiLowLines diterapkan dengan tipe diagram HiLowClose, OpenHiLowClose, VolumeHiLowClose, dan VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Baca/tulis Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Mendapatkan elemen pada indeks yang ditentukan. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang terpisah sepenuhnya). - 0%: Batang ditempatkan bersebelahan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang sepenuhnya tumpang tindih satu sama lain). Properti ini Baca/tulis SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Baca/tulis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Informasi pemisahan khusus untuk diagram pie-of-pie atau bar-of-pie dengan pemisahan khusus. Berisi titik data yang akan digambar pada pai atau batang kedua dalam diagram pie-of-pie atau bar-of-pie. Hanya-baca [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca/tulis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Menunjukkan apakah seri dalam grup ini diplot pada sumbu sekunder. Hanya-baca Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (dapat antara 5 dan 200 persen). Baca/tulis UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Mengembalikan koleksi hanya-baca dari seri diagram. Hanya-baca [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Mengembalikan tipe grup seri ini. Hanya-baca [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Menyediakan akses ke batang naik/turun pada diagram Garis atau Saham. Hanya-baca [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Catatan

1) Lihat ringkasan dan catatan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("series group properties"). "Series group properties" dalam kelas ChartSeriesGroup adalah baca/tulis. Setiap "series group properties" dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.

### Lihat Juga

* antarmuka [IChartComponent](../ichartcomponent)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->