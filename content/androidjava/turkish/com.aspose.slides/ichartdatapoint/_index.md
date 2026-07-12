---
title: IChartDataPoint
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Seri veri noktasını temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartdatapoint/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Seri veri noktasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getXValue()](#getXValue--) | Grafik veri noktasının x değerini döndürür. |
| [getYValue()](#getYValue--) | Grafik veri noktasının y değerini döndürür. |
| [getBubbleSize()](#getBubbleSize--) | Grafik veri noktasının balon boyutunu döndürür. |
| [getValue()](#getValue--) | Grafik veri noktasının değerini döndürür. |
| [getSizeValue()](#getSizeValue--) | Grafik veri noktasının boyut değerini döndürür. |
| [getColorValue()](#getColorValue--) | Grafik veri noktasının renk değerini döndürür. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Özel değer türünde serinin hata çubukları değerlerini temsil eder. |
| [getLabel()](#getLabel--) | Grafik veri noktasının etiketini temsil eder. |
| [isBubble3D()](#isBubble3D--) | Balonların 3-D etkisine sahip olduğunu belirtir. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Balonların 3-D etkisine sahip olduğunu belirtir. |
| [getExplosion()](#getExplosion--) | Veri noktasının pasta merkezinden ne kadar uzaklaştırılacağını belirtir. |
| [setExplosion(int value)](#setExplosion-int-) | Veri noktasının pasta merkezinden ne kadar uzaklaştırılacağını belirtir. |
| [getFormat()](#getFormat--) | Biçimlendirme özelliklerini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biçimlendirme özelliklerini temsil eder. |
| [getMarker()](#getMarker--) | Bir veri işaretleyicisini belirtir. |
| [remove()](#remove--) | Veri noktasını grafik serisinden kaldırır. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve grafik stili temel alınarak veri noktasının otomatik rengini döndürür. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu listedeki grafik tipi durumunda ilgili lejand girişinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Veri noktasını toplam olarak ayarlar. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Veri noktasını toplam olarak ayarlar. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Veri noktasının değeri negatifse renklerini tersine çevireceğini belirtir. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Veri noktasının değeri negatifse renklerini tersine çevireceğini belirtir. |
| [getDataPointLevels()](#getDataPointLevels--) | Veri noktası seviyelerinin kapsayıcısını döndürür. |
| [getIndex()](#getIndex--) | Bu veri noktasının ebeveynin çocuk koleksiyonlarından hangisine uygulandığını belirler. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Grafik veri noktasının x değerini döndürür. Salt okunur [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Döndürür:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Grafik veri noktasının y değerini döndürür. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Grafik veri noktasının balon boyutunu döndürür. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Grafik veri noktasının değerini döndürür. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Grafik veri noktasının boyut değerini döndürür. Treemap ve Sunburst grafiklerinde kullanılır. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Grafik veri noktasının renk değerini döndürür. Harita grafiklerinde kullanılır. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Özel değer türünde serinin hata çubukları değerlerini temsil eder. Salt okunur [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Döndürür:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Grafik veri noktasının etiketini temsil eder. Salt okunur [IDataLabel](../../com.aspose.slides/idatalabel).

**Döndürür:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Balonların 3-D etkisine sahip olduğunu belirtir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Balonların 3-D etkisine sahip olduğunu belirtir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Veri noktasının pasta merkezinden ne kadar uzaklaştırılacağını belirtir. Okuma/yazma int.

**Döndürür:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Veri noktasının pasta merkezinden ne kadar uzaklaştırılacağını belirtir. Okuma/yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Biçimlendirme özelliklerini temsil eder. Okuma/yazma [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Biçimlendirme özelliklerini temsil eder. Okuma/yazma [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Bir veri işaretleyicisini belirtir. Salt okunur [IMarker](../../com.aspose.slides/imarker).

**Döndürür:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Veri noktasını grafik serisinden kaldırır.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve grafik stiline göre veri noktasının otomatik rengini döndürür. Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır.

**Döndürür:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Bu listedeki grafik tipi durumunda ilgili lejand girişinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Salt okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall seri tipi için uygulanır.

**Döndürür:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall seri tipi için uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Veri noktasının değeri negatifse renklerini tersine çevireceğini belirtir. Okuma/yazma boolean.

**Döndürür:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Veri noktasının değeri negatifse renklerini tersine çevireceğini belirtir. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Veri noktası seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyeleri indekslemesi sıfır tabanlıdır.

**Döndürür:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Bu veri noktasının ebeveynin çocuk koleksiyonlarından hangisine uygulandığını belirler. Okuma long.

**Döndürür:**
long