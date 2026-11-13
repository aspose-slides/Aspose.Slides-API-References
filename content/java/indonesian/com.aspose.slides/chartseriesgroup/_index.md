---
title: ChartSeriesGroup
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili grup seri.
type: docs
url: /id/com.aspose.slides/chartseriesgroup/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Mewakili grup seri.

--------------------

1) Lihat ringkasan dan catatan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri"). "Properti grup seri" dalam kelas ChartSeriesGroup bersifat baca/tulis. Setiap "properti grup seri" dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mengembalikan tipe grup seri ini. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Menunjukkan apakah seri dalam grup ini diplot pada sumbu sekunder. |
| [getSeries()](#getSeries--) | Mengembalikan koleksi seri. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [getUpDownBars()](#getUpDownBars--) | Menyediakan akses ke batang naik/turun pada grafik Line atau Stock. |
| [getGapWidth()](#getGapWidth--) | Mendapatkan atau mengatur ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. |
| [setGapWidth(int value)](#setGapWidth-int-) | Mendapatkan atau mengatur ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. |
| [getGapDepth()](#getGapDepth--) | Mendapatkan atau mengatur jarak antara seri data dalam grafik 3D, sebagai persentase lebar penanda. |
| [setGapDepth(int value)](#setGapDepth-int-) | Mendapatkan atau mengatur jarak antara seri data dalam grafik 3D, sebagai persentase lebar penanda. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Mendapatkan atau mengatur sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Mendapatkan atau mengatur sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Menentukan ukuran lubang dalam diagram donat (bisa antara 0 hingga 90 persen dari ukuran area plot). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Menentukan ukuran lubang dalam diagram donat (bisa antara 0 hingga 90 persen dari ukuran area plot). |
| [getOverlap()](#getOverlap--) | Menentukan seberapa banyak batang dan kolom saling bertumpuk pada grafik 2-D, sebagai persentase (dari -100% hingga 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Menentukan seberapa banyak batang dan kolom saling bertumpuk pada grafik 2-D, sebagai persentase (dari -100% hingga 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (bisa antara 5 hingga 200 persen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (bisa antara 5 hingga 200 persen). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. |
| [hasSeriesLines()](#hasSeriesLines--) | True jika chart memiliki garis seri. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True jika chart memiliki garis seri. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Menentukan format HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Menentukan faktor skala untuk diagram gelembung (bisa antara 0 hingga 300 persen dari ukuran default). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Menentukan faktor skala untuk diagram gelembung (bisa antara 0 hingga 300 persen dari ukuran default). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informasi pemisahan kustom untuk diagram pie-of-pie atau bar-of-pie dengan pemisahan kustom. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Mengembalikan chart induk. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Mengembalikan tipe grup seri ini. Hanya-baca [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Mengembalikan:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Menunjukkan apakah seri dalam grup ini diplot pada sumbu sekunder. Hanya-baca boolean.

**Mengembalikan:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Mengembalikan koleksi seri. Hanya-baca [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Mengembalikan:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Menyediakan akses ke batang naik/turun pada grafik Line atau Stock. Hanya-baca [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Mengembalikan:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Mendapatkan atau mengatur ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. Nilai harus antara 0 dan 500. Baca/tulis int.

--------------------

Properti ini berlaku untuk seri dari tipe berikut: Subtipe Bar (lihat juga metode [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), Subtipe Column (lihat juga metode [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Mengembalikan:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Mendapatkan atau mengatur ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. Nilai harus antara 0 dan 500. Baca/tulis int.

--------------------

Properti ini berlaku untuk seri dari tipe berikut: Subtipe Bar (lihat juga metode [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), Subtipe Column (lihat juga metode [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Mendapatkan atau mengatur jarak antara seri data dalam grafik 3D, sebagai persentase lebar penanda. Nilai harus antara 0 dan 500. Baca/tulis int.

--------------------

Properti ini berlaku untuk seri dari tipe berikut: Subtipe bar dan kolom 3D (lihat juga metode [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Mengembalikan:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Mendapatkan atau mengatur jarak antara seri data dalam grafik 3D, sebagai persentase lebar penanda. Nilai harus antara 0 dan 500. Baca/tulis int.

--------------------

Properti ini berlaku untuk seri dari tipe berikut: Subtipe bar dan kolom 3D (lihat juga metode [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Mendapatkan atau mengatur sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Baca/tulis int.

**Mengembalikan:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Mendapatkan atau mengatur sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Baca/tulis int.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Menentukan ukuran lubang dalam diagram donat (bisa antara 0 hingga 90 persen dari ukuran area plot). Baca/tulis byte.

**Mengembalikan:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Menentukan ukuran lubang dalam diagram donat (bisa antara 0 hingga 90 persen dari ukuran area plot). Baca/tulis byte.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Menentukan seberapa banyak batang dan kolom saling bertumpuk pada grafik 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang sepenuhnya terpisah). - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang sepenuhnya tumpang tindih satu sama lain). Properti ini adalah baca/tulis byte.

**Mengembalikan:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Menentukan seberapa banyak batang dan kolom saling bertumpuk pada grafik 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang sepenuhnya terpisah). - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang sepenuhnya tumpang tindih satu sama lain). Properti ini adalah baca/tulis byte.

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Atur overlap menjadi 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
byte

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Atur overlap menjadi 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (bisa antara 5 hingga 200 persen). Baca/tulis int.

**Mengembalikan:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Menentukan ukuran pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (bisa antara 5 hingga 200 persen). Baca/tulis int.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Baca/tulis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Mengembalikan:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung. Baca/tulis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca/tulis double.

**Mengembalikan:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca/tulis double.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Baca/tulis [PieSplitType](../../com.aspose.slides/piesplittype).

**Mengembalikan:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pie-of-pie atau bar-of-pie. Baca/tulis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

True jika chart memiliki garis seri. Diterapkan pada chart stacked bar dan OfPie. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

True jika chart memiliki garis seri. Diterapkan pada chart stacked bar dan OfPie. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Menentukan format HiLowLines. HiLowLines diterapkan dengan tipe chart HiLowClose, OpenHiLowClose, VolumeHiLowClose, dan VolumeOpenHiLowClose.

**Mengembalikan:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Menentukan faktor skala untuk diagram gelembung (bisa antara 0 hingga 300 persen dari ukuran default). Baca/tulis int.

**Mengembalikan:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Menentukan faktor skala untuk diagram gelembung (bisa antara 0 hingga 300 persen dari ukuran default). Baca/tulis int.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informasi pemisahan kustom untuk diagram pie-of-pie atau bar-of-pie dengan pemisahan kustom. Berisi titik data yang akan digambar di pai atau batang kedua dalam diagram pie-of-pie atau bar-of-pie. Hanya-baca [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Mengembalikan:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan chart induk. Hanya-baca [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari FillFormat. Hanya-baca [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari FillFormat. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)