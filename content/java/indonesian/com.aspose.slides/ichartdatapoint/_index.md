---
title: IChartDataPoint
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili titik data seri.
type: docs
url: /id/com.aspose.slides/ichartdatapoint/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Mewakili titik data seri.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getXValue()](#getXValue--) | Mengembalikan nilai x dari titik data bagan. |
| [getYValue()](#getYValue--) | Mengembalikan nilai y dari titik data bagan. |
| [getBubbleSize()](#getBubbleSize--) | Mengembalikan ukuran gelembung dari titik data bagan. |
| [getValue()](#getValue--) | Mengembalikan nilai dari titik data bagan. |
| [getSizeValue()](#getSizeValue--) | Mengembalikan nilai ukuran dari titik data bagan. |
| [getColorValue()](#getColorValue--) | Mengembalikan nilai warna dari titik data bagan. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Mewakili nilai batang error seri bila tipe nilai Custom. |
| [getLabel()](#getLabel--) | Mewakili label titik data bagan. |
| [isBubble3D()](#isBubble3D--) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan padanya. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan padanya. |
| [getExplosion()](#getExplosion--) | Menentukan jumlah pergeseran titik data dari pusat pai. |
| [setExplosion(int value)](#setExplosion-int-) | Menentukan jumlah pergeseran titik data dari pusat pai. |
| [getFormat()](#getFormat--) | Mewakili properti pemformatan. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Mewakili properti pemformatan. |
| [getMarker()](#getMarker--) | Menentukan penanda data. |
| [remove()](#remove--) | Menghapus DataPoint dari seri bagan. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried, dan gaya bagan. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properti entri legenda yang sesuai bila tipe bagan dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Menetapkan titik data sebagai total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Menetapkan titik data sebagai total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Menentukan titik data harus membalikkan warnanya jika nilainya negatif. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Menentukan titik data harus membalikkan warnanya jika nilainya negatif. |
| [getDataPointLevels()](#getDataPointLevels--) | Mengembalikan kontainer level titik data. |
| [getIndex()](#getIndex--) | Menentukan koleksi anak orang tua yang mana titik data ini berlaku. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Mengembalikan nilai x dari titik data bagan. Hanya-baca [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Mengembalikan:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Mengembalikan nilai y dari titik data bagan. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Mengembalikan ukuran gelembung dari titik data bagan. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Mengembalikan nilai dari titik data bagan. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Mengembalikan nilai ukuran dari titik data bagan. Digunakan dengan bagan Treemap dan Sunburst. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Mengembalikan nilai warna dari titik data bagan. Digunakan dengan bagan Peta. Hanya-baca [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Mewakili nilai batang error seri bila tipe nilai Custom. Hanya-baca [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Mengembalikan:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Mewakili label titik data bagan. Hanya-baca [IDataLabel](../../com.aspose.slides/idatalabel).

**Mengembalikan:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan padanya. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan padanya. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Menentukan jumlah pergeseran titik data dari pusat pai. Baca/tulis int.

**Mengembalikan:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Menentukan jumlah pergeseran titik data dari pusat pai. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Mewakili properti pemformatan. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Mengembalikan:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Mewakili properti pemformatan. Baca/tulis [IFormat](../../com.aspose.slides/iformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Menentukan penanda data. Hanya-baca [IMarker](../../com.aspose.slides/imarker).

**Mengembalikan:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Menghapus DataPoint dari seri bagan.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried, dan gaya bagan. Warna ini digunakan secara default bila FillType sama dengan NotDefined.

**Mengembalikan:**
java.awt.Color - Automatic color of data point java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Properti entri legenda yang sesuai bila tipe bagan dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Hanya-baca [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Mengembalikan:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Menetapkan titik data sebagai total. Diterapkan hanya untuk tipe seri Waterfall.

**Mengembalikan:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Menetapkan titik data sebagai total. Diterapkan hanya untuk tipe seri Waterfall.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Menentukan titik data harus membalikkan warnanya jika nilainya negatif. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Menentukan titik data harus membalikkan warnanya jika nilainya negatif. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Mengembalikan kontainer level titik data. Diterapkan untuk seri Treeamp dan Sunburst. Pengindeksan level titik data dimulai dari nol.

**Mengembalikan:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Menentukan koleksi anak orang tua yang mana titik data ini berlaku. Baca long.

**Mengembalikan:**
long