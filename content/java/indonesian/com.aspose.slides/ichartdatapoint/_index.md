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
| [getXValue()](#getXValue--) | Mengambil nilai x dari titik data chart. |
| [getYValue()](#getYValue--) | Mengambil nilai y dari titik data chart. |
| [getBubbleSize()](#getBubbleSize--) | Mengambil ukuran gelembung dari titik data chart. |
| [getValue()](#getValue--) | Mengambil nilai dari titik data chart. |
| [getCachedXValue()](#getCachedXValue--) | Mengambil nilai X yang di-cache dari titik data chart. |
| [getCachedYValue()](#getCachedYValue--) | Mengambil nilai Y yang di-cache dari titik data chart. |
| [getCachedValue()](#getCachedValue--) | Mengambil nilai yang di-cache dari titik data chart. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Mengambil ukuran gelembung yang di-cache dari titik data chart. |
| [getSizeValue()](#getSizeValue--) | Mengambil nilai ukuran dari titik data chart. |
| [getColorValue()](#getColorValue--) | Mengambil nilai warna dari titik data chart. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Mewakili nilai error bar seri dalam kasus tipe nilai Custom. |
| [getLabel()](#getLabel--) | Mewakili label titik data chart. |
| [isBubble3D()](#isBubble3D--) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan pada mereka. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan pada mereka. |
| [getExplosion()](#getExplosion--) | Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. |
| [setExplosion(int value)](#setExplosion-int-) | Menentukan jumlah titik data yang harus dipindahkan dari pusat pai. |
| [getFormat()](#getFormat--) | Mewakili properti pemformatan. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Mewakili properti pemformatan. |
| [getMarker()](#getMarker--) | Menentukan penanda data. |
| [remove()](#remove--) | Menghapus DataPoint dari seri chart. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried, dan gaya chart. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properti entri legenda yang sesuai dalam kasus tipe chart dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Menetapkan titik data sebagai total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Menetapkan titik data sebagai total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Menentukan bahwa titik data harus membalikkan warnanya jika nilainya negatif. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Menentukan bahwa titik data harus membalikkan warnanya jika nilainya negatif. |
| [getDataPointLevels()](#getDataPointLevels--) | Mengembalikan kontainer level titik data. |
| [getIndex()](#getIndex--) | Menentukan koleksi anak orang tua mana yang berlaku untuk titik data ini. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Mengambil nilai x dari titik data chart. Baca-saja [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Mengembalikan:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Mengambil nilai y dari titik data chart. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Mengambil ukuran gelembung dari titik data chart. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Mengambil nilai dari titik data chart. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```


Mengambil nilai X yang di-cache dari titik data chart. Baca-saja [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Cetak semua nilai X yang di-cache dari seri chart.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```


Mengambil nilai Y yang di-cache dari titik data chart. Baca-saja [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Cetak semua nilai Y yang di-cache dari seri chart.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


Mengambil nilai yang di-cache dari titik data chart. Baca-saja [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Cetak semua nilai yang di-cache dari seri chart.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```


Mengambil ukuran gelembung yang di-cache dari titik data chart. Baca-saja [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Cetak semua nilai ukuran gelembung yang di-cache dari seri chart.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Mengambil nilai ukuran dari titik data chart. Digunakan dengan chart Treemap dan Sunburst. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Mengambil nilai warna dari titik data chart. Digunakan dengan chart Map. Baca-saja [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Mengembalikan:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Mewakili nilai error bar seri dalam kasus tipe nilai Custom. Baca-saja [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Mengembalikan:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Mewakili label titik data chart. Baca-saja [IDataLabel](../../com.aspose.slides/idatalabel).

**Mengembalikan:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan pada mereka. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Menentukan bahwa gelembung memiliki efek 3-D yang diterapkan pada mereka. Baca/tulis boolean.

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


Menghapus DataPoint dari seri chart.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


Mengembalikan warna otomatis titik data berdasarkan indeks seri, indeks titik data, properti ParentSeriesGroup.IsColorVaried, dan gaya chart. Warna ini digunakan secara default jika FillType sama dengan NotDefined.

**Mengembalikan:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Properti entri legenda yang sesuai dalam kasus tipe chart dari daftar berikut: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Baca-saja [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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


Menentukan bahwa titik data harus membalikkan warnanya jika nilainya negatif. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Menentukan bahwa titik data harus membalikkan warnanya jika nilainya negatif. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Mengembalikan kontainer level titik data. Diterapkan untuk seri Treeamp dan Sunburst. Pengindeksan level titik data berbasis nol.

**Mengembalikan:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Menentukan koleksi anak orang tua mana yang berlaku untuk titik data ini. Baca long.

**Mengembalikan:**
long