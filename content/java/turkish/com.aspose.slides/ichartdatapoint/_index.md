---
title: IChartDataPoint
second_title: Aspose.Slides için Java API Referansı
description: Seri veri noktasını temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartdatapoint/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Seri veri noktasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getXValue()](#getXValue--) | Bir grafik veri noktasının x değerini alır. |
| [getYValue()](#getYValue--) | Bir grafik veri noktasının y değerini alır. |
| [getBubbleSize()](#getBubbleSize--) | Bir grafik veri noktasının balon boyutunu alır. |
| [getValue()](#getValue--) | Bir grafik veri noktasının değerini alır. |
| [getCachedXValue()](#getCachedXValue--) | Bir grafik veri noktasının önbelleğe alınmış X değerini alır. |
| [getCachedYValue()](#getCachedYValue--) | Bir grafik veri noktasının önbelleğe alınmış Y değerini alır. |
| [getCachedValue()](#getCachedValue--) | Bir grafik veri noktasının önbelleğe alınmış değerini alır. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Bir grafik veri noktasının önbelleğe alınmış balon boyutunu alır. |
| [getSizeValue()](#getSizeValue--) | Bir grafik veri noktasının boyut değerini alır. |
| [getColorValue()](#getColorValue--) | Bir grafik veri noktasının renk değerini alır. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Özel değer tipi durumunda seri hata çubukları değerlerini temsil eder. |
| [getLabel()](#getLabel--) | Grafik veri noktasının etiketini temsil eder. |
| [isBubble3D()](#isBubble3D--) | Balonların 3-B etkisi uygulanacağını belirtir. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Balonların 3-B etkisi uygulanacağını belirtir. |
| [getExplosion()](#getExplosion--) | Veri noktasının pasta merkezinden ne kadar kaydırılacağını belirtir. |
| [setExplosion(int value)](#setExplosion-int-) | Veri noktasının pasta merkezinden ne kadar kaydırılacağını belirtir. |
| [getFormat()](#getFormat--) | Biçimlendirme özelliklerini temsil eder. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biçimlendirme özelliklerini temsil eder. |
| [getMarker()](#getMarker--) | Bir veri işaretçisi belirtir. |
| [remove()](#remove--) | Veri noktasını grafik serisinden kaldırır. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve grafik stiline göre veri noktasının otomatik rengini döndürür. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Şu listedeki grafik tipleri için ilgili lejand girişine ait özellikler: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Veri noktasını toplam olarak ayarlar. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Veri noktasını toplam olarak ayarlar. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Değer negatif olduğunda veri noktasının renklerini tersine çevireceğini belirtir. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Değer negatif olduğunda veri noktasının renklerini tersine çevireceğini belirtir. |
| [getDataPointLevels()](#getDataPointLevels--) | Veri noktası seviyelerinin kapsayıcısını döndürür. |
| [getIndex()](#getIndex--) | Bu veri noktasının ebeveynin çocuk koleksiyonunun hangisine uygulandığını belirler. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Bir grafik veri noktasının x değerini alır. Salt okunur [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Döndürür:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Bir grafik veri noktasının y değerini alır. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Bir grafik veri noktasının balon boyutunu alır. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Bir grafik veri noktasının değerini alır. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

Bir grafik veri noktasının önbelleğe alınmış X değerini alır. Salt okunur [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Grafik serisinin tüm önbelleğe alınmış X değerlerini yazdır.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

Bir grafik veri noktasının önbelleğe alınmış Y değerini alır. Salt okunur [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Grafik serisinin tüm önbelleğe alınmış Y değerlerini yazdır.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Bir grafik veri noktasının önbelleğe alınmış değerini alır. Salt okunur [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Grafik serisinin tüm önbelleğe alınmış değerlerini yazdır.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

Bir grafik veri noktasının önbelleğe alınmış balon boyutunu alır. Salt okunur [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Grafik serisinin tüm önbelleğe alınmış balon boyutu değerlerini yazdır.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Bir grafik veri noktasının boyut değerini alır. Treemap ve Sunburst grafiklerinde kullanılır. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Bir grafik veri noktasının renk değerini alır. Harita grafiklerinde kullanılır. Salt okunur [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Döndürür:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Özel değer tipi durumunda seri hata çubukları değerlerini temsil eder. Salt okunur [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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

Balonların 3-B etkisi uygulanacağını belirtir. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Balonların 3-B etkisi uygulanacağını belirtir. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Veri noktasının pasta merkezinden ne kadar kaydırılacağını belirtir. Okunur/Yazılabilir int.

**Döndürür:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Veri noktasının pasta merkezinden ne kadar kaydırılacağını belirtir. Okunur/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Biçimlendirme özelliklerini temsil eder. Okunur/Yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Biçimlendirme özelliklerini temsil eder. Okunur/Yazılabilir [IFormat](../../com.aspose.slides/iformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Bir veri işaretçisi belirtir. Salt okunur [IMarker](../../com.aspose.slides/imarker).

**Döndürür:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

Veri noktasını grafik serisinden kaldırır.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Seri indeksi, veri noktası indeksi, ParentSeriesGroup.IsColorVaried özelliği ve grafik stiline göre veri noktasının otomatik rengini döndürür. Bu renk, FillType NotDefined olduğunda varsayılan olarak kullanılır.

**Döndürür:**
java.awt.Color - Otomatik veri noktası rengi java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Şu listedeki grafik tipleri için ilgili lejand girişine ait özellikler: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Salt okunur [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Değer negatif olduğunda veri noktasının renklerini tersine çevireceğini belirtir. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Değer negatif olduğunda veri noktasının renklerini tersine çevireceğini belirtir. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Veri noktasının seviyelerinin kapsayıcısını döndürür. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyeleri sıfır-tabanlıdır.

**Döndürür:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Bu veri noktasının ebeveynin çocuk koleksiyonunun hangisine uygulandığını belirler. Salt okuma long.

**Döndürür:**
long