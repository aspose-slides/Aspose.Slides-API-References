---
title: IChartDataPoint
second_title: Aspose.Slides for Java API Referansı
description: Seri veri noktasını temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartdatapoint/
---
**All Implemented Interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Seri veri noktasını temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | Grafik veri noktasının x değerini döndürür. |
| [getYValue()](#getYValue--) | Grafik veri noktasının y değerini döndürür. |
| [getBubbleSize()](#getBubbleSize--) | Grafik veri noktasının balon boyutunu döndürür. |
| [getValue()](#getValue--) | Grafik veri noktasının değerini döndürür. |
| [getSizeValue()](#getSizeValue--) | Grafik veri noktasının boyut değerini döndürür. |
| [getColorValue()](#getColorValue--) | Grafik veri noktasının renk değerini döndürür. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Özel değer türü durumunda seri hata çubukları değerlerini temsil eder. |
| [getLabel()](#getLabel--) | Grafik veri noktasının etiketini temsil eder. |
| [isBubble3D()](#isBubble3D--) | Balonların 3B etkisine sahip olduğunu belirtir. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Balonların 3B etkisine sahip olduğunu belirtir. |
| [getExplosion()](#getExplosion--) | Veri noktasının pasta grafiğinin merkezinden ne kadar taşınacağını belirtir. |
| [setExplosion(int value)](#setExplosion-int-) | Veri noktasının pasta grafiğinin merkezinden ne kadar taşınacağını belirtir. |
| [getFormat()](#getFormat--) | Biçimlendirme özelliklerini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biçimlendirme özelliklerini temsil eder. |
| [getMarker()](#getMarker--) | Bir veri işaretçisi belirtir. |
| [remove()](#remove--) | DataPoint'i grafik serisinden kaldırır. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Seri indeksine, veri noktası indeksine, ParentSeriesGroup.IsColorVaried özelliğine ve grafik stiline göre veri noktasının otomatik rengini döndürür. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu listeden grafik tipi durumunda ilgili lejand girişinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Veri noktasını toplam olarak ayarlar. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Veri noktasını toplam olarak ayarlar. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. |
| [getDataPointLevels()](#getDataPointLevels--) | Veri noktası seviyelerinin kapsayıcısını döndürür. |
| [getIndex()](#getIndex--) | Bu veri noktasının ebeveynin çocuk koleksiyonundan hangisine uygulandığını belirler. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Grafik veri noktasının x değerini döndürür. Yalnızca okuma [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Döndürür:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Grafik veri noktasının y değerini döndürür. Yalnızca okuma [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Grafik veri noktasının balon boyutunu döndürür. Yalnızca okuma [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Grafik veri noktasının değerini döndürür. Yalnızca okuma [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Grafik veri noktasının boyut değerini döndürür. Treemap ve Sunburst grafiklerinde kullanılır. Yalnızca okuma [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Grafik veri noktasının renk değerini döndürür. Harita grafiklerinde kullanılır. Yalnızca okuma [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Özel değer türü durumunda seri hata çubukları değerlerini temsil eder. Yalnızca okuma [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Döndürür:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Grafik veri noktasının etiketini temsil eder. Yalnızca okuma [IDataLabel](../../com.aspose.slides/idatalabel).

**Döndürür:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


Balonların 3B etkisine sahip olduğunu belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Balonların 3B etkisine sahip olduğunu belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Veri noktasının pasta grafiğinin merkezinden ne kadar taşınacağını belirtir. Okuma/Yazma int.

**Döndürür:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Veri noktasının pasta grafiğinin merkezinden ne kadar taşınacağını belirtir. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Biçimlendirme özelliklerini temsil eder. Okuma/Yazma [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Biçimlendirme özelliklerini temsil eder. Okuma/Yazma [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


Bir veri işaretçisi belirtir. Yalnızca okuma [IMarker](../../com.aspose.slides/imarker).

**Döndürür:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


DataPoint'i grafik serisinden kaldırır.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


Seri indeksine, veri noktası indeksine, ParentSeriesGroup.IsColorVaried özelliğine ve grafik stiline göre veri noktasının otomatik rengini döndürür. Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır.

**Döndürür:**
java.awt.Color - Veri noktasının otomatik rengi java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Bu listeden grafik tipi durumunda ilgili lejand girişinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Yalnızca okuma [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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


Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Değer negatifse veri noktasının renklerini tersine çevireceğini belirtir. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Veri noktası seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyeleri indeksleme sıfır tabanlıdır.

**Döndürür:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Bu veri noktasının ebeveynin çocuk koleksiyonundan hangisine uygulandığını belirler. Okuma long.

**Döndürür:**
long