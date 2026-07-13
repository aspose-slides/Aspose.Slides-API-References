---
title: IChartDataPoint
second_title: Aspose.Slides untuk Android melalui Referensi API Java
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
| [getXValue()](#getXValue--) | Mengembalikan nilai x dari titik data grafik. |
| [getYValue()](#getYValue--) | Mengembalikan nilai y dari titik data grafik. |
| [getBubbleSize()](#getBubbleSize--) | Mengembalikan ukuran gelembung dari titik data grafik. |
| [getValue()](#getValue--) | Mengembalikan nilai dari titik data grafik. |
| [getSizeValue()](#getSizeValue--) | Mengembalikan nilai ukuran dari titik data grafik. |
| [getColorValue()](#getColorValue--) | Mengembalikan nilai warna dari titik data grafik. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Mewakili nilai batang kesalahan seri dalam kasus tipe nilai Custom. |
| [getLabel()](#getLabel--) | Mewakili label dari titik data grafik. |
| [isBubble3D()](#isBubble3D--) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan padanya. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan padanya. |
| [getExplosion()](#getExplosion--) | Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. |
| [setExplosion(int value)](#setExplosion-int-) | Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. |
| [getFormat()](#getFormat--) | Mewakili properti pemformatan. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Mewakili properti pemformatan. |
| [getMarker()](#getMarker--) | Menentukan penanda data. |
| [remove()](#remove--) | Menghapus DataPoint dari seri grafik. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Mengembalikan warna otomatis dari titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried, dan gaya grafik. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properti entri legenda yang sesuai dalam kasus tipe grafik dari daftar ini: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Menetapkan titik data sebagai total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Menetapkan titik data sebagai total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Menentukan titik data harus membalikkan warnanya jika nilai negatif. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Menentukan titik data harus membalikkan warnanya jika nilai negatif. |
| [getDataPointLevels()](#getDataPointLevels--) | Mengembalikan kontainer level titik data. |
| [getIndex()](#getIndex--) | Menentukan koleksi anak orang tua yang mana titik data ini berlaku. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Mengembalikan nilai x dari titik data grafik. Baca-saja [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Mengembalikan:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Mengembalikan nilai y dari titik data grafik. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Mengembalikan ukuran gelembung dari titik data grafik. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Mengembalikan nilai dari titik data grafik. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Mengembalikan nilai ukuran dari titik data grafik. Digunakan dengan grafik Treemap dan Sunburst. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Mengembalikan nilai warna dari titik data grafik. Digunakan dengan grafik Peta. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Mewakili nilai batang kesalahan seri dalam kasus tipe nilai Custom. Baca-saja [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Mengembalikan:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Mewakili label dari titik data grafik. Baca-saja [IDataLabel](../../com.aspose.slides/idatalabel).

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

Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. Baca/tulis int.

**Mengembalikan:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. Baca/tulis int.

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

Menentukan penanda data. Baca-saja [IMarker](../../com.aspose.slides/imarker).

**Mengembalikan:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Menghapus DataPoint dari seri grafik.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Mengembalikan warna otomatis dari titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried, dan gaya grafik. Warna ini digunakan secara default jika FillType sama dengan NotDefined.

**Mengembalikan:**
java.lang.Integer - Warna otomatis dari titik data java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Properti entri legenda yang sesuai dalam kasus tipe grafik dari daftar ini: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Baca-saja [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Menentukan titik data harus membalikkan warnanya jika nilai negatif. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Menentukan titik data harus membalikkan warnanya jika nilai negatif. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Mengembalikan kontainer level titik data. Diterapkan untuk seri Treeamp dan Sunburst. Pengindeksan level titik data mulai dari nol.

**Mengembalikan:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Menentukan koleksi anak orang tua yang mana titik data ini berlaku. Baca long.

**Mengembalikan:**
long