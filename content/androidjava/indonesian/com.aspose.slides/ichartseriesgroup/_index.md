---
title: IChartSeriesGroup
second_title: Referensi API Java Aspose.Slides untuk Android
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

1) Lihat ringkasan dan catatan untuk kelas ChartSeriesGroupCollection dan enumerasi CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("series group properties"). "Series group properties" dalam kelas ChartSeriesGroup adalah baca/tulis. Setiap "series group properties" dapat memiliki proyeksi baca-saja dalam kelas ChartSeries.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mengembalikan tipe dari grup seri ini. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Menunjukkan apakah seri grup ini diplot pada sumbu sekunder. |
| [getSeries()](#getSeries--) | Mengembalikan koleksi baca-saja dari seri bagan. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [getUpDownBars()](#getUpDownBars--) | Memberikan akses ke bar naik/turun pada bagan Line- atau Stock-chart. |
| [getGapWidth()](#getGapWidth--) | Menentukan ruang antara kelompok bar atau kolom, sebagai persentase lebar bar atau kolom. |
| [setGapWidth(int value)](#setGapWidth-int-) | Menentukan ruang antara kelompok bar atau kolom, sebagai persentase lebar bar atau kolom. |
| [getGapDepth()](#getGapDepth--) | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam bagan 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam bagan 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Mendapatkan atau mengatur sudut irisan pertama bagan pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 sampai 360 derajat). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Mendapatkan atau mengatur sudut irisan pertama bagan pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 sampai 360 derajat). |
| [isColorVaried()](#isColorVaried--) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. |
| [hasSeriesLines()](#hasSeriesLines--) | Benar jika bagan memiliki garis seri. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Benar jika bagan memiliki garis seri. |
| [getOverlap()](#getOverlap--) | Menentukan seberapa banyak bar dan kolom harus tumpang tindih pada bagan 2-D, sebagai persentase (dari -100% sampai 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Menentukan seberapa banyak bar dan kolom harus tumpang tindih pada bagan 2-D, sebagai persentase (dari -100% sampai 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Menentukan ukuran pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie, sebagai persentase dari ukuran pai pertama (bisa antara 5 hingga 200 persen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Menentukan ukuran pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie, sebagai persentase dari ukuran pai pertama (bisa antara 5 hingga 200 persen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Menentukan cara menentukan titik data mana yang berada di pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Menentukan cara menentukan titik data mana yang berada di pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informasi pemisahan khusus untuk bagan pie-of-pie atau bar-of-pie dengan pemisahan khusus. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Menentukan ukuran lubang pada bagan donat (bisa antara 10 hingga 90 persen dari ukuran area plot). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Menentukan ukuran lubang pada bagan donat (bisa antara 10 hingga 90 persen dari ukuran area plot). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Menentukan faktor skala untuk bagan gelembung (bisa antara 0 hingga 300 persen dari ukuran default). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Menentukan faktor skala untuk bagan gelembung (bisa antara 0 hingga 300 persen dari ukuran default). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Menentukan format HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada bagan gelembung. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada bagan gelembung. |

### getType() {#getType--}
```
public abstract int getType()
```

Mengembalikan tipe dari grup seri ini. Baca-saja [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Mengembalikan:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Menunjukkan apakah seri grup ini diplot pada sumbu sekunder. Baca-saja boolean.

**Mengembalikan:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Mengembalikan koleksi baca-saja dari seri bagan. Baca-saja [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

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

Memberikan akses ke bar naik/turun pada bagan Line- atau Stock-chart. Baca-saja [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Mengembalikan:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Menentukan ruang antara kelompok bar atau kolom, sebagai persentase lebar bar atau kolom. Baca/tulis int.

**Mengembalikan:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Menentukan ruang antara kelompok bar atau kolom, sebagai persentase lebar bar atau kolom. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam bagan 3D. Baca/tulis int.

**Mengembalikan:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam bagan 3D. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Mendapatkan atau mengatur sudut irisan pertama bagan pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 sampai 360 derajat). Baca/tulis int.

**Mengembalikan:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Mendapatkan atau mengatur sudut irisan pertama bagan pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 sampai 360 derajat). Baca/tulis int.

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

Benar jika bagan memiliki garis seri. Diterapkan pada bagan bar bertumpuk dan OfPie. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Benar jika bagan memiliki garis seri. Diterapkan pada bagan bar bertumpuk dan OfPie. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Menentukan seberapa banyak bar dan kolom harus tumpang tindih pada bagan 2-D, sebagai persentase (dari -100% sampai 100%). - -100%: Jarak maksimum (bar terpisah sepenuhnya). - 0%: Bar ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (bar tumpang tindih sepenuhnya). Properti ini adalah baca/tulis byte.

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

Menentukan seberapa banyak bar dan kolom harus tumpang tindih pada bagan 2-D, sebagai persentase (dari -100% sampai 100%). - -100%: Jarak maksimum (bar terpisah sepenuhnya). - 0%: Bar ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (bar tumpang tindih sepenuhnya). Properti ini adalah baca/tulis byte.

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

Menentukan ukuran pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie, sebagai persentase dari ukuran pai pertama (bisa antara 5 hingga 200 persen). Baca/tulis int.

**Mengembalikan:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Menentukan ukuran pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie, sebagai persentase dari ukuran pai pertama (bisa antara 5 hingga 200 persen). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca/tulis double.

**Mengembalikan:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Menentukan cara menentukan titik data mana yang berada di pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie. Baca/tulis [PieSplitType](../../com.aspose.slides/piesplittype).

**Mengembalikan:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Menentukan cara menentukan titik data mana yang berada di pai atau bar kedua pada bagan pie-of-pie atau bar-of-pie. Baca/tulis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informasi pemisahan khusus untuk bagan pie-of-pie atau bar-of-pie dengan pemisahan khusus. Berisi titik data yang akan digambar di pai atau bar kedua dalam bagan pie-of-pie atau bar-of-pie. Baca-saja [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Mengembalikan:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Menentukan ukuran lubang pada bagan donat (bisa antara 10 hingga 90 persen dari ukuran area plot). Baca/tulis byte.

**Mengembalikan:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Menentukan ukuran lubang pada bagan donat (bisa antara 10 hingga 90 persen dari ukuran area plot). Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Menentukan faktor skala untuk bagan gelembung (bisa antara 0 hingga 300 persen dari ukuran default). Baca/tulis int.

**Mengembalikan:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Menentukan faktor skala untuk bagan gelembung (bisa antara 0 hingga 300 persen dari ukuran default). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Menentukan format HiLowLines. HiLowLines diterapkan pada tipe bagan HiLowClose, OpenHiLowClose, VolumeHiLowClose dan VolumeOpenHiLowClose.

**Mengembalikan:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada bagan gelembung. Baca/tulis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Mengembalikan:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada bagan gelembung. Baca/tulis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |