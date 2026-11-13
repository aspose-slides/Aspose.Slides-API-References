---
title: IChartSeriesGroup
second_title: Aspose.Sildes untuk Referensi API .NET
description: Mewakili grup seri.
type: docs
weight: 1970
url: /id/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup antarmuka

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Properti

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Memungkinkan mendapatkan antarmuka IChartComponent dasar. Hanya-baca [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Baca/tulis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 dan 300 persen dari ukuran default). Baca/tulis Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Menentukan ukuran lubang pada diagram donat (dapat antara 10 dan 90 persen dari ukuran area plot). Baca/tulis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Mendapatkan atau mengatur sudut iris pertama pada diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Baca/tulis UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Mendapatkan atau mengatur jarak antara seri data pada diagram 3D, sebagai persentase lebar penanda. Nilai harus antara 0 dan 500. Baca/tulis UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Mendapatkan atau mengatur ruang antara gugusan batang atau kolom, sebagai persentase lebar batang atau kolom. Nilai harus antara 0 dan 500. Baca/tulis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Benar jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie. Baca/tulis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Menentukan format HiLowLines. HiLowLines diterapkan dengan tipe diagram HiLowClose, OpenHiLowClose, VolumeHiLowClose, dan VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Baca/tulis Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Mendapatkan elemen pada indeks yang ditentukan. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang benar-benar terpisah). - 0%: Batang diletakkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang benar-benar tumpang tindih satu sama lain). Properti ini baca/tulis SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dari-pai atau batang-dari-pai. Baca/tulis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Informasi pemisahan khusus untuk diagram pai-dari-pai atau batang-dari-pai dengan pemisahan khusus. Berisi titik data yang akan digambar pada pai atau batang kedua dalam diagram pai-dari-pai atau batang-dari-pai. Hanya-baca [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dari-pai atau batang-dari-pai. Digunakan bersama properti PieSplitBy. Baca/tulis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Menunjukkan apakah seri dalam grup ini diplot pada sumbu sekunder. Hanya-baca Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Menentukan ukuran pai atau batang kedua pada diagram pai-dari-pai atau batang-dari-pai, sebagai persentase ukuran pai pertama (dapat antara 5 dan 200 persen). Baca/tulis UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Mengembalikan koleksi hanya-baca dari seri diagram. Hanya-baca [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Mengembalikan tipe dari grup seri ini. Hanya-baca [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Menyediakan akses ke batang naik/turun pada diagram Line- atau Stock-chart. Hanya-baca [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Catatan

1) Lihat ringkasan dan catatan untuk ChartSeriesGroupCollection kelas dan enum CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri"). "Properti grup seri" dalam kelas ChartSeriesGroup adalah baca/tulis. Setiap "properti grup seri" dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.

### Lihat Juga

* antarmuka [IChartComponent](../ichartcomponent)
* ruang nama [Aspose.Slides.Charts](../../aspose.slides.charts)
* rakitan [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->