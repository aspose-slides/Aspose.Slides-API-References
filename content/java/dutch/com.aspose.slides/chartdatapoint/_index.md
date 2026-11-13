---
title: ChartDataPoint
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een gegevenspunt van de serie voor.
type: docs
url: /nl/com.aspose.slides/chartdatapoint/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Stelt een gegevenspunt van de serie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Retourneert de groottewaarde van een grafiekdatapunt. |
| [getColorValue()](#getColorValue--) | Retourneert de kleurwaarde van een grafiekdatapunt. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stelt de foutbalkwaarden van de serie voor in het geval van een Custom-waarde type. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Geeft aan dat de bubbels een 3D-effect hebben. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Geeft aan dat de bubbels een 3D-effect hebben. |
| [getExplosion()](#getExplosion--) | Geeft de hoeveelheid aan waarmee het gegevenspunt vanaf het middelpunt van de taartgrafiek wordt verplaatst. |
| [setExplosion(int value)](#setExplosion-int-) | Geeft de hoeveelheid aan waarmee het gegevenspunt vanaf het middelpunt van de taartgrafiek wordt verplaatst. |
| [getFormat()](#getFormat--) | Stelt de opmaak-eigenschappen voor. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stelt de opmaak-eigenschappen voor. |
| [getMarker()](#getMarker--) | Geeft een gegevensmarkering aan. |
| [getSetAsTotal()](#getSetAsTotal--) | Stelt het gegevenspunt in als totaal. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Stelt het gegevenspunt in als totaal. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschappen van het bijbehorende legenda-item in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Verwijdert DataPoint uit de grafiekreeks. |
| [getDataPointLevels()](#getDataPointLevels--) | Retourneert een container van de niveaus van het gegevenspunt. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Retourneert een automatische kleur van een gegevenspunt op basis van serie-index, gegevenspunt-index, de eigenschap ParentSeriesGroup.IsColorVaried en de grafiekstijl. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Geeft aan dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Geeft aan dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. |
| [getCachedValue()](#getCachedValue--) | Haalt de in cache opgeslagen waarde van een grafiekdatapunt op. |
| [getCachedXValue()](#getCachedXValue--) | Haalt de in cache opgeslagen X-waarde van een grafiekdatapunt op. |
| [getCachedYValue()](#getCachedYValue--) | Haalt de in cache opgeslagen Y-waarde van een grafiekdatapunt op. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Haalt de in cache opgeslagen bubbelgrootte van een grafiekdatapunt op. |
| [getActualX()](#getActualX--) | Geeft de daadwerkelijke x-positie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek aan. |
| [getActualY()](#getActualY--) | Geeft de daadwerkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek aan. |
| [getActualWidth()](#getActualWidth--) | Geeft de daadwerkelijke breedte van het grafiekelement aan. |
| [getActualHeight()](#getActualHeight--) | Geeft de daadwerkelijke hoogte van het grafiekelement aan. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Alleen-lezen [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Retourneert:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Retourneert de groottewaarde van een grafiekdatapunt. Wordt gebruikt met Treemap- en Sunburst-grafieken. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Retourneert de kleurwaarde van een grafiekdatapunt. Wordt gebruikt met Kaart-grafieken. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Stelt de foutbalkwaarden van de serie voor in het geval van een Custom-waarde type. Alleen-lezen [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Retourneert:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Alleen-lezen [IDataLabel](../../com.aspose.slides/idatalabel).

**Retourneert:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Geeft aan dat de bubbels een 3D-effect hebben. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Geeft aan dat de bubbels een 3D-effect hebben. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Geeft de hoeveelheid aan waarmee het gegevenspunt vanaf het middelpunt van de taartgrafiek wordt verplaatst. Lezen/Schrijven int.

**Retourneert:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Geeft de hoeveelheid aan waarmee het gegevenspunt vanaf het middelpunt van de taartgrafiek wordt verplaatst. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Stelt de opmaak-eigenschappen voor. Lezen/Schrijven [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Stelt de opmaak-eigenschappen voor. Lezen/Schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Geeft een gegevensmarkering aan. Alleen-lezen [IMarker](../../com.aspose.slides/imarker).

**Retourneert:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Stelt het gegevenspunt in als totaal. Alleen van toepassing op het Waterfall-serietype.

**Retourneert:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Stelt het gegevenspunt in als totaal. Alleen van toepassing op het Waterfall-serietype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Eigenschappen van het bijbehorende legenda-item in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retourneert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```


Verwijdert DataPoint uit de grafiekreeks.
### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


Retourneert een container van de niveaus van het gegevenspunt. Toegepast op Treeamp- en Sunburst-series. Indexering van gegevenspunt-niveaus is nul-gebaseerd.

**Retourneert:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Retourneert:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```


Retourneert een automatische kleur van een gegevenspunt op basis van serie-index, gegevenspunt-index, de eigenschap ParentSeriesGroup.IsColorVaried en de grafiekstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined.

**Retourneert:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Geeft aan dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Geeft aan dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```


Haalt de in cache opgeslagen waarde van een grafiekdatapunt op. Alleen-lezen [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

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
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```


Haalt de in cache opgeslagen X-waarde van een grafiekdatapunt op. Alleen-lezen [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

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
public final ICachedChartValue getCachedYValue()
```


Haalt de in cache opgeslagen Y-waarde van een grafiekdatapunt op. Alleen-lezen [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

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
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```


Haalt de in cache opgeslagen bubbelgrootte van een grafiekdatapunt op. Alleen-lezen [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Print alle gecachte bubbelgroottewaarden van de grafiekserie.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Geeft de daadwerkelijke x-positie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek aan. Roep IChart.ValidateChartLayout() aan vóór het ophalen van de feitelijke waarden. Lees float.

**Retourneert:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Geeft de daadwerkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek aan. Roep IChart.ValidateChartLayout() aan vóór het ophalen van de feitelijke waarden. Lees float.

**Retourneert:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Geeft de daadwerkelijke breedte van het grafiekelement aan. Roep IChart.ValidateChartLayout() aan vóór het ophalen van de feitelijke waarden. Lees float.

**Retourneert:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Geeft de daadwerkelijke hoogte van het grafiekelement aan. Roep IChart.ValidateChartLayout() aan vóór het ophalen van de feitelijke waarden. Lees float.

**Retourneert:**
float