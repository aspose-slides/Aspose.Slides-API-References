---
title: ChartDataPoint
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje datový bod řady.
type: docs
url: /cs/com.aspose.slides/chartdatapoint/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Reprezentuje datový bod řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Vrací velikostní hodnotu datového bodu grafu. |
| [getColorValue()](#getColorValue--) | Vrací hodnotu barvy datového bodu grafu. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Reprezentuje hodnoty čárových chyb řady v případě typu Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Určuje, že bubliny mají aplikován 3-D efekt. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Určuje, že bubliny mají aplikován 3-D efekt. |
| [getExplosion()](#getExplosion--) | Určuje, o kolik má být datový bod posunut od středu koláče. |
| [setExplosion(int value)](#setExplosion-int-) | Určuje, o kolik má být datový bod posunut od středu koláče. |
| [getFormat()](#getFormat--) | Reprezentuje vlastnosti formátování. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Reprezentuje vlastnosti formátování. |
| [getMarker()](#getMarker--) | Určuje datový marker. |
| [getSetAsTotal()](#getSetAsTotal--) | Nastavuje datový bod jako celkový. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Nastavuje datový bod jako celkový. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Vlastnosti odpovídající položky legendy v případě typů grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Odstraňuje DataPoint z řady grafu. |
| [getDataPointLevels()](#getDataPointLevels--) | Vrací kontejner úrovní datových bodů. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná. |
| [getCachedValue()](#getCachedValue--) | Získává kešovanou hodnotu datového bodu grafu. |
| [getCachedXValue()](#getCachedXValue--) | Získává kešovanou X hodnotu datového bodu grafu. |
| [getCachedYValue()](#getCachedYValue--) | Získává kešovanou Y hodnotu datového bodu grafu. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Získává kešovanou velikost bubliny datového bodu grafu. |
| [getActualX()](#getActualX--) | Určuje skutečnou X polohu (levá) grafického elementu relativně k levému hornímu rohu grafu. |
| [getActualY()](#getActualY--) | Určuje skutečnou horní polohu grafického elementu relativně k levému hornímu rohu grafu. |
| [getActualWidth()](#getActualWidth--) | Určuje skutečnou šířku grafického elementu. |
| [getActualHeight()](#getActualHeight--) | Určuje skutečnou výšku grafického elementu. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Pouze pro čtení [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Vrací:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Vrací velikostní hodnotu datového bodu grafu. Používá se u grafů Treemap a Sunburst. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Vrací hodnotu barvy datového bodu grafu. Používá se u mapových grafů. Pouze pro čtení [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Vrací:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Reprezentuje hodnoty čárových chyb řady v případě typu Custom. Pouze pro čtení [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Vrací:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Pouze pro čtení [IDataLabel](../../com.aspose.slides/idatalabel).

**Vrací:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Určuje, že bubliny mají aplikován 3-D efekt. Čtení/Zápis boolean.

**Vrací:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Určuje, že bubliny mají aplikován 3-D efekt. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Určuje, o kolik má být datový bod posunut od středu koláče. Čtení/Zápis int.

**Vrací:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Určuje, o kolik má být datový bod posunut od středu koláče. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Reprezentuje vlastnosti formátování. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Reprezentuje vlastnosti formátování. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Určuje datový marker. Pouze pro čtení [IMarker](../../com.aspose.slides/imarker).

**Vrací:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Nastavuje datový bod jako celkový. Používá se pouze pro typ řady Waterfall.

**Vrací:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Nastavuje datový bod jako celkový. Používá se pouze pro typ řady Waterfall.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Vlastnosti odpovídající položky legendy v případě typů grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

Odstraňuje DataPoint z řady grafu.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Vrací kontejner úrovní datových bodů. Používá se pro Treeamp a Sunburst řady. Indexování úrovní datových bodů je nulové.

**Vrací:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```

  

**Vrací:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. Tato barva se použije jako výchozí, pokud FillType je NotDefined.

**Vrací:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Vrací:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Získává kešovanou hodnotu datového bodu grafu. Pouze pro čtení [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Vytiskne všechny kešované hodnoty řady grafu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

Získává kešovanou X hodnotu datového bodu grafu. Pouze pro čtení [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Vytiskne všechny kešované hodnoty X řady grafu.
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
public final ICachedChartValue getCachedYValue()
```

Získává kešovanou Y hodnotu datového bodu grafu. Pouze pro čtení [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Vytiskne všechny kešované hodnoty Y řady grafu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

Získává kešovanou velikost bubliny datového bodu grafu. Pouze pro čtení [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Vytiskne všechny kešované hodnoty velikosti bublin řady grafu.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Určuje skutečnou X polohu (levá) grafického elementu relativně k levému hornímu rohu grafu. Zavolejte metodu IChart.ValidateChartLayout() před získáním skutečných hodnot. Pouze pro čtení float.

**Vrací:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Určuje skutečnou horní polohu grafického elementu relativně k levému hornímu rohu grafu. Zavolejte metodu IChart.ValidateChartLayout() před získáním skutečných hodnot. Pouze pro čtení float.

**Vrací:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Určuje skutečnou šířku grafického elementu. Zavolejte metodu IChart.ValidateChartLayout() před získáním skutečných hodnot. Pouze pro čtení float.

**Vrací:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Určuje skutečnou výšku grafického elementu. Zavolejte metodu IChart.ValidateChartLayout() před získáním skutečných hodnot. Pouze pro čtení float.

**Vrací:**
float