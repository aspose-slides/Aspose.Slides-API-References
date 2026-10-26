---
title: ChartDataPoint
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een gegevenspunt van de serie voor.
type: docs
url: /nl/com.aspose.slides/chartdatapoint/
---
**Erfenis:**
java.lang.Object

**Alle Geïmplementeerde Interfaces:**
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
| [getSizeValue()](#getSizeValue--) | Retourneert de groottewaarde van het diagramgegevenspunt. |
| [getColorValue()](#getColorValue--) | Retourneert de kleurwaarde van het diagramgegevenspunt. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Stelt de waarden van seriefoutbalken voor in het geval van een aangepast waardetype. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Geeft aan dat de bellen een 3D-effect hebben. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Geeft aan dat de bellen een 3D-effect hebben. |
| [getExplosion()](#getExplosion--) | Geeft de hoeveelheid aan waarmee het gegevenspunt van het midden van de taart moet worden verplaatst. |
| [setExplosion(int value)](#setExplosion-int-) | Geeft de hoeveelheid aan waarmee het gegevenspunt van het midden van de taart moet worden verplaatst. |
| [getFormat()](#getFormat--) | Stelt de opmaak-eigenschappen voor. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Stelt de opmaak-eigenschappen voor. |
| [getMarker()](#getMarker--) | Geeft een datamarker aan. |
| [getSetAsTotal()](#getSetAsTotal--) | Stelt gegevenspunt in als totaal. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Stelt gegevenspunt in als totaal. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Eigenschappen van het overeenkomstige legende-item in het geval van een diagramtype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Verwijdert DataPoint uit de grafiekserie. |
| [getDataPointLevels()](#getDataPointLevels--) | Retourneert de container van gegevenspuntniveaus. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Retourneert een automatische kleur van het gegevenspunt op basis van de serienummer, gegevenspuntnummer, ParentSeriesGroup.IsColorVaried-eigenschap en diagramstijl. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Geeft aan dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Geeft aan dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. |
| [getActualX()](#getActualX--) | Geeft de werkelijke x-locatie (links) van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram weer. |
| [getActualY()](#getActualY--) | Geeft de werkelijke bovenkant van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram weer. |
| [getActualWidth()](#getActualWidth--) | Geeft de werkelijke breedte van het diagramonderdeel weer. |
| [getActualHeight()](#getActualHeight--) | Geeft de werkelijke hoogte van het diagramonderdeel weer. |
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

Retourneert de groottewaarde van het diagramgegevenspunt. Wordt gebruikt met Treemap- en Sunburst-diagrammen. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

Retourneert de kleurwaarde van het diagramgegevenspunt. Wordt gebruikt met kaartdiagrammen. Alleen-lezen [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retourneert:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Stelt de waarden van seriefoutbalken voor in het geval van een aangepast waardetype. Alleen-lezen [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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

Geeft aan dat de bellen een 3D-effect hebben. Lees/Schrijf boolean.

**Retourneert:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Geeft aan dat de bellen een 3D-effect hebben. Lees/Schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Geeft de hoeveelheid aan waarmee het gegevenspunt van het midden van de taart moet worden verplaatst. Lees/Schrijf int.

**Retourneert:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Geeft de hoeveelheid aan waarmee het gegevenspunt van het midden van de taart moet worden verplaatst. Lees/Schrijf int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Stelt de opmaak-eigenschappen voor. Lees/Schrijf [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Stelt de opmaak-eigenschappen voor. Lees/Schrijf [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Geeft een datamarker aan. Alleen-lezen [IMarker](../../com.aspose.slides/imarker).

**Retourneert:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

Stelt gegevenspunt in als totaal. Alleen van toepassing op serietype Waterfall.

**Retourneert:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Stelt gegevenspunt in als totaal. Alleen van toepassing op serietype Waterfall.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Eigenschappen van het overeenkomstige legende-item in het geval van een diagramtype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retourneert:**
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

Retourneert de container van gegevenspuntniveaus. Van toepassing op Treeamp- en Sunburst-series. Indexering van gegevenspuntniveaus begint bij nul.

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

Retourneert een automatische kleur van het gegevenspunt op basis van serienummer, gegevenspuntnummer, ParentSeriesGroup.IsColorVaried-eigenschap en diagramstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined.

**Retourneert:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Geeft aan dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. Lees/Schrijf boolean.

**Retourneert:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Geeft aan dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. Lees/Schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Geeft de werkelijke x-locatie (links) van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram weer. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden opvraagt. Alleen-lezen float.

**Retourneert:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Geeft de werkelijke bovenkant van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram weer. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden opvraagt. Alleen-lezen float.

**Retourneert:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Geeft de werkelijke breedte van het diagramonderdeel weer. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden opvraagt. Alleen-lezen float.

**Retourneert:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Geeft de werkelijke hoogte van het diagramonderdeel weer. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden opvraagt. Alleen-lezen float.

**Retourneert:**
float