---
title: ChartDataPoint
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een gegevenspunt van de serie voor.
type: docs
url: /nl/com.aspose.slides/chartdatapoint/
---
**Erfenis:**  
java.lang.Object

**Alle geïmplementeerde interfaces:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Stelt een datapunt van de serie voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Retourneert de groottewaarde van het diagramgegevenspunt. |
| [getColorValue()](#getColorValue--) | Retourneert de kleurwaarde van het diagramgegevenspunt. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stelt de waarden van seriesfoutbalken voor in het geval van een aangepast waardetype. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Specificeert dat de bubbels een 3D-effect hebben. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specificeert dat de bubbels een 3D-effect hebben. |
| [getExplosion()](#getExplosion--) | Specificeert de hoeveelheid waarmee het gegevenspunt van het middelpunt van de taartgrafiek moet worden verplaatst. |
| [setExplosion(int value)](#setExplosion-int-) | Specificeert de hoeveelheid waarmee het gegevenspunt van het middelpunt van de taartgrafiek moet worden verplaatst. |
| [getFormat()](#getFormat--) | Stelt de opmaak-eigenschappen voor. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stelt de opmaak-eigenschappen voor. |
| [getMarker()](#getMarker--) | Specificeert een datamarkering. |
| [getSetAsTotal()](#getSetAsTotal--) | Stelt het gegevenspunt in als totaal. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Stelt het gegevenspunt in als totaal. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschappen van de overeenkomstige legendarijvermelding in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Verwijdert DataPoint uit de grafiekserie. |
| [getDataPointLevels()](#getDataPointLevels--) | Retourneert de container van gegevenspuntniveaus. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Retourneert een automatische kleur van het gegevenspunt op basis van de series-index, gegevenspunt-index, de eigenschap ParentSeriesGroup.IsColorVaried en de diagramstijl. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specificeert dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specificeert dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. |
| [getActualX()](#getActualX--) | Specificeert de werkelijke x-locatie (links) van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram. |
| [getActualY()](#getActualY--) | Specificeert de werkelijke bovenkant van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram. |
| [getActualWidth()](#getActualWidth--) | Specificeert de werkelijke breedte van het diagramonderdeel. |
| [getActualHeight()](#getActualHeight--) | Specificeert de werkelijke hoogte van het diagramonderdeel. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. Alleen-lezen [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Retour:**  
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

Retourneert de groottewaarde van het diagramgegevenspunt. Wordt gebruikt met Treemap- en Sunburst-diagrammen. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Retourneert de kleurwaarde van het diagramgegevenspunt. Wordt gebruikt met kaart-diagrammen. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retour:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Stelt de waarden van seriesfoutbalken voor in het geval van een aangepast waardetype. Alleen-lezen [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Retour:**  
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. Alleen-lezen [IDataLabel](../../com.aspose.slides/idatalabel).

**Retour:**  
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

Specificeert dat de bubbels een 3D-effect hebben. Lezen/schrijven boolean.

**Retour:**  
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Specificeert dat de bubbels een 3D-effect hebben. Lezen/schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Specificeert de hoeveelheid waarmee het gegevenspunt van het middelpunt van de taartgrafiek moet worden verplaatst. Lezen/schrijven int.

**Retour:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Specificeert de hoeveelheid waarmee het gegevenspunt van het middelpunt van de taartgrafiek moet worden verplaatst. Lezen/schrijven int.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Stelt de opmaak-eigenschappen voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Retour:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Stelt de opmaak-eigenschappen voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Specificeert een datamarkering. Alleen-lezen [IMarker](../../com.aspose.slides/imarker).

**Retour:**  
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Stelt het gegevenspunt in als totaal. Alleen toegepast op Waterfall-serietype.

**Retour:**  
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Stelt het gegevenspunt in als totaal. Alleen toegepast op Waterfall-serietype.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Eigenschappen van de overeenkomstige legendarijvermelding in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retour:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

Verwijdert DataPoint uit de grafiekserie.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Retourneert de container van gegevenspuntniveaus. Alleen toegepast op Treeamp- en Sunburst-reeksen. Indexering van gegevenspuntniveaus begint bij nul.

**Retour:**  
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

  

**Retour:**  
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retour:**  
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

Retourneert een automatische kleur van het gegevenspunt op basis van de series-index, gegevenspunt-index, de eigenschap ParentSeriesGroup.IsColorVaried en de diagramstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined.

**Retour:**  
java.lang.Integer

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Specificeert dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. Lezen/schrijven boolean.

**Retour:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Specificeert dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. Lezen/schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Specificeert de werkelijke x-locatie (links) van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram. Roep methode IChart.ValidateChartLayout() aan vóór het ophalen van de werkelijke waarden. Lezen float.

**Retour:**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Specificeert de werkelijke bovenkant van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram. Roep methode IChart.ValidateChartLayout() aan vóór het ophalen van de werkelijke waarden. Lezen float.

**Retour:**  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Specificeert de werkelijke breedte van het diagramonderdeel. Roep methode IChart.ValidateChartLayout() aan vóór het ophalen van de werkelijke waarden. Lezen float.

**Retour:**  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Specificeert de werkelijke hoogte van het diagramonderdeel. Roep methode IChart.ValidateChartLayout() aan vóór het ophalen van de werkelijke waarden. Lezen float.

**Retour:**  
float