---
title: IChartSeries
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een grafiekreeks.
type: docs
url: /nl/com.aspose.slides/ichartseries/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Vertegenwoordigt een grafiekreeks.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getExplosion()](#getExplosion--) | De afstand van een open taartpunt vanaf het midden van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. |
| [setExplosion(int value)](#setExplosion-int-) | De afstand van een open taartpunt vanaf het midden van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. |
| [getSmooth()](#getSmooth--) | Stelt curvegladmaken voor. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Stelt curvegladmaken voor. |
| [getMarker()](#getMarker--) | Geeft seriemarker terug. |
| [getBar3DShape()](#getBar3DShape--) | Specificeert de vorm van een serie van een 3-D-balkgrafiek. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specificeert de vorm van een serie van een 3-D-balkgrafiek. |
| [getName()](#getName--) | Geeft de naam van de serie terug. |
| [getDataPoints()](#getDataPoints--) | Retourneert collectie van gegevenspunten van deze serie. |
| [getType()](#getType--) | Retourneert een type van deze serie. |
| [setType(int value)](#setType-int-) | Retourneert een type van deze serie. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Retourneert de bovenliggende seriesgroep. |
| [getFormat()](#getFormat--) | Retourneert het formaat van een serie. |
| [getOrder()](#getOrder--) | Retourneert de volgorde van een serie. |
| [setOrder(int value)](#setOrder-int-) | Retourneert de volgorde van een serie. |
| [getLabels()](#getLabels--) | Retourneert de labels van een serie. |
| [getTrendLines()](#getTrendLines--) | Collectie van serietrendlijnen Alleen-lezen [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Stelt ErrorBars van serie met richting X voor. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Stelt ErrorBars van serie met richting Y voor. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of deze serie wordt geplot op de tweede waardenas. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Geeft aan of deze serie wordt geplot op de tweede waardenas. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Retourneert of stelt het getalformaat in voor serie-waarden. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Retourneert of stelt het getalformaat in voor serie-waarden. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Retourneert of stelt het getalformaat in voor x-waarden van de serie. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Retourneert of stelt het getalformaat in voor x-waarden van de serie. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Retourneert of stelt het getalformaat in voor y-waarden van de serie. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Retourneert of stelt het getalformaat in voor y-waarden van de serie. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Retourneert of stelt het getalformaat in voor bubbelgroottes van de serie. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Retourneert of stelt het getalformaat in voor bubbelgroottes van de serie. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specificeert dat de balk-, kolom- of bubbelserie zijn kleuren moet omkeren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specificeert dat de balk-, kolom- of bubbelserie zijn kleuren moet omkeren als de waarde negatief is. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specificeert omgekeerde effen kleur voor serie. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stelt legende-item gerelateerd aan deze serie voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Retourneert een automatische kleur van serie gebaseerd op serie-index en grafiekstijl. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Stelt innerlijke punten voor. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Stelt innerlijke punten voor. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Stelt uitschieterpunten voor. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Stelt uitschieterpunten voor. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Stelt gemiddelde markeringen voor. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Stelt gemiddelde markeringen voor. |
| [getShowMeanLine()](#getShowMeanLine--) | Stelt gemiddelde markeringen voor. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Stelt gemiddelde markeringen voor. |
| [getQuartileMethod()](#getQuartileMethod--) | Stelt kwartielmethode voor. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Stelt kwartielmethode voor. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Stelt verbindingslijnen voor. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Stelt verbindingslijnen voor. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Stelt lay-out van bovenliggende categorie-labels voor. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Stelt lay-out van bovenliggende categorie-labels voor. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 % van de standaardgrootte liggen). |
| [hasUpDownBars()](#hasUpDownBars--) | Bepaalt of een lijn- of aandelen-grafiek up/down-balken heeft. |
| [getGapWidth()](#getGapWidth--) | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de balk- of kolombreedte. |
| [getGapDepth()](#getGapDepth--) | Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensreeksen in een 3-D-grafiek. |
| [isColorVaried()](#isColorVaried--) | Specificeert dat elke datamarker in de serie een andere kleur heeft. |
| [hasSeriesLines()](#hasSeriesLines--) | Bepaalt of er serielijnen zijn voor deze serie en verwante series. |
| [getOverlap()](#getOverlap--) | Specificeert hoeveel balken en kolommen overlappen op 2-D-grafieken, als een percentage (van -100 % tot 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificeert de grootte van de tweede taart of balk van een pie-of-pie-grafiek of een bar-of-pie-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 % en 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificeert een waarde die wordt gebruikt om te bepalen welke gegevenspunten in de tweede taart of balk van een pie-of-pie- of bar-of-pie-grafiek vallen. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificeert hoe te bepalen welke gegevenspunten in de tweede taart of balk van een pie-of-pie- of bar-of-pie-grafiek vallen. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificeert de grootte van de gat in een donutgrafiek (kan tussen 10 % en 90 % van de grootte van het plot-gebied liggen). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specificeert de hoek van het eerste taart- of donut-grafieksegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste splitsingsinformatie voor een pie-of-pie- of bar-of-pie-grafiek met een aangepaste splitsing. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificeert hoe de bubbelgrootte-waarden worden weergegeven op de bubbelgrafiek. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

De afstand van een open taartpunt vanaf het midden van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. Lezen/Schrijven int.

**Retour:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

De afstand van een open taartpunt vanaf het midden van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. Lezen/Schrijven int.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Stelt curvegladmaken voor. Waarbij true als curvegladmaken is ingeschakeld voor de lijngrafiek of spreidingsgrafiek. Geldt alleen voor lijngrafieken en spreidingsgrafieken die met lijnen verbonden zijn. Lezen/Schrijven boolean.

**Retour:**  
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Stelt curvegladmaken voor. Waarbij true als curvegladmaken is ingeschakeld voor de lijngrafiek of spreidingsgrafiek. Geldt alleen voor lijngrafieken en spreidingsgrafieken die met lijnen verbonden zijn. Lezen/Schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Geeft seriemarker terug. Alleen-lezen [IMarker](../../com.aspose.slides/imarker).

**Retour:**  
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Specificeert de vorm van een serie van een 3-D-balkgrafiek. Het wijzigen van de waarde van deze eigenschap kan automatisch het type van de serie wijzigen. Lezen/Schrijven [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Retour:**  
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Specificeert de vorm van een serie van een 3-D-balkgrafiek. Het wijzigen van de waarde van deze eigenschap kan automatisch het type van de serie wijzigen. Lezen/Schrijven [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Geeft de naam van de serie terug. Alleen-lezen [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Retour:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Retourneert collectie van gegevenspunten van deze serie. Alleen-lezen [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Retour:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Retourneert een type van deze serie. Lezen/Schrijven [ChartType](../../com.aspose.slides/charttype).

**Retour:**  
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Retourneert een type van deze serie. Lezen/Schrijven [ChartType](../../com.aspose.slides/charttype).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Retourneert de bovenliggende seriesgroep. Alleen-lezen [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Retour:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Retourneert het formaat van een serie. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Retour:**  
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Retourneert de volgorde van een serie. Lezen/Schrijven int.

**Retour:**  
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Retourneert de volgorde van een serie. Lezen/Schrijven int.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Retourneert de labels van een serie. Alleen-lezen [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Retour:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Collectie van serietrendlijnen Alleen-lezen [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Retour:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Stelt ErrorBars van serie met richting X voor. Alleen-lezen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars met X-richting zijn beschikbaar voor series van type area, bar, scatter en bubble. Voor alle andere grafiektype-s retourneert deze eigenschap null (inclusief 3-D-grafieken). Bij aangepaste waarden moet de DataPoints-collectie worden gebruikt om de waarde te specificeren (met ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap).

**Retour:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Stelt ErrorBars van serie met richting Y voor. Alleen-lezen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars met Y-richting zijn beschikbaar voor series van type area, bar, line, scatter en bubble. Voor alle andere grafiektype-s retourneert deze eigenschap null (inclusief 3-D-grafieken). Bij aangepaste waarden moet de DataPoints-collectie worden gebruikt om de waarde te specificeren (met ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap).

**Retour:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Geeft aan of deze serie wordt geplot op de tweede waardenas. Lezen/Schrijven boolean.

**Retour:**  
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Geeft aan of deze serie wordt geplot op de tweede waardenas. Lezen/Schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Retourneert of stelt het getalformaat in voor serie-waarden. Lezen/Schrijven String.

**Retour:**  
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Retourneert of stelt het getalformaat in voor serie-waarden. Lezen/Schrijven String.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Retourneert of stelt het getalformaat in voor x-waarden van de serie. Lezen/Schrijven String.

**Retour:**  
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Retourneert of stelt het getalformaat in voor x-waarden van de serie. Lezen/Schrijven String.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Retourneert of stelt het getalformaat in voor y-waarden van de serie. Lezen/Schrijven String.

**Retour:**  
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Retourneert of stelt het getalformaat in voor y-waarden van de serie. Lezen/Schrijven String.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Retourneert of stelt het getalformaat in voor bubbelgroottes van de serie. Lezen/Schrijven String.

**Retour:**  
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Retourneert of stelt het getalformaat in voor bubbelgroottes van de serie. Lezen/Schrijven String.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Specificeert dat de balk-, kolom- of bubbelserie zijn kleuren moet omkeren als de waarde negatief is. Lezen/Schrijven boolean.

**Retour:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Specificeert dat de balk-, kolom- of bubbelserie zijn kleuren moet omkeren als de waarde negatief is. Lezen/Schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Specificeert omgekeerde effen kleur voor serie. Om de kleuring toe te passen, stel serie-formaat.FillType in op FillType.Solid. Lezen/Schrijven [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Stelt legende-item gerelateerd aan deze serie voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retour:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Retourneert een automatische kleur van serie gebaseerd op serie-index en grafiekstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined.

**Retour:**  
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Stelt innerlijke punten voor. Waarbij true als innerlijke punten worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Retour:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Stelt innerlijke punten voor. Waarbij true als innerlijke punten worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Stelt uitschieterpunten voor. Waarbij true als uitschieterpunten worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Retour:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Stelt uitschieterpunten voor. Waarbij true als uitschieterpunten worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Stelt gemiddelde markeringen voor. Waarbij true als gemiddelde markeringen worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Retour:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Stelt gemiddelde markeringen voor. Waarbij true als gemiddelde markeringen worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Stelt gemiddelde markeringen voor. Waarbij true als gemiddelde lijn wordt weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Retour:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Stelt gemiddelde markeringen voor. Waarbij true als gemiddelde lijn wordt weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Stelt kwartielmethode voor. Geldt alleen voor BoxAndWhisker-grafieken.

**Retour:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Stelt kwartielmethode voor. Geldt alleen voor BoxAndWhisker-grafieken.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Stelt verbindingslijnen voor. Geldt alleen voor Waterfall-grafieken.

**Retour:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Stelt verbindingslijnen voor. Geldt alleen voor Waterfall-grafieken.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Stelt lay-out van bovenliggende categorie-labels voor. Geldt alleen voor Treemap-grafieken.

**Retour:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Stelt lay-out van bovenliggende categorie-labels voor. Geldt alleen voor Treemap-grafieken.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 % van de standaardgrootte liggen). Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.BubbleSizeScale Lezen/Schrijven-eigenschap om de waarde te wijzigen.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.BubbleSizeScale.

**Retour:**  
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Bepaalt of een lijn- of aandelen-grafiek up/down-balken heeft. Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.UpDownBars.HasUpDownBars Lezen/Schrijven-eigenschap om de waarde te wijzigen. Gebruik ParentSeriesGroup.UpDownBars eigenschap voor het opmaken van up/down-balken. Alleen-lezen boolean.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Retour:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de balk- of kolombreedte. Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.GapWidth Lezen/Schrijven-eigenschap om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.GapWidth.

**Retour:**  
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensreeksen in een 3-D-grafiek. Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.GapDepth Lezen/Schrijven-eigenschap om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.GapDepth.

**Retour:**  
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Specificeert dat elke datamarker in de serie een andere kleur heeft. Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.IsColorVaried Lezen/Schrijven-eigenschap om de waarde te wijzigen. Alleen-lezen boolean.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.IsColorVaried.

**Retour:**  
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Bepaalt of er serielijnen zijn voor deze serie en verwante series. Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.HasSeriesLines Lezen/Schrijven-eigenschap om de waarde te wijzigen. Gebruik ParentSeriesGroup.SeriesLinesFormat eigenschap voor het opmaken van serielijnen. Alleen-lezen boolean.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.HasSeriesLines.

**Retour:**  
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Specificeert hoeveel balken en kolommen overlappen op 2-D-grafieken, als een percentage (van -100 % tot 100 %). Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep. Het is een projectie van de overeenkomstige eigenschap in de bovenliggende seriesgroep, en daarom is deze eigenschap Alleen-lezen. Om de waarde te wijzigen, gebruik de eigenschap ParentSeriesGroup.Overlap Lezen/Schrijven. Alleen-lezen byte.

--------------------

Overlap specificeert de mate van overlapping of afstand tussen balken en kolommen als een percentage van hun breedte: -100 %: maximale afstand (balken zijn volledig gescheiden). 0 %: balken naast elkaar zonder overlapping of afstand. 100 %: maximale overlapping (balken overlappen volledig). Dit is een projectie van de eigenschap ParentSeriesGroup.Overlap.

**Retour:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Specificeert de grootte van de tweede taart of balk van een pie-of-pie-grafiek of een bar-of-pie-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 % en 200 % liggen). Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.SecondPieSize Lezen/Schrijven-eigenschap om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.SecondPieSize.

**Retour:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specificeert een waarde die wordt gebruikt om te bepalen welke gegevenspunten in de tweede taart of balk van een pie-of-pie- of bar-of-pie-grafiek vallen. Wordt gebruikt samen met de eigenschap PieSplitBy. Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.PieSplitPosition Lezen/Schrijven-eigenschap om de waarde te wijzigen. Alleen-lezen double.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitPosition.

**Retour:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specificeert hoe te bepalen welke gegevenspunten in de tweede taart of balk van een pie-of-pie- of bar-of-pie-grafiek vallen. Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.PieSplitBy Lezen/Schrijven-eigenschap om de waarde te wijzigen. Alleen-lezen [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitBy. 2) Als de eigenschapwaarde PieSplitType.Custom is, kun je aangepaste splitsingsinformatie definiëren met de eigenschap ParentSeriesGroup.PieSplitCustomPoints.

**Retour:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specificeert de grootte van het gat in een donutgrafiek (kan tussen 10 % en 90 % van de grootte van het plot-gebied liggen). Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.DoughnutHoleSize Lezen/Schrijven-eigenschap om de waarde te wijzigen. Alleen-lezen byte.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.DoughnutHoleSize.

**Retour:**  
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Specificeert de hoek van het eerste taart- of donut-segment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.FirstSliceAngle Lezen/Schrijven-eigenschap om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.FirstSliceAngle.

**Retour:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

De aangepaste splitsingsinformatie voor een pie-of-pie- of bar-of-pie-grafiek met een aangepaste splitsing. Bevat gegevenspunten die in de tweede taart of balk van een pie-of-pie- of bar-of-pie-grafiek moeten worden getekend. Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap Alleen-lezen [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitCustomPoints.

**Retour:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Specificeert hoe de bubbelgrootte-waarden worden weergegeven op de bubbelgrafiek. Dit is niet alleen een eigenschap van deze serie maar van alle series van de bovenliggende seriesgroep – dit is een projectie van de overeenkomstige groeps-eigenschap. Daarom is deze eigenschap Alleen-lezen. Gebruik de eigenschap ParentSeriesGroup voor toegang tot de bovenliggende seriesgroep. Gebruik ParentSeriesGroup.BubbleSizeRepresentation Lezen/Schrijven-eigenschap om de waarde te wijzigen.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.BubbleSizeRepresentation.

**Retour:**  
int