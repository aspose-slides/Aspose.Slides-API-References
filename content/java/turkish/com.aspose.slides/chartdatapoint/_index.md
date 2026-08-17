---
title: ChartDataPoint
second_title: Aspose.Slides for Java API Referansı
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
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Özel değer türü durumunda seri hata çubukları değerlerini temsil eder. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Baloncukların 3D etkisi uygulandığını belirtir. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Baloncukların 3D etkisi uygulandığını belirtir. |
| [getExplosion()](#getExplosion--) | Veri noktasının pasta merkezinden ne kadar uzaklaştırılacağını belirtir. |
| [setExplosion(int value)](#setExplosion-int-) | Veri noktasının pasta merkezinden ne kadar uzaklaştırılacağını belirtir. |
| [getFormat()](#getFormat--) | Biçimlendirme özelliklerini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biçimlendirme özelliklerini temsil eder. |
| [getMarker()](#getMarker--) | Veri işaretleyicisini belirtir. |
| [getSetAsTotal()](#getSetAsTotal--) | Veriyi toplam olarak ayarlar. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Veriyi toplam olarak ayarlar. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Bu listeden bir grafik türü için ilgili lejand girdisinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | DataPoint öğesini grafik serisinden kaldırır. |
| [getDataPointLevels()](#getDataPointLevels--) | Veri noktası seviyelerinin kapsayıcısını döndürür. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Seri indeksine, veri noktası indeksine, ParentSeriesGroup.IsColorVaried özelliğine ve grafik stiline göre veri noktasının otomatik rengini döndürür. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Veri noktasının değeri negatifse renklerini tersine çevirir. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Veri noktasının değeri negatifse renklerini tersine çevirir. |
| [getActualX()](#getActualX--) | Grafik öğesinin sol üst köşesine göre gerçek x konumunu (sol) belirtir. |
| [getActualY()](#getActualY--) | Grafik öğesinin sol üst köşesine göre gerçek üst konumunu belirtir. |
| [getActualWidth()](#getActualWidth--) | Grafik öğesinin gerçek genişliğini belirtir. |
| [getActualHeight()](#getActualHeight--) | Grafik öğesinin gerçek yüksekliğini belirtir. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Salt-okunur [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Döndürür:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Salt-okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Salt-okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Salt-okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Grafik veri noktasının boyut değerini döndürür. Treemap ve Sunburst grafiklerinde kullanılır. Salt-okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Grafik veri noktasının renk değerini döndürür. Harita grafiklerinde kullanılır. Salt-okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Özel değer türü durumunda seri hata çubukları değerlerini temsil eder. Salt-okunur [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Döndürür:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Salt-okunur [IDataLabel](../../com.aspose.slides/idatalabel).

**Döndürür:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Baloncukların 3D etkisi uygulandığını belirtir. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Baloncukların 3D etkisi uygulandığını belirtir. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Veri noktasının pasta merkezinden ne kadar uzaklaştırılacağını belirtir. Okunur/Yazılabilir int.

**Döndürür:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Veri noktasının pasta merkezinden ne kadar uzaklaştırılacağını belirtir. Okunur/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Biçimlendirme özelliklerini temsil eder. Okunur/Yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Biçimlendirme özelliklerini temsil eder. Okunur/Yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Veri işaretleyicisini belirtir. Salt-okunur [IMarker](../../com.aspose.slides/imarker).

**Döndürür:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Veriyi toplam olarak ayarlar. Yalnızca Waterfall seri türü için uygulanır.

**Döndürür:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Veriyi toplam olarak ayarlar. Yalnızca Waterfall seri türü için uygulanır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Bu listeden bir grafik türü için ilgili lejand girdisinin özellikleri: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Salt-okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Döndürür:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```


DataPoint öğesini grafik serisinden kaldırır.
### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


Veri noktası seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyesi indekslemesi sıfır temellidir.

**Döndürür:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Döndürür:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```


Seri indeksine, veri noktası indeksine, ParentSeriesGroup.IsColorVaried özelliğine ve grafik stiline göre veri noktasının otomatik rengini döndürür. Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır.

**Döndürür:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Veri noktasının değeri negatifse renklerini tersine çevirir. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Veri noktasının değeri negatifse renklerini tersine çevirir. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Grafik öğesinin sol üst köşesine göre gerçek x konumunu (sol) belirtir. Gerçek değerleri elde etmek için IChart.ValidateChartLayout() metodunu çağırın. Okunur float.

**Döndürür:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Grafik öğesinin sol üst köşesine göre gerçek üst konumunu belirtir. Gerçek değerleri elde etmek için IChart.ValidateChartLayout() metodunu çağırın. Okunur float.

**Döndürür:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri elde etmek için IChart.ValidateChartLayout() metodunu çağırın. Okunur float.

**Döndürür:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri elde etmek için IChart.ValidateChartLayout() metodunu çağırın. Okunur float.

**Döndürür:**
float