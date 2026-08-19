---
title: ChartSeriesGroup
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili grup seri.
type: docs
url: /id/com.aspose.slides/chartseriesgroup/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Mewakili grup seri.

--------------------

1) Lihat ringkasan dan keterangan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri"). "Properti grup seri" dalam kelas ChartSeriesGroup bersifat baca/tulis. Setiap "properti grup seri" dapat memiliki proyeksi baca-saja dalam kelas ChartSeries.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Mengembalikan tipe grup seri ini. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Menunjukkan apakah seri grup ini diplot pada sumbu sekunder. |
| [getSeries()](#getSeries--) | Mengembalikan koleksi seri. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [getUpDownBars()](#getUpDownBars--) | Menyediakan akses ke batang naik/turun pada grafik Line atau Stock. |
| [getGapWidth()](#getGapWidth--) | Menentukan ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. |
| [setGapWidth(int value)](#setGapWidth-int-) | Menentukan ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. |
| [getGapDepth()](#getGapDepth--) | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam grafik 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam grafik 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Mendapatkan atau mengatur sudut irisan pertama grafik pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Mendapatkan atau mengatur sudut irisan pertama grafik pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Menentukan ukuran lubang pada grafik donat (dapat antara 0 hingga 90 persen dari ukuran area plot). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Menentukan ukuran lubang pada grafik donat (dapat antara 0 hingga 90 persen dari ukuran area plot). |
| [getOverlap()](#getOverlap--) | Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada grafik 2-D, sebagai persentase (dari -100% hingga 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada grafik 2-D, sebagai persentase (dari -100% hingga 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Menentukan ukuran pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (dapat antara 5 hingga 200 persen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Menentukan ukuran pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (dapat antara 5 hingga 200 persen). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada grafik gelembung. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada grafik gelembung. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. |
| [hasSeriesLines()](#hasSeriesLines--) | Benar jika grafik memiliki garis seri. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Benar jika grafik memiliki garis seri. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Menentukan format HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Menentukan faktor skala untuk grafik gelembung (dapat antara 0 hingga 300 persen dari ukuran default). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Menentukan faktor skala untuk grafik gelembung (dapat antara 0 hingga 300 persen dari ukuran default). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informasi pemisahan kustom untuk grafik pie-of-pie atau bar-of-pie dengan pemisahan kustom. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Mengembalikan grafik induk. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari FillFormat. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari FillFormat. |
### getType() {#getType--}
```
public final int getType()
```

Mengembalikan tipe grup seri ini. Baca-saja [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Mengembalikan:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Menunjukkan apakah seri grup ini diplot pada sumbu sekunder. Baca-saja boolean.

**Mengembalikan:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Mengembalikan koleksi seri. Baca-saja [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Mengembalikan:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
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
public final IUpDownBarsManager getUpDownBars()
```

Menyediakan akses ke batang naik/turun pada grafik Line atau Stock. Baca-saja [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Mengembalikan:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Menentukan ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. Baca/tulis int.

**Mengembalikan:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Menentukan ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam grafik 3D. Baca/tulis int.

**Mengembalikan:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam grafik 3D. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Mendapatkan atau mengatur sudut irisan pertama grafik pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Baca/tulis int.

**Mengembalikan:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Mendapatkan atau mengatur sudut irisan pertama grafik pai atau donat, dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Menentukan ukuran lubang pada grafik donat (dapat antara 0 hingga 90 persen dari ukuran area plot). Baca/tulis byte.

**Mengembalikan:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Menentukan ukuran lubang pada grafik donat (dapat antara 0 hingga 90 persen dari ukuran area plot). Baca/tulis byte.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada grafik 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang terpisah sepenuhnya). - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang sepenuhnya menutupi satu sama lain). Properti ini Baca/tulis byte.

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


**Mengembalikan:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Menentukan seberapa banyak batang dan kolom harus tumpang tindih pada grafik 2-D, sebagai persentase (dari -100% hingga 100%). - -100%: Jarak maksimum (batang terpisah sepenuhnya). - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak. - 100%: Tumpang tindih maksimum (batang sepenuhnya menutupi satu sama lain). Properti ini Baca/tulis byte.

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
public final int getSecondPieSize()
```

Menentukan ukuran pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (dapat antara 5 hingga 200 persen). Baca/tulis int.

**Mengembalikan:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Menentukan ukuran pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie, sebagai persentase ukuran pai pertama (dapat antara 5 hingga 200 persen). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada grafik gelembung. Baca/tulis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Mengembalikan:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada grafik gelembung. Baca/tulis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca/tulis double.

**Mengembalikan:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie. Digunakan bersama properti PieSplitBy. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie. Baca/tulis [PieSplitType](../../com.aspose.slides/piesplittype).

**Mengembalikan:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada grafik pie-of-pie atau bar-of-pie. Baca/tulis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Benar jika grafik memiliki garis seri. Diterapkan pada grafik stacked bar dan OfPie. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Benar jika grafik memiliki garis seri. Diterapkan pada grafik stacked bar dan OfPie. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Menentukan format HiLowLines. HiLowLines diterapkan dengan tipe grafik HiLowClose, OpenHiLowClose, VolumeHiLowClose dan VolumeOpenHiLowClose.

**Mengembalikan:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Menentukan faktor skala untuk grafik gelembung (dapat antara 0 hingga 300 persen dari ukuran default). Baca/tulis int.

**Mengembalikan:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Menentukan faktor skala untuk grafik gelembung (dapat antara 0 hingga 300 persen dari ukuran default). Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Informasi pemisahan kustom untuk grafik pie-of-pie atau bar-of-pie dengan pemisahan kustom. Berisi titik data yang harus digambar di pai atau batang kedua dalam grafik pie-of-pie atau bar-of-pie. Baca-saja [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Mengembalikan:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent\_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Mengembalikan grafik induk. Baca-saja [IChart](../../com.aspose.slides/ichart).

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari FillFormat. Baca-saja [BaseSlide](../../com.aspose.slides/baseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari FillFormat. Baca-saja [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)