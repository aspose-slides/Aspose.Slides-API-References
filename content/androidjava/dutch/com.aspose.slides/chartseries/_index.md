---
title: ChartSeries
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een grafiekreeks voor.
type: docs
url: /nl/com.aspose.slides/chartseries/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Stelt een grafiekreeks voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retourneert de bovenliggende grafiek. |
| [getExplosion()](#getExplosion--) | De afstand van een open taartpunt vanaf het centrum van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. |
| [setExplosion(int value)](#setExplosion-int-) | De afstand van een open taartpunt vanaf het centrum van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. |
| [getSmooth()](#getSmooth--) | Stelt krommeverzachting voor. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Stelt krommeverzachting voor. |
| [getName()](#getName--) | Retourneert de naam van de reeks. |
| [getDataPoints()](#getDataPoints--) | Retourneert de collectie datapoints van deze reeks. |
| [getType()](#getType--) | Retourneert een type van deze reeks. |
| [setType(int value)](#setType-int-) | Retourneert een type van deze reeks. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of deze reeks wordt weergegeven op een secundaire as. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Geeft aan of deze reeks wordt weergegeven op een secundaire as. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Retourneert het formaat van een reeks. |
| [getOrder()](#getOrder--) | Retourneert de volgorde van een reeks. |
| [setOrder(int value)](#setOrder-int-) | Retourneert de volgorde van een reeks. |
| [getLabels()](#getLabels--) | Retourneert de Labels van een reeks. |
| [getTrendLines()](#getTrendLines--) | Collectie van trendlijnen van de reeks. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Stelt ErrorBars van de reeks met richting X voor. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Stelt ErrorBars van de reeks met richting Y voor. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stelt legenda-item gerelateerd aan deze reeks voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Specificeert de vorm van een reeks van een 3-D staafgrafiek. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specificeert de vorm van een reeks van een 3-D staafgrafiek. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specificeert dat de staaf-, kolom- of bubbelreeks zijn kleuren moet inverteren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specificeert dat de staaf-, kolom- of bubbelreeks zijn kleuren moet inverteren als de waarde negatief is. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specificeert het omkeren van een effen kleur voor de reeks. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Retourneert een automatische kleur van de reeks gebaseerd op de reeksindex en grafiekstijl. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Stelt binnenpunten voor. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Stelt binnenpunten voor. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Stelt uitbijterpunten voor. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Stelt uitbijterpunten voor. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Stelt gemiddelde markers voor. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Stelt gemiddelde markers voor. |
| [getShowMeanLine()](#getShowMeanLine--) | Stelt gemiddelde lijn voor. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Stelt gemiddelde lijn voor. |
| [getQuartileMethod()](#getQuartileMethod--) | Stelt kwartielmethode voor. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Stelt kwartielmethode voor. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Stelt connectorlijnen voor. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Stelt connectorlijnen voor. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Stelt de lay-out van bovenliggende categoriënlabels voor. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Stelt de lay-out van bovenliggende categoriënlabels voor. |
| [hasUpDownBars()](#hasUpDownBars--) | Bepaalt of een Lijn- of Aandelen-grafiek up/down balken heeft. |
| [getGapWidth()](#getGapWidth--) | Specificeert de ruimte tussen staaf- of kolomclusters, als een percentage van de staaf- of kolombreedte. |
| [getGapDepth()](#getGapDepth--) | Retourneert of stelt de afstand, als een percentage van de markerbreedte, tussen de datarijken in een 3D-grafiek in. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specificeert de hoek van het eerste taart- of donutsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificeert de grootte van het gat in een donutgrafiek (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). |
| [getOverlap()](#getOverlap--) | Specificeert hoeveel staaf- en kolomoverlapping er is op 2-D grafieken, als een percentage (van -100% tot 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificeert de grootte van de tweede taart of staaf van een taart-in-taart grafiek of een staaf-in-taart grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [hasSeriesLines()](#hasSeriesLines--) | Bepaalt of er serielijnen zijn voor deze reeks en verwante reeksen. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificeert hoe de bubbelformaatwaarden worden weergegeven op de bubbeldiagram. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificeert een waarde die gebruikt moet worden om te bepalen welke datapoints in de tweede taart of staaf van een taart-in-taart of staaf-in-taart grafiek vallen. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificeert hoe te bepalen welke datapoints in de tweede taart of staaf van een taart-in-taart of staaf-in-taart grafiek vallen. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste splitsingsinformatie voor een taart-in-taart of staaf-in-taart grafiek met een aangepaste splitsing. |
| [isColorVaried()](#isColorVaried--) | Specificeert dat elke datamarker in de reeks een andere kleur heeft. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificeert de schaalfactor voor het bubbeldiagram (kan tussen 0 en 300 procent van de standaardsgrootte liggen). |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de bovenliggende grafiek. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retour:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

De afstand van een open taartpunt vanaf het centrum van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. Lezen/Schrijven int.

**Retour:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

De afstand van een open taartpunt vanaf het centrum van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Stelt krommeverzachting voor. Waar (true) als krommeverzachting is ingeschakeld voor de lijngrafiek of spreidingsgrafiek. Geldt alleen voor lijngrafieken en spreidingsgrafieken verbonden door lijnen. Lezen/Schrijven boolean.

**Retour:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Stelt krommeverzachting voor. Waar (true) als krommeverzachting is ingeschakeld voor de lijngrafiek of spreidingsgrafiek. Geldt alleen voor lijngrafieken en spreidingsgrafieken verbonden door lijnen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Retourneert de naam van de reeks. Alleen-lezen [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Retour:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Retourneert de collectie datapoints van deze reeks. Alleen-lezen [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Retour:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Retourneert een type van deze reeks. Lezen/Schrijven [ChartType](../../com.aspose.slides/charttype).

**Retour:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Retourneert een type van deze reeks. Lezen/Schrijven [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Geeft aan of deze reeks wordt weergegeven op een secundaire as. Lezen/Schrijven boolean.

**Retour:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Geeft aan of deze reeks wordt weergegeven op een secundaire as. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Alleen-lezen [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Retour:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Retourneert het formaat van een reeks. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Retour:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Retourneert de volgorde van een reeks. Lezen/Schrijven int.

**Retour:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Retourneert de volgorde van een reeks. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Retourneert de Labels van een reeks. Alleen-lezen [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Retour:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Collectie van trendlijnen van de reeks. Alleen-lezen [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines zijn beschikbaar (niet null) voor datarijen in niet-gestapelde 2-D gebied-, staaf-, kolom-, lijn-, aandelen-, xy (spreiding)- en bubbeldiagrammen. Een trendlijn is niet beschikbaar voor datarijen in enige grafiektype die gestapeld of 3-D is. Trendlines zijn ook niet beschikbaar voor radardiagrammen, taart-, oppervlak- of donutgrafieken.

**Retour:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Stelt ErrorBars van de reeks met richting X voor. Alleen-lezen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars met X-richting zijn beschikbaar voor reeksen van het type gebied, staaf, spreiding en bubbel. Voor alle andere grafiektypeën retourneert deze eigenschap null (inclusief 3D-grafieken). In het geval van aangepaste waarden gebruik de DataPoints-collectie om de waarde te specificeren (met ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap).

**Retour:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Stelt ErrorBars van de reeks met richting Y voor. Alleen-lezen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars met Y-richting zijn beschikbaar voor reeksen van het type gebied, staaf, lijn, spreiding en bubbel. Voor alle andere grafiektypeën retourneert deze eigenschap null (inclusief 3D-grafieken). In het geval van aangepaste waarden gebruik de DataPoints-collectie om de waarde te specificeren (met ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap).

**Retour:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Stelt legenda-item gerelateerd aan deze reeks voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retour:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Lezen/Schrijven String.

**Retour:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Lezen/Schrijven String.

**Retour:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Lezen/Schrijven String.

**Retour:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Lezen/Schrijven String.

**Retour:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Alleen-lezen [IMarker](../../com.aspose.slides/imarker).

**Retour:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Specificeert de vorm van een reeks van een 3-D staafgrafiek. Wijzigen van de waarde van deze eigenschap kan automatisch het Type van de reeks wijzigen. Lezen/Schrijven [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Retour:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Specificeert de vorm van een reeks van een 3-D staafgrafiek. Wijzigen van de waarde van deze eigenschap kan automatisch het Type van de reeks wijzigen. Lezen/Schrijven [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Specificeert dat de staaf-, kolom- of bubbelreeks zijn kleuren moet inverteren als de waarde negatief is. Lezen/Schrijven boolean.

**Retour:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Specificeert dat de staaf-, kolom- of bubbelreeks zijn kleuren moet inverteren als de waarde negatief is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Specificeert het omkeren van een effen kleur voor de reeks. Om de kleuraanpassing toe te passen, stel de FillType van de reeks in op FillType.Solid. Lezen/Schrijven [ColorFormat](../../com.aspose.slides/colorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Retourneert een automatische kleur van de reeks gebaseerd op de reeksindex en grafiekstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined.

**Retour:**
java.lang.Integer - The java.lang.Integer object.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Stelt binnenpunten voor. Waar (true) als binnenpunten worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Retour:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Stelt binnenpunten voor. Waar (true) als binnenpunten worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Stelt uitbijterpunten voor. Waar (true) als uitbijterpunten worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Retour:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Stelt uitbijterpunten voor. Waar (true) als uitbijterpunten worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Stelt gemiddelde markers voor. Waar (true) als gemiddelde markers worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Retour:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Stelt gemiddelde markers voor. Waar (true) als gemiddelde markers worden weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Stelt gemiddelde lijn voor. Waar (true) als gemiddelde lijn wordt weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Retour:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Stelt gemiddelde lijn voor. Waar (true) als gemiddelde lijn wordt weergegeven in de BoxAndWhisker-grafiek. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Stelt kwartielmethode voor. Geldt alleen voor BoxAndWhisker-grafieken.

**Retour:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Stelt kwartielmethode voor. Geldt alleen voor BoxAndWhisker-grafieken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Stelt connectorlijnen voor. Geldt alleen voor Waterfall-grafieken.

**Retour:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Stelt connectorlijnen voor. Geldt alleen voor Waterfall-grafieken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Stelt de lay-out van bovenliggende categoriënlabels voor. Geldt alleen voor Treemap-grafieken.

**Retour:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Stelt de lay-out van bovenliggende categoriënlabels voor. Geldt alleen voor Treemap-grafieken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Bepaalt of een Lijn- of Aandelen-grafiek up/down balken heeft. Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.UpDownBars.HasUpDownBars (Lezen/Schrijven) om de waarde te wijzigen. Gebruik de eigenschap ParentSeriesGroup.UpDownBars voor de opmaak van up/down balken. Alleen-lezen boolean.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Retour:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Specificeert de ruimte tussen staaf- of kolomclusters, als een percentage van de staaf- of kolombreedte. Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.GapWidth (Lezen/Schrijven) om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.GapWidth.

**Retour:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Retourneert of stelt de afstand, als een percentage van de markerbreedte, tussen de datarijen in een 3D-grafiek in. Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.GapDepth (Lezen/Schrijven) om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.GapDepth.

**Retour:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Specificeert de hoek van het eerste taart- of donutsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.FirstSliceAngle (Lezen/Schrijven) om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.FirstSliceAngle.

**Retour:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Specificeert de grootte van het gat in een donutgrafiek (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.DoughnutHoleSize (Lezen/Schrijven) om de waarde te wijzigen. Alleen-lezen byte.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.DoughnutHoleSize.

**Retour:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Specificeert hoeveel staaf- en kolomoverlapping er is op 2-D grafieken, als een percentage (van -100% tot 100%). Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep. Het is een projectie van de overeenkomstige eigenschap in de bovenliggende reeksgroep, en daarom is deze eigenschap alleen-lezen. Om de waarde te wijzigen, gebruik de eigenschap ParentSeriesGroup.Overlap (Lezen/Schrijven). Alleen-lezen byte.

--------------------

Overlap specificeert de mate van overlapping of spatiëring tussen staaf- en kolommen als een percentage van hun breedte:
- -100%: Maximale spatiëring (staafjes zijn volledig gescheiden).
- 0%: Staafjes staan naast elkaar zonder overlapping of spatiëring.
- 100%: Maximale overlapping (staafjes overlappen volledig). Dit is een projectie van de eigenschap ParentSeriesGroup.Overlap.

**Retour:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Specificeert de grootte van de tweede taart of staaf van een taart-in-taart grafiek of een staaf-in-taart grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.SecondPieSize (Lezen/Schrijven) om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.SecondPieSize.

**Retour:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public  …  ... This  ...

```

Bepaalt of er serielijnen zijn voor deze reeks en verwante reeksen. Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.HasSeriesLines (Lezen/Schrijven) om de waarde te wijzigen. Gebruik de eigenschap ParentSeriesGroup.SeriesLinesFormat voor de opmaak van serielijnen. Alleen-lezen boolean.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.HasSeriesLines.

**Retour:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Specificeert hoe de bubbelformaatwaarden worden weergegeven op de bubbeldiagram. Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.BubbleSizeRepresentation (Lezen/Schrijven) om de waarde te wijzigen.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.BubbleSizeRepresentation.

**Retour:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Specificeert een waarde die gebruikt moet worden om te bepalen welke datapoints in de tweede taart of staaf van een taart-in-taart of staaf-in-taart grafiek vallen. Wordt gebruikt samen met de eigenschap PieSplitBy. Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.PieSplitPosition (Lezen/Schrijven) om de waarde te wijzigen. Alleen-lezen double.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitPosition.

**Retour:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Specificeert hoe te bepalen welke datapoints in de tweede taart of staaf van een taart-in-taart of staaf-in-taart grafiek vallen. Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.PieSplitBy (Lezen/Schrijven) om de waarde te wijzigen. Alleen-lezen [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitBy. 2) Als de eigenschapswaarde PieSplitType.Custom is, kunt u aangepaste splitsingsinformatie definiëren met de eigenschap ParentSeriesGroup.PieSplitCustomPoints.

**Retour:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

De aangepaste splitsingsinformatie voor een taart-in-taart of staaf-in-taart grafiek met een aangepaste splitsing. Bevat datapoints die in de tweede taart of staaf van een taart-in-taart of staaf-in-taart grafiek moeten worden getekend. Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap Alleen-lezen [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.PieSplitCustomPoints.

**Retour:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Specificeert dat elke datamarker in de reeks een andere kleur heeft. Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.IsColorVaried (Lezen/Schrijven) om de waarde te wijzigen. Alleen-lezen boolean.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.IsColorVaried.

**Retour:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specificeert de schaalfactor voor het bubbeldiagram (kan tussen 0 en 300 procent van de standaardsgrootte liggen). Deze eigenschap is niet alleen van deze reeks, maar van alle reeksen van de bovenliggende reeksgroep – dit is de projectie van de overeenkomstige groepseigenschap. Daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap ParentSeriesGroup om toegang te krijgen tot de bovenliggende reeksgroep. Gebruik de eigenschap ParentSeriesGroup.BubbleSizeScale (Lezen/Schrijven) om de waarde te wijzigen.

--------------------

Dit is de projectie van de eigenschap ParentSeriesGroup.BubbleSizeScale.

**Retour:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een FillFormat. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retour:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een FillFormat. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)