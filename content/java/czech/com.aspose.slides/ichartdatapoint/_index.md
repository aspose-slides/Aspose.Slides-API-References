---
title: IChartDataPoint
second_title: Aspose.Slides pro Java – referenční příručka
description: Představuje datový bod řady.
type: docs
url: /cs/com.aspose.slides/ichartdatapoint/
---
**All Implemented Interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Reprezentuje datový bod řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [getXValue()](#getXValue--) | Získá hodnotu x datového bodu v grafu. |
| [getYValue()](#getYValue--) | Získá hodnotu y datového bodu v grafu. |
| [getBubbleSize()](#getBubbleSize--) | Získá velikost bubliny datového bodu v grafu. |
| [getValue()](#getValue--) | Získá hodnotu datového bodu v grafu. |
| [getCachedXValue()](#getCachedXValue--) | Získá uloženou hodnotu X datového bodu v grafu. |
| [getCachedYValue()](#getCachedYValue--) | Získá uloženou hodnotu Y datového bodu v grafu. |
| [getCachedValue()](#getCachedValue--) | Získá uloženou hodnotu datového bodu v grafu. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Získá uloženou velikost bubliny datového bodu v grafu. |
| [getSizeValue()](#getSizeValue--) | Získá velikostní hodnotu datového bodu v grafu. |
| [getColorValue()](#getColorValue--) | Získá barevnou hodnotu datového bodu v grafu. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Reprezentuje hodnoty chybových úseků řady v případě typu Custom. |
| [getLabel()](#getLabel--) | Reprezentuje popisek datového bodu v grafu. |
| [isBubble3D()](#isBubble3D--) | Určuje, že bubliny mají aplikovaný 3-D efekt. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Určuje, že bubliny mají aplikovaný 3-D efekt. |
| [getExplosion()](#getExplosion--) | Určuje, o kolik má být datový bod posunut od středu koláče. |
| [setExplosion(int value)](#setExplosion-int-) | Určuje, o kolik má být datový bod posunut od středu koláče. |
| [getFormat()](#getFormat--) | Reprezentuje vlastnosti formátování. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje vlastnosti formátování. |
| [getMarker()](#getMarker--) | Určuje datový značkovač. |
| [remove()](#remove--) | Odstraňuje DataPoint ze série grafu. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Vlastnosti odpovídající položky legendy v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Nastaví datový bod jako součet. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Nastaví datový bod jako součet. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Určuje, že datový bod má invertovat své barvy, pokud je hodnota záporná. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Určuje, že datový bod má invertovat své barvy, pokud je hodnota záporná. |
| [getDataPointLevels()](#getDataPointLevels--) | Vrací kontejner úrovní datových bodů. |
| [getIndex()](#getIndex--) | Určuje, ke které kolekci podřízených prvků nadřazeného objektu se tento datový bod vztahuje. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Získá hodnotu x datového bodu v grafu. Pouze ke čtení [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Vrací:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Získá hodnotu y datového bodu v grafu. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Získá velikost bubliny datového bodu v grafu. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Získá hodnotu datového bodu v grafu. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```


Získá uloženou hodnotu X datového bodu v grafu. Pouze ke čtení [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Vytiskne všechny uložené hodnoty X řady grafu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```


Získá uloženou hodnotu Y datového bodu v grafu. Pouze ke čtení [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Vytiskne všechny uložené hodnoty Y řady grafu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


Získá uloženou hodnotu datového bodu v grafu. Pouze ke čtení [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Vytiskne všechny uložené hodnoty řady grafu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```


Získá uloženou velikost bubliny datového bodu v grafu. Pouze ke čtení [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Vytiskne všechny uložené hodnoty velikosti bubliny řady grafu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Získá velikostní hodnotu datového bodu v grafu. Používá se s grafy Treemap a Sunburst. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Získá barevnou hodnotu datového bodu v grafu. Používá se s mapovými grafy. Pouze ke čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Reprezentuje hodnoty chybových úseků řady v případě typu Custom. Pouze ke čtení [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Vrací:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Reprezentuje popisek datového bodu v grafu. Pouze ke čtení [IDataLabel](../../com.aspose.slides/idatalabel).

**Vrací:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


Určuje, že bubliny mají aplikovaný 3-D efekt. Čtení/Zápis boolean.

**Vrací:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Určuje, že bubliny mají aplikovaný 3-D efekt. Čtení/Zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Určuje, o kolik má být datový bod posunut od středu koláče. Čtení/Zápis int.

**Vrací:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Určuje, o kolik má být datový bod posunut od středu koláče. Čtení/Zápis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Reprezentuje vlastnosti formátování. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Reprezentuje vlastnosti formátování. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


Určuje datový značkovač. Pouze ke čtení [IMarker](../../com.aspose.slides/imarker).

**Vrací:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


Odstraňuje DataPoint ze série grafu.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. Tato barva se použije ve výchozím nastavení, pokud FillType má hodnotu NotDefined.

**Vrací:**
java.awt.Color - Automatická barva datového bodu java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Vlastnosti odpovídající položky legendy v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Pouze ke čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


Nastaví datový bod jako součet. Používá se pouze pro typ řady Waterfall.

**Vrací:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


Nastaví datový bod jako součet. Používá se pouze pro typ řady Waterfall.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


Určuje, že datový bod má invertovat své barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Vrací:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Určuje, že datový bod má invertovat své barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Vrací kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst. Indexování úrovní datových bodů je nulové.

**Vrací:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Určuje, ke které kolekci podřízených prvků nadřazeného objektu se tento datový bod vztahuje. Pouze ke čtení long.

**Vrací:**
long