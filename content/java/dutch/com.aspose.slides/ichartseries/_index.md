---
title: IChartSeries
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een grafiekreeks voor.
type: docs
url: /nl/com.aspose.slides/ichartseries/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Stelt een diagramreeks voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getExplosion()](#getExplosion--) | De afstand van een open taartpunt van het midden van het taartdiagram wordt uitgedrukt als een percentage van de taartdiameter. |
| [setExplosion(int value)](#setExplosion-int-) | De afstand van een open taartpunt van het midden van het taartdiagram wordt uitgedrukt als een percentage van de taartdiameter. |
| [getSmooth()](#getSmooth--) | Stelt curvegladstrijken voor. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Stelt curvegladstrijken voor. |
| [getMarker()](#getMarker--) | Retourneert reeksmarker. |
| [getBar3DShape()](#getBar3DShape--) | Specificeert de vorm van een reeks van een 3D-balkdiagram. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specificeert de vorm van een reeks van een 3D-balkdiagram. |
| [getName()](#getName--) | Retourneert reeksnaam. |
| [getDataPoints()](#getDataPoints--) | Retourneert verzameling gegevenspunten van deze reeks. |
| [getType()](#getType--) | Retourneert een type van deze reeks. |
| [setType(int value)](#setType-int-) | Retourneert een type van deze reeks. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Retourneert bovenliggende reeksgroep. |
| [getFormat()](#getFormat--) | Retourneert het formaat van een reeks. |
| [getOrder()](#getOrder--) | Retourneert de volgorde van een reeks. |
| [setOrder(int value)](#setOrder-int-) | Retourneert de volgorde van een reeks. |
| [getLabels()](#getLabels--) | Retourneert de labels van een reeks. |
| [getTrendLines()](#getTrendLines--) | Verzameling van reekstrendlijnen Alleen-lezen [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Stelt foutbalken van de reeks met richting X voor. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Stelt foutbalken van de reeks met richting Y voor. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of deze reeks op een tweede waardenas wordt geplot. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Geeft aan of deze reeks op een tweede waardenas wordt geplot. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Retourneert of stelt het getalformaat in voor reekswerte. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Retourneert of stelt het getalformaat in voor reekswerte. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Retourneert of stelt het getalformaat in voor x-waarden van de reeks. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Retourneert of stelt het getalformaat in voor x-waarden van de reeks. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Retourneert of stelt het getalformaat in voor y-waarden van de reeks. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Retourneert of stelt het getalformaat in voor y-waarden van de reeks. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Retourneert of stelt het getalformaat in voor bubbelgroottes van de reeks. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Retourneert of stelt het getalformaat in voor bubbelgroottes van de reeks. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specificeert dat de balk-, kolom- of bubbelreeks zijn kleuren moet omkeren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specificeert dat de balk-, kolom- of bubbelreeks zijn kleuren moet omkeren als de waarde negatief is. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specificeert het omkeren van de vulkleur voor de reeks. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stelt legende-item gerelateerd aan deze reeks voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Retourneert een automatische kleur van de reeks gebaseerd op reeksendex en diagramstijl. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Stelt binnenste punten voor. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Stelt binnenste punten voor. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Stelt uitschieterpunten voor. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Stelt uitschieterpunten voor. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Stelt gemiddelde markers voor. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Stelt gemiddelde markers voor. |
| [getShowMeanLine()](#getShowMeanLine--) | Stelt gemiddelde markers voor. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Stelt gemiddelde markers voor. |
| [getQuartileMethod()](#getQuartileMethod--) | Stelt kwartielmethode voor. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Stelt kwartielmethode voor. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Stelt connectorlijnen voor. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Stelt connectorlijnen voor. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Stelt de lay-out van bovenliggende categorielabels voor. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Stelt de lay-out van bovenliggende categorielabels voor. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [hasUpDownBars()](#hasUpDownBars--) | Bepaalt of een lijn- of aandelen-diagram op/naar beneden balken heeft. |
| [getGapWidth()](#getGapWidth--) | Specificeert de ruimte tussen balk- of kolomclusters, als percentage van de balk- of kolombreedte. |
| [getGapDepth()](#getGapDepth--) | Retourneert of stelt de afstand in, als percentage van de markerbreedte, tussen de gegevensreeksen in een 3D-diagram. |
| [isColorVaried()](#isColorVaried--) | Specificeert dat elke gegevensmarker in de reeks een andere kleur heeft. |
| [hasSeriesLines()](#hasSeriesLines--) | Bepaalt of er serielijnen zijn voor deze reeks en verwante reeksen. |
| [getOverlap()](#getOverlap--) | Specificeert hoeveel balken en kolommen overlappen op 2D-diagrammen, als percentage (van -100% tot 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificeert de grootte van de tweede taart of balk van een taart-in-taart-diagram of een balk-in-taart-diagram, als percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten in de tweede taart of balk staan in een taart-in-taart- of balk-in-taart-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificeert hoe te bepalen welke gegevenspunten in de tweede taart of balk staan in een taart-in-taart- of balk-in-taart-diagram. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificeert de grootte van het gat in een donutdiagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specificeert de hoek van de eerste taart- of donutdiagramsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste split-informatie voor een taart-in-taart- of balk-in-taart-diagram met een aangepaste split. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificeert hoe de bubbelgroottwaarden worden weergegeven op het bubbel-diagram. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

De afstand van een open taartpunt van het midden van het taartdiagram wordt uitgedrukt als een percentage van de taartdiameter. Alleen-lezen int.

**Returns:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

De afstand van een open taartpunt van het midden van het taartdiagram wordt uitgedrukt als een percentage van de taartdiameter. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Stelt curvegladstrijken voor. Waar als curvegladstrijken is ingeschakeld voor het lijndiagram of spreidingsdiagram. Geldt alleen voor lijndiagrammen en spreidingsdiagrammen die met lijnen verbonden zijn. Lezen/schrijven boolean.

**Returns:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Stelt curvegladstrijken voor. Waar als curvegladstrijken is ingeschakeld voor het lijndiagram of spreidingsdiagram. Geldt alleen voor lijndiagrammen en spreidingsdiagrammen die met lijnen verbonden zijn. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Retourneert reeksmarker. Alleen-lezen [IMarker](../../com.aspose.slides/imarker).

**Returns:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Specificeert de vorm van een reeks van een 3D-balkdiagram. Het wijzigen van de waarde van deze eigenschap kan automatisch het type van de reeks wijzigen. Lezen/schrijven [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returns:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Specificeert de vorm van een reeks van een 3D-balkdiagram. Het wijzigen van de waarde van deze eigenschap kan automatisch het type van de reeks wijzigen. Lezen/schrijven [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Retourneert reeksnaam. Alleen-lezen [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returns:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Retourneert verzameling gegevenspunten van deze reeks. Alleen-lezen [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Returns:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

Retourneert een type van deze reeks. Lezen/schrijven [ChartType](../../com.aspose.slides/charttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Retourneert een type van deze reeks. Lezen/schrijven [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Retourneert bovenliggende reeksgroep. Alleen-lezen [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Returns:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Retourneert het formaat van een reeks. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Retourneert de volgorde van een reeks. Lezen/schrijven int.

**Returns:**
int
### setOrder(int value) {#setOrder-int-}
```java
public abstract void setOrder(int value)
```

Retourneert de volgorde van een reeks. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Retourneert de labels van een reeks. Alleen-lezen [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Returns:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Verzameling van reekstrendlijnen Alleen-lezen [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Returns:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Stelt foutbalken van de reeks met richting X voor. Alleen-lezen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars met X-richting zijn beschikbaar voor reeksen van het type area, bar, scatter en bubble. Voor alle andere diagramtypen retourneert deze eigenschap null (inclusief 3D-diagrammen). In het geval van aangepaste waarden gebruik de DataPoints-collectie om de waarde te specificeren (met de ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap).

**Returns:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Stelt foutbalken van de reeks met richting Y voor. Alleen-lezen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars met Y-richting zijn beschikbaar voor reeksen van het type area, bar, line, scatter en bubble. Voor alle andere diagramtypen retourneert deze eigenschap null (inclusief 3D-diagrammen). In het geval van aangepaste waarden gebruik de DataPoints-collectie om de waarde te specificeren (met de ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap).

**Returns:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Geeft aan of deze reeks op een tweede waardenas wordt geplot. Lezen/schrijven boolean.

**Returns:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Geeft aan of deze reeks op een tweede waardenas wordt geplot. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Retourneert of stelt het getalformaat in voor reekswerte. Lezen/schrijven String.

**Returns:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Retourneert of stelt het getalformaat in voor reekswerte. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Retourneert of stelt het getalformaat in voor x-waarden van de reeks. Lezen/schrijven String.

**Returns:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Retourneert of stelt het getalformaat in voor x-waarden van de reeks. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Retourneert of stelt het getalformaat in voor y-waarden van de reeks. Lezen/schrijven String.

**Returns:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Retourneert of stelt het getalformaat in voor y-waarden van de reeks. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Retourneert of stelt het getalformaat in voor bubbelgroottes van de reeks. Lezen/schrijven String.

**Returns:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Retourneert of stelt het getalformaat in voor bubbelgroottes van de reeks. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Specificeert dat de balk-, kolom- of bubbelreeks zijn kleuren moet omkeren als de waarde negatief is. Lezen/schrijven boolean.

**Returns:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Specificeert dat de balk-, kolom- of bubbelreeks zijn kleuren moet omkeren als de waarde negatief is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Specificeert het omkeren van de vulkleur voor de reeks. Om de kleuring toe te passen, stel de FillType van de reeks in op FillType.Solid. Lezen/schrijven [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Stelt legende-item gerelateerd aan deze reeks voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Retourneert een automatische kleur van de serie op basis van de serie-index en diagramstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined.

**Retour:**
java.awt.Color - Automatische kleur van de serie java.awt.Color

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Stelt interne punten voor. Waar als interne punten worden weergegeven in het BoxAndWhisker-diagram. Geldt alleen voor BoxAndWhisker-diagrammen. Lezen/Schrijven boolean.

**Retour:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Stelt interne punten voor. Waar als interne punten worden weergegeven in het BoxAndWhisker-diagram. Geldt alleen voor BoxAndWhisker-diagrammen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Stelt uitschieters voor. Waar als uitschieters worden weergegeven in het BoxAndWhisker-diagram. Geldt alleen voor BoxAndWhisker-diagrammen. Lezen/Schrijven boolean.

**Retour:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Stelt uitschieters voor. Waar als uitschieters worden weergegeven in het BoxAndWhisker-diagram. Geldt alleen voor BoxAndWhisker-diagrammen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Stelt gemiddelde markeringen voor. Waar als gemiddelde markeringen worden weergegeven in het BoxAndWhisker-diagram. Geldt alleen voor BoxAndWhisker-diagrammen. Lezen/Schrijven boolean.

**Retour:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Stelt gemiddelde markeringen voor. Waar als gemiddelde markeringen worden weergegeven in het BoxAndWhisker-diagram. Geldt alleen voor BoxAndWhisker-diagrammen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Stelt gemiddelde markeringen voor. Waar als gemiddelde lijn wordt weergegeven in het BoxAndWhisker-diagram. Geldt alleen voor BoxAndWhisker-diagrammen. Lezen/Schrijven boolean.

**Retour:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Stelt gemiddelde markeringen voor. Waar als gemiddelde lijn wordt weergegeven in het BoxAndWhisker-diagram. Geldt alleen voor BoxAndWhisker-diagrammen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Stelt kwantielmethode voor. Geldt alleen voor BoxAndWhisker-diagrammen.

**Retour:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Stelt kwantielmethode voor. Geldt alleen voor BoxAndWhisker-diagrammen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Stelt verbindingslijnen voor. Geldt alleen voor Waterfall-diagrammen.

**Retour:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Stelt verbindingslijnen voor. Geldt alleen voor Waterfall-diagrammen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Stelt de lay-out van bovenliggende categoriënlabels voor. Geldt alleen voor Treemap-diagrammen.

**Retour:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Stelt de lay-out van bovenliggende categoriënlabels voor. Geldt alleen voor Treemap-diagrammen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 % van de standaardgrootte liggen). Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.BubbleSizeScale om de waarde te wijzigen.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.BubbleSizeScale.

**Retour:**
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Bepaalt of een lijn- of aandelen-diagram omhoog/omlaag-balken heeft. Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.UpDownBars.HasUpDownBars om de waarde te wijzigen. Gebruik de eigenschap ParentSeriesGroup.UpDownBars voor de opmaak van omhoog/omlaag-balken. Alleen-lees boolean.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Retour:**
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de breedte van de balk of kolom. Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.GapWidth om de waarde te wijzigen. Alleen-lees int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.GapWidth.

**Retour:**
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Retourneert of stelt de afstand in, als een percentage van de markeerbreedte, tussen de dataseries in een 3D-diagram. Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.GapDepth om de waarde te wijzigen. Alleen-lees int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.GapDepth.

**Retour:**
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Specificeert dat elke datamarker in de serie een andere kleur heeft. Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.IsColorVaried om de waarde te wijzigen. Alleen-lees boolean.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.IsColorVaried.

**Retour:**
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Bepaalt of er serielijnen zijn voor deze serie en verwante series. Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.HasSeriesLines om de waarde te wijzigen. Gebruik de eigenschap ParentSeriesGroup.SeriesLinesFormat voor de opmaak van serielijnen. Alleen-lees boolean.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.HasSeriesLines.

**Retour:**
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Specificeert hoeveel balken en kolommen elkaar overlappen in 2-D-diagrammen, als een percentage (van -100 % tot 100 %). Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep. Het is een projectie van de overeenkomstige eigenschap in de bovenliggende seriesgroep, en daarom is deze eigenschap alleen-lees. Om de waarde te wijzigen, gebruik de lees/schrijf-eigenschap ParentSeriesGroup.Overlap. Alleen-lees byte.

--------------------

Overlap specificeert de mate van overlapping of afstand tussen balken en kolommen als een percentage van hun breedte:
- -100 %: maximale afstand (balken zijn volledig gescheiden).
- 0 %: balken staan naast elkaar zonder overlapping of afstand.
- 100 %: maximale overlapping (balken overlappen volledig). Dit is een projectie van de eigenschap ParentSeriesGroup.Overlap.

**Retour:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Specificeert de grootte van de tweede taart of balk van een pie-of-pie-diagram of een balk-of-pie-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 % liggen). Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.SecondPieSize om de waarde te wijzigen. Alleen-lees int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.SecondPieSize.

**Retour:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten in de tweede taart of balk staan in een pie-of-pie- of balk-of-pie-diagram. Wordt samen met de eigenschap PieSplitBy gebruikt. Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.PieSplitPosition om de waarde te wijzigen. Alleen-lees double.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitPosition.

**Retour:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specificeert hoe bepaald wordt welke gegevenspunten in de tweede taart of balk staan in een pie-of-pie- of balk-of-pie-diagram. Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.PieSplitBy om de waarde te wijzigen. Alleen-lees [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitBy. 2) Als de eigenschapswaarde PieSplitType.Custom is, kun je aangepaste splitsingsinformatie definiëren met de eigenschap ParentSeriesGroup.PieSplitCustomPoints.

**Retour:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specificeert de grootte van het gat in een donuts-diagram (kan tussen 10 en 90 % van de grootte van het plotgebied liggen). Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.DoughnutHoleSize om de waarde te wijzigen. Alleen-lees byte.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.DoughnutHoleSize.

**Retour:**
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Specificeert de hoek van het eerste taart- of donuts-diagramsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Deze eigenschap is daarom alleen-lees. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik de lees/schrijf-eigenschap ParentSeriesGroup.FirstSliceAngle om de waarde te wijzigen. Alleen-lees int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.FirstSliceAngle.

**Retour:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

De aangepaste splitsingsinformatie voor een pie-of-pie- of balk-of-pie-diagram met een aangepaste splitsing. Bevat gegevenspunten die getekend moeten worden in de tweede taart of balk. Dit is niet alleen een eigenschap van deze serie, maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Alleen-lees [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitCustomPoints.

**Retour:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Specifies how the bubble size values are represented on the bubble chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.BubbleSizeRepresentation.

**Retour:**
int