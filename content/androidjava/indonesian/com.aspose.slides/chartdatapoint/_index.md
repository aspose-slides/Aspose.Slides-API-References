---
title: ChartDataPoint
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili titik data seri.
type: docs
url: /id/com.aspose.slides/chartdatapoint/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Mewakili titik data seri.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Mengembalikan nilai ukuran titik data bagan. |
| [getColorValue()](#getColorValue--) | Mengembalikan nilai warna titik data bagan. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Mewakili nilai batang galat seri dalam kasus tipe nilai Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan pada mereka. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan pada mereka. |
| [getExplosion()](#getExplosion--) | Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. |
| [setExplosion(int value)](#setExplosion-int-) | Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. |
| [getFormat()](#getFormat--) | Mewakili properti pemformatan. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Mewakili properti pemformatan. |
| [getMarker()](#getMarker--) | Menentukan penanda data. |
| [getSetAsTotal()](#getSetAsTotal--) | Menetapkan titik data sebagai total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Menetapkan titik data sebagai total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properti entri legenda yang sesuai dalam kasus tipe bagan dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Menghapus DataPoint dari seri bagan. |
| [getDataPointLevels()](#getDataPointLevels--) | Mengembalikan kontainer level titik data. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried dan gaya bagan. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Menentukan titik data harus membalikkan warnanya jika nilai negatif. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Menentukan titik data harus membalikkan warnanya jika nilai negatif. |
| [getActualX()](#getActualX--) | Menentukan lokasi x aktual (kiri) elemen bagan relatif terhadap sudut kiri atas bagan. |
| [getActualY()](#getActualY--) | Menentukan bagian atas aktual elemen bagan relatif terhadap sudut kiri atas bagan. |
| [getActualWidth()](#getActualWidth--) | Menentukan lebar aktual elemen bagan. |
| [getActualHeight()](#getActualHeight--) | Menentukan tinggi aktual elemen bagan. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Hanya-baca [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Mengembalikan:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Mengembalikan nilai ukuran titik data bagan. Digunakan dengan bagan Treemap dan Sunburst. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Mengembalikan nilai warna titik data bagan. Digunakan dengan bagan Peta. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Mewakili nilai batang galat seri dalam kasus tipe nilai Custom. Hanya-baca [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Mengembalikan:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Hanya-baca [IDataLabel](../../com.aspose.slides/idatalabel).

**Mengembalikan:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan pada mereka. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan pada mereka. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. Baca/tulis int.

**Mengembalikan:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Mewakili properti pemformatan. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Mewakili properti pemformatan. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Menentukan penanda data. Hanya-baca [IMarker](../../com.aspose.slides/imarker).

**Mengembalikan:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Menetapkan titik data sebagai total. Diterapkan hanya untuk tipe seri Waterfall.

**Mengembalikan:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Menetapkan titik data sebagai total. Diterapkan hanya untuk tipe seri Waterfall.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Properti entri legenda yang sesuai dalam kasus tipe bagan dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Hanya-baca [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Mengembalikan:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

Menghapus DataPoint dari seri bagan.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Mengembalikan kontainer level titik data. Diterapkan untuk seri Treeamp dan Sunburst. Pengindeksan level titik data berbasis nol.

**Mengembalikan:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**Mengembalikan:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried dan gaya bagan. Warna ini digunakan secara default jika FillType sama dengan NotDefined.

**Mengembalikan:**
java.lang.Integer

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Menentukan titik data harus membalikkan warnanya jika nilai negatif. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Menentukan titik data harus membalikkan warnanya jika nilai negatif. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualY()
```

Menentukan lokasi x aktual (kiri) elemen bagan relatif terhadap sudut kiri atas bagan. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. Baca float.

**Mengembalikan:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Menentukan bagian atas aktual elemen bagan relatif terhadap sudut kiri atas bagan. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. Baca float.

**Mengembalikan:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Menentukan lebar aktual elemen bagan. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. Baca float.

**Mengembalikan:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Menentukan tinggi aktual elemen bagan. Panggil metode IChart.ValidateChartLayout() sebelumnya untuk mendapatkan nilai aktual. Baca float.

**Mengembalikan:**
float