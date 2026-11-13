---
title: IChartSeriesGroup
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili grup seri.
type: docs
url: /id/com.aspose.slides/ichartseriesgroup/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Mewakili grup seri.

--------------------

1) Lihat ringkasan dan keterangan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri"). "Properti grup seri" dalam kelas ChartSeriesGroup bersifat baca/tulis. Setiap "properti grup seri" dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mengembalikan tipe grup seri ini. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Menunjukkan apakah seri grup ini diplot pada sumbu sekunder. |
| [getSeries()](#getSeries--) | Mengembalikan koleksi hanya-baca dari seri diagram. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [getUpDownBars()](#getUpDownBars--) | Menyediakan akses ke batang naik/turun pada diagram Garis atau Saham. |
| [getGapWidth()](#getGapWidth--) | Mendapatkan atau mengatur spasi antara kelompok batang atau kolom, sebagai persentase lebar batang atau kolom. |
| [setGapWidth(int value)](#setGapWidth-int-) | Mendapatkan atau mengatur spasi antara kelompok batang atau kolom, sebagai persentase lebar batang atau kolom. |
| [getGapDepth()](#getGapDepth--) | Mendapatkan atau mengatur jarak antara seri data dalam diagram 3D, sebagai persentase lebar penanda. |
| [setGapDepth(int value)](#setGapDepth-int-) | Mendapatkan atau mengatur jarak antara seri data dalam diagram 3D, sebagai persentase lebar penanda. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Mendapatkan atau mengatur sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, 0 hingga 360 derajat). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Mendapatkan atau mengatur sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, 0 hingga 360 derajat). |
| [isColorVaried()](#isColorVaried--) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. |
| [hasSeriesLines()](#hasSeriesLines--) | Benar jika diagram memiliki garis seri. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Benar jika diagram memiliki garis seri. |
| [getOverlap()](#getOverlap--) | Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Menentukan ukuran pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai, sebagai persentase ukuran pai pertama (bisa antara 5 dan 200 persen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Menentukan ukuran pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai, sebagai persentase ukuran pai pertama (bisa antara 5 dan 200 persen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Menentukan nilai yang digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Menentukan nilai yang digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. |
| [getPieSplitBy()](#getPieSplitBy--) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informasi pemisahan khusus untuk diagram pai-dalam-pai atau batang-dalam-pai dengan pemisahan khusus. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Menentukan ukuran lubang dalam diagram donat (bisa antara 10 dan 90 persen ukuran area plot). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Menentukan ukuran lubang dalam diagram donat (bisa antara 10 dan 90 persen ukuran area plot). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Menentukan faktor skala untuk diagram gelembung (bisa antara 0 dan 300 persen ukuran default). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Menentukan faktor skala untuk diagram gelembung (bisa antara 0 dan 300 persen ukuran default). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Menentukan format HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Menentukan cara nilai ukuran gelembung direpresentasikan pada diagram gelembung. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Menentukan cara nilai ukuran gelembung direpresentasikan pada diagram gelembung. |
### getType() {#getType--}
```
public abstract int getType()
```


Mengembalikan tipe grup seri ini. Hanya-baca [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Mengembalikan:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```


Menunjukkan apakah seri grup ini diplot pada sumbu sekunder. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```


Mengembalikan koleksi hanya-baca dari seri diagram. Hanya-baca [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Mengembalikan:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```


Menyediakan akses ke batang naik/turun pada diagram Garis atau Saham. Hanya-baca [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Mengembalikan:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Mendapatkan atau mengatur spasi antara kelompok batang atau kolom, sebagai persentase lebar batang atau kolom. Nilai harus antara 0 dan 500. Baca/tulis int.

--------------------

Properti ini berlaku untuk seri dari tipe berikut: Semua subtipe batang dan kolom, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Mengembalikan:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Mendapatkan atau mengatur spasi antara kelompok batang atau kolom, sebagai persentase lebar batang atau kolom. Nilai harus antara 0 dan 500. Baca/tulis int.

--------------------

Properti ini berlaku untuk seri dari tipe berikut: Semua subtipe batang dan kolom, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```


Mendapatkan atau mengatur jarak antara seri data dalam diagram 3D, sebagai persentase lebar penanda. Nilai harus antara 0 dan 500. Baca/tulis int.

--------------------

Properti ini berlaku untuk seri dari tipe berikut: Subtipe batang dan kolom 3D, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Mengembalikan:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```


Mendapatkan atau mengatur jarak antara seri data dalam diagram 3D, sebagai persentase lebar penanda. Nilai harus antara 0 dan 500. Baca/tulis int.

--------------------

Properti ini berlaku untuk seri dari tipe berikut: Subtipe batang dan kolom 3D, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```


Mendapatkan atau mengatur sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, 0 hingga 360 derajat). Baca/tulis int.

**Mengembalikan:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```


Mendapatkan atau mengatur sudut irisan pertama diagram pai atau donat, dalam derajat (searah jarum jam dari atas, 0 hingga 360 derajat). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```


Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```


Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```


Benar jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```


Benar jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```


Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang benar-benar terpisah). - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang benar-benar tumpang tindih satu sama lain). Properti ini adalah baca/tulis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Atur tumpang tindih menjadi 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```


Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang benar-benar terpisah). - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang benar-benar tumpang tindih satu sama lain). Properti ini adalah baca/tulis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Atur tumpang tindih menjadi 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```


Menentukan ukuran pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai, sebagai persentase ukuran pai pertama (bisa antara 5 dan 200 persen). Baca/tulis int.

**Mengembalikan:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```


Menentukan ukuran pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai, sebagai persentase ukuran pai pertama (bisa antara 5 dan 200 persen). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```


Menentukan nilai yang digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. Digunakan bersama properti PieSplitBy. Baca/tulis double.

**Mengembalikan:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```


Menentukan nilai yang digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. Digunakan bersama properti PieSplitBy. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```


Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. Baca/tulis [PieSplitType](../../com.aspose.slides/piesplittype).

**Mengembalikan:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```


Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. Baca/tulis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


Informasi pemisahan khusus untuk diagram pai-dalam-pai atau batang-dalam-pai dengan pemisahan khusus. Berisi titik data yang harus digambar di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai. Hanya-baca [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Mengembalikan:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```


Menentukan ukuran lubang dalam diagram donat (bisa antara 10 dan 90 persen ukuran area plot). Baca/tulis byte.

**Mengembalikan:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```


Menentukan ukuran lubang dalam diagram donat (bisa antara 10 dan 90 persen ukuran area plot). Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```


Menentukan faktor skala untuk diagram gelembung (bisa antara 0 dan 300 persen ukuran default). Baca/tulis int.

**Mengembalikan:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```


Menentukan faktor skala untuk diagram gelembung (bisa antara 0 dan 300 persen ukuran default). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```


Menentukan format HiLowLines. HiLowLines diterapkan pada tipe diagram HiLowClose, OpenHiLowClose, VolumeHiLowClose dan VolumeOpenHiLowClose.

**Mengembalikan:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```


Menentukan cara nilai ukuran gelembung direpresentasikan pada diagram gelembung. Baca/tulis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Mengembalikan:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```


Menentukan cara nilai ukuran gelembung direpresentasikan pada diagram gelembung. Baca/tulis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |