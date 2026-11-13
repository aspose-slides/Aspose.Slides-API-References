---
title: IChartDataPoint
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een seriesdatapunt voor.
type: docs
url: /nl/com.aspose.slides/ichartdatapoint/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Stelt een seriesdatapunt voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXValue()](#getXValue--) | Haalt de x-waarde van een grafiekdatapunt op. |
| [getYValue()](#getYValue--) | Haalt de y-waarde van een grafiekdatapunt op. |
| [getBubbleSize()](#getBubbleSize--) | Haalt de bubbelgrootte van een grafiekdatapunt op. |
| [getValue()](#getValue--) | Haalt de waarde van een grafiekdatapunt op. |
| [getCachedXValue()](#getCachedXValue--) | Haalt de gecachte X-waarde van een grafiekdatapunt op. |
| [getCachedYValue()](#getCachedYValue--) | Haalt de gecachte Y-waarde van een grafiekdatapunt op. |
| [getCachedValue()](#getCachedValue--) | Haalt de gecachte waarde van een grafiekdatapunt op. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Haalt de gecachte bubbelgrootte van een grafiekdatapunt op. |
| [getSizeValue()](#getSizeValue--) | Haalt de grootte-waarde van een grafiekdatapunt op. |
| [getColorValue()](#getColorValue--) | Haalt de kleurwaarde van een grafiekdatapunt op. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stelt de waarden van seriefoutbalken voor in het geval van een aangepast (Custom) waardetype. |
| [getLabel()](#getLabel--) | Stelt het label van een grafiekdatapunt voor. |
| [isBubble3D()](#isBubble3D--) | Geeft aan dat de bubbels een 3-D-effect hebben. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Geeft aan dat de bubbels een 3-D-effect hebben. |
| [getExplosion()](#getExplosion--) | Geeft de afstand aan waarmee het datapunt van het middelpunt van de taartgrafiek verplaatst moet worden. |
| [setExplosion(int value)](#setExplosion-int-) | Geeft de afstand aan waarmee het datapunt van het middelpunt van de taartgrafiek verplaatst moet worden. |
| [getFormat()](#getFormat--) | Stelt de opmaak-eigenschappen voor. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stelt de opmaak-eigenschappen voor. |
| [getMarker()](#getMarker--) | Geeft een datamarker aan. |
| [remove()](#remove--) | Verwijdert DataPoint uit de grafiekserie. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Retourneert een automatische kleur van het datapunt op basis van de series-index, datapunt-index, de eigenschap ParentSeriesGroup.IsColorVaried en de grafiekstijl. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschappen van het overeenkomstige legenda-item in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Stelt het datapunt in als totaal. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Stelt het datapunt in als totaal. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Geeft aan dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Geeft aan dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. |
| [getDataPointLevels()](#getDataPointLevels--) | Retourneert een container van datapuntniveaus. |
| [getIndex()](#getIndex--) | Bepaalt op welke van de kindcollecties van de ouder dit datapunt van toepassing is. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Haalt de x-waarde van een grafiekdatapunt op. Alleen-lezen [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Retourneert:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Haalt de y-waarde van een grafiekdatapunt op. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Haalt de bubbelgrootte van een grafiekdatapunt op. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Haalt de waarde van een grafiekdatapunt op. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```


Haalt de gecachte X-waarde van een grafiekdatapunt op. Alleen-lezen [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print alle gecachte X-waarden van de grafiekserie.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```


Haalt de gecachte Y-waarde van een grafiekdatapunt op. Alleen-lezen [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print alle gecachte Y-waarden van de grafiekserie.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


Haalt de gecachte waarde van een grafiekdatapunt op. Alleen-lezen [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print alle gecachte waarden van de grafiekserie.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```


Haalt de gecachte bubbelgrootte van een grafiekdatapunt op. Alleen-lezen [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print alle gecachte bubbelgrootte-waarden van de grafiekserie.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Haalt de grootte-waarde van een grafiekdatapunt op. Wordt gebruikt met Treemap- en Sunburst-grafieken. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Haalt de kleurwaarde van een grafiekdatapunt op. Wordt gebruikt met kaart-grafieken. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Stelt de waarden van seriefoutbalken voor in het geval van een aangepast (Custom) waardetype. Alleen-lezen [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Retourneert:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Stelt het label van een grafiekdatapunt voor. Alleen-lezen [IDataLabel](../../com.aspose.slides/idatalabel).

**Retourneert:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


Geeft aan dat de bubbels een 3-D-effect hebben. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Geeft aan dat de bubbels een 3-D-effect hebben. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Geeft de afstand aan waarmee het datapunt van het middelpunt van de taartgrafiek verplaatst moet worden. Lezen/schrijven int.

**Retourneert:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Geeft de afstand aan waarmee het datapunt van het middelpunt van de taartgrafiek verplaatst moet worden. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Stelt de opmaak-eigenschappen voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Stelt de opmaak-eigenschappen voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


Geeft een datamarker aan. Alleen-lezen [IMarker](../../com.aspose.slides/imarker).

**Retourneert:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```


Verwijdert DataPoint uit de grafiekserie.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


Retourneert een automatische kleur van het datapunt op basis van de series-index, datapunt-index, de eigenschap ParentSeriesGroup.IsColorVaried en de grafiekstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined.

**Retourneert:**
java.awt.Color - Automatic color of data point java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Eigenschappen van het overeenkomstige legenda-item in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retourneert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


Stelt het datapunt in als totaal. Alleen-toegepast voor de Waterfall-serietype.

**Retourneert:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


Stelt het datapunt in als totaal. Alleen-toegepast voor de Waterfall-serietype.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


Geeft aan dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Geeft aan dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Retourneert een container van datapuntniveaus. Alleen-toegepast voor Treeamp- en Sunburst-series. Indexering van datapuntniveaus is nul-gebaseerd.

**Retourneert:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Bepaalt op welke van de kindcollecties van de ouder dit datapunt van toepassing is. Alleen-lezen long.

**Retourneert:**
long