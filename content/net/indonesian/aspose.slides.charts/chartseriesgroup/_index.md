---
title: ChartSeriesGroup
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mewakili grup seri.
type: docs
weight: 1440
url: /id/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup kelas

Mewakili grup seri.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada bagan gelembung. Baca/tulis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Menentukan faktor skala untuk bagan gelembung (bisa antara 0 dan 300 persen dari ukuran default). Baca/tulis Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Mengembalikan bagan induk. Baca-saja [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Menentukan ukuran lubang pada bagan donat (bisa antara 0 dan 90 persen dari ukuran area plot). Baca/tulis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Mendapatkan atau mengatur sudut irisan pertama bagan pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Baca/tulis UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara rangkaian data dalam bagan 3D. Baca/tulis UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Menentukan ruang antara gugusan batang atau kolom, sebagai persentase lebar batang atau kolom. Baca/tulis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Benar jika bagan memiliki garis seri. Diterapkan pada bagan batang bertumpuk dan OfPie. Baca/tulis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Menentukan format HiLowLines. HiLowLines diterapkan dengan tipe bagan HiLowClose, OpenHiLowClose, VolumeHiLowClose, dan VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Baca/tulis Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Mendapatkan elemen pada indeks yang ditentukan. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Menentukan seberapa banyak batang dan kolom harus saling tumpang pada bagan 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang terpisah sepenuhnya). - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang sepenuhnya menumpuk satu sama lain). Properti ini adalah baca/tulis SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada bagan pie-of-pie atau bar-of-pie. Baca/tulis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Informasi pembagian khusus untuk bagan pie-of-pie atau bar-of-pie dengan pembagian khusus. Berisi titik data yang harus digambar pada pai atau batang kedua dalam bagan pie-of-pie atau bar-of-pie. Baca-saja [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada bagan pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca/tulis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Menunjukkan apakah seri grup ini dipetakan pada sumbu sekunder. Baca-saja Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Menentukan ukuran pai atau batang kedua pada bagan pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (bisa antara 5 dan 200 persen). Baca/tulis UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Mengembalikan koleksi seri. Baca-saja [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Mengembalikan tipe grup seri ini. Baca-saja [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Menyediakan akses ke bar naik/turun pada bagan Line atau Stock. Baca-saja [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Catatan

1) Lihat ringkasan dan catatan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri"). "Properti grup seri" dalam kelas ChartSeriesGroup adalah baca/tulis. Setiap "properti grup seri" dapat memiliki proyeksi baca-saja dalam kelas ChartSeries.

### Lihat Juga

* antarmuka [IChartSeriesGroup](../ichartseriesgroup)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* perakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->