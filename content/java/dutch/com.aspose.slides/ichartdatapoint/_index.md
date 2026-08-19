---
title: IChartDataPoint
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een seriedatapunt.
type: docs
url: /nl/com.aspose.slides/ichartdatapoint/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Vertegenwoordigt een seriedatapunt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getXValue()](#getXValue--) | Retourneert de x-waarde van het diagramdatapunt. |
| [getYValue()](#getYValue--) | Retourneert de y-waarde van het diagramdatapunt. |
| [getBubbleSize()](#getBubbleSize--) | Retourneert de bubbelgrootte van het diagramdatapunt. |
| [getValue()](#getValue--) | Retourneert de waarde van het diagramdatapunt. |
| [getSizeValue()](#getSizeValue--) | Retourneert de groottewaarde van het diagramdatapunt. |
| [getColorValue()](#getColorValue--) | Retourneert de kleurwaarde van het diagramdatapunt. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stelt de waarden van de foutbalken van de serie voor in het geval van een aangepast waardetype. |
| [getLabel()](#getLabel--) | Stelt het label van het diagramdatapunt voor. |
| [isBubble3D()](#isBubble3D--) | Specificeert dat de bubbels een 3D-effect hebben. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specificeert dat de bubbels een 3D-effect hebben. |
| [getExplosion()](#getExplosion--) | Specificeert de hoeveelheid waarmee het datapunt van het midden van de taartgrafiek moet worden verplaatst. |
| [setExplosion(int value)](#setExplosion-int-) | Specificeert de hoeveelheid waarmee het datapunt van het midden van de taartgrafiek moet worden verplaatst. |
| [getFormat()](#getFormat--) | Stelt de opmaak eigenschappen voor. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stelt de opmaak eigenschappen voor. |
| [getMarker()](#getMarker--) | Specificeert een datamarkering. |
| [remove()](#remove--) | Verwijdert DataPoint uit de diagramreeks. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Retourneert een automatische kleur van het datapunt op basis van de serie-index, datapunt-index, ParentSeriesGroup.IsColorVaried-eigenschap en diagramstijl. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschappen van de overeenkomstige legende vermelding in het geval van een diagrame type uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Stelt het datapunt in als totaal. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Stelt het datapunt in als totaal. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specificeert dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specificeert dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. |
| [getDataPointLevels()](#getDataPointLevels--) | Retourneert een container van datapuntniveaus. |
| [getIndex()](#getIndex--) | Bepaalt op welke collectie van de kinderen van de ouder dit datapunt van toepassing is. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Retourneert de x-waarde van het diagramdatapunt. Alleen-lezen [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Retourneert:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Retourneert de y-waarde van het diagramdatapunt. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Retourneert de bubbelgrootte van het diagramdatapunt. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Retourneert de waarde van het diagramdatapunt. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Retourneert de groottewaarde van het diagramdatapunt. Wordt gebruikt met Treemap- en Sunburst-diagrammen. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Retourneert de kleurwaarde van het diagramdatapunt. Wordt gebruikt met Kaart-diagrammen. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Stelt de waarden van de foutbalken van de serie voor in het geval van een aangepast waardetype. Alleen-lezen [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Retourneert:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Stelt het label van het diagramdatapunt voor. Alleen-lezen [IDataLabel](../../com.aspose.slides/idatalabel).

**Retourneert:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Specificeert dat de bubbels een 3D-effect hebben. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Specificeert dat de bubbels een 3D-effect hebben. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Specificeert de hoeveelheid waarmee het datapunt van het midden van de taartgrafiek moet worden verplaatst. Lezen/schrijven int.

**Retourneert:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Specificeert de hoeveelheid waarmee het datapunt van het midden van de taartgrafiek moet worden verplaatst. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Stelt de opmaak eigenschappen voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Stelt de opmaak eigenschappen voor. Lezen/schrijven [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Specificeert een datamarkering. Alleen-lezen [IMarker](../../com.aspose.slides/imarker).

**Retourneert:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Verwijdert DataPoint uit de diagramreeks.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Retourneert een automatische kleur van het datapunt op basis van de serie-index, datapunt-index, ParentSeriesGroup.IsColorVaried-eigenschap en diagramstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined.

**Retourneert:**
java.awt.Color - Automatic color of data point java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Eigenschappen van de overeenkomstige legende vermelding in het geval van een diagrame type uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retourneert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Stelt het datapunt in als totaal. Alleen van toepassing op Waterfall-serietype.

**Retourneert:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Stelt het datapunt in als totaal. Alleen van toepassing op Waterfall-serietype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Specificeert dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Specificeert dat het datapunt zijn kleuren moet inverteren als de waarde negatief is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Retourneert een container van datapuntniveaus. Toegepast voor TreeMap- en Sunburst-series. Indexering van datapuntniveaus begint bij nul.

**Retourneert:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Bepaalt op welke collectie van de kinderen van de ouder dit datapunt van toepassing is. Alleen-lezen long.

**Retourneert:**
long