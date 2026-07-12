---
title: ChartDataPoint
second_title: Aspose.Slides Android için Java API Referansı
description: Seri veri noktasını temsil eder.
type: docs
url: /tr/com.aspose.slides/chartdatapoint/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Seri veri noktasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Grafik veri noktasının boyut değerini döndürür. |
| [getColorValue()](#getColorValue--) | Grafik veri noktasının renk değerini döndürür. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Özel değer tipinde serinin hata çubukları değerlerini temsil eder. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Balonların 3D etkisi uygulanacağını belirtir. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Balonların 3D etkisi uygulanacağını belirtir. |
| [getExplosion()](#getExplosion--) | Veri noktasının pasta grafiğinin merkezinden ne kadar uzaklaştırılacağını belirtir. |
| [setExplosion(int value)](#setExplosion-int-) | Veri noktasının pasta grafiğinin merkezinden ne kadar uzaklaştırılacağını belirtir. |
| [getFormat()](#getFormat--) | Biçimlendirme özelliklerini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biçimlendirme özelliklerini temsil eder. |
| [getMarker()](#getMarker--) | Bir veri işaretleyicisi belirtir. |
| [getSetAsTotal()](#getSetAsTotal--) | Veri noktasını toplam olarak ayarlar. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Veri noktasını toplam olarak ayarlar. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu listeden bir grafik tipi durumunda karşılık gelen lejand girişinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | DataPoint'ı grafik serisinden kaldırır. |
| [getDataPointLevels()](#getDataPointLevels--) | Veri noktası seviyelerinin kapsayıcısını döndürür. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Seri indeksine, veri noktası indeksine, ParentSeriesGroup.IsColorVaried özelliğine ve grafik stiline göre veri noktasının otomatik rengini döndürür. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. |
| [getActualX()](#getActualX--) | Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. |
| [getActualY()](#getActualY--) | Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. |
| [getActualWidth()](#getActualWidth--) | Grafik öğesinin gerçek genişliğini belirtir. |
| [getActualHeight()](#getActualHeight--) | Grafik öğesinin gerçek yüksekliğini belirtir. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Sadece okunabilir [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Döndürür:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Sadece okunabilir [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Sadece okunabilir [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Sadece okunabilir [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Grafik veri noktasının boyut değerini döndürür. Treemap ve Sunburst grafiklerinde kullanılır. Sadece okunabilir [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Grafik veri noktasının renk değerini döndürür. Harita grafiklerinde kullanılır. Sadece okunabilir [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Özel değer tipinde serinin hata çubukları değerlerini temsil eder. Sadece okunabilir [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Döndürür:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Sadece okunabilir [IDataLabel](../../com.aspose.slides/idatalabel).

**Döndürür:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Balonların 3D etkisi uygulanacağını belirtir. Okunabilir/yazılabilir boolean.

**Döndürür:** boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Balonların 3D etkisi uygulanacağını belirtir. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Veri noktasının pasta grafiğinin merkezinden ne kadar uzaklaştırılacağını belirtir. Okunabilir/yazılabilir int.

**Döndürür:** int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Veri noktasının pasta grafiğinin merkezinden ne kadar uzaklaştırılacağını belirtir. Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Biçimlendirme özelliklerini temsil eder. Okunabilir/yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Biçimlendirme özelliklerini temsil eder. Okunabilir/yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Bir veri işaretleyicisi belirtir. Sadece okunabilir [IMarker](../../com.aspose.slides/imarker).

**Döndürür:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall seri tipi için uygulanır.

**Döndürür:** boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Veri noktasını toplam olarak ayarlar. Yalnızca Waterfall seri tipi için uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Bu listeden bir grafik tipi durumunda karşılık gelen lejand girişinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Sadece okunabilir [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

DataPoint'ı grafik serisinden kaldırır.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Veri noktası seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyeleri sıfır tabanlı indekslenir.

**Döndürür:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


**Döndürür:** long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Sadece okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

Seri indeksine, veri noktası indeksine, ParentSeriesGroup.IsColorVaried özelliğine ve grafik stiline göre veri noktasının otomatik rengini döndürür. Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır.

**Döndürür:**
java.lang.Integer
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. Okunabilir/yazılabilir boolean.

**Döndürür:** boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için IChart.ValidateChartLayout() metodunu önceden çağırın. Okunabilir float.

**Döndürür:** float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. Gerçek değerleri almak için IChart.ValidateChartLayout() metodunu önceden çağırın. Okunabilir float.

**Döndürür:** float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için IChart.ValidateChartLayout() metodunu önceden çağırın. Okunabilir float.

**Döndürür:** float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için IChart.ValidateChartLayout() metodunu önceden çağırın. Okunabilir float.

**Döndürür:** float