---
title: ChartSeries
second_title: Aspose.Slides voor Java API-referentie
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
| [getExplosion()](#getExplosion--) | De afstand van een geopend taartpunt van het middelpunt van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. |
| [setExplosion(int value)](#setExplosion-int-) | De afstand van een geopend taartpunt van het middelpunt van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. |
| [getSmooth()](#getSmooth--) | Geeft curve smoothing weer. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Geeft curve smoothing weer. |
| [getName()](#getName--) | Retourneert de naam van de reeks. |
| [getDataPoints()](#getDataPoints--) | Retourneert de verzameling gegevenspunten van deze reeks. |
| [getType()](#getType--) | Retourneert een type van deze reeks. |
| [setType(int value)](#setType-int-) | Retourneert een type van deze reeks. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of deze reeks wordt weergegeven op een secundaire as. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Geeft aan of deze reeks wordt weergegeven op een secundaire as. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Retourneert het formaat van een reeks. |
| [getOrder()](#getOrder--) | Retourneert de volgorde van een reeks. |
| [setOrder(int value)](#setOrder-int-) | Retourneert de volgorde van een reeks. |
| [getLabels()](#getLabels--) | Retourneert de Labels van een reeks. |
| [getTrendLines()](#getTrendLines--) | Verzameling van trendlijnen van de reeks. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Stelt ErrorBars van de reeks met richtings X voor. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Stelt ErrorBars van de reeks met richtings Y voor. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stelt legende-item gerelateerd aan deze reeks voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Specificeert de vorm van een reeks van een 3D-staafgrafiek. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specificeert de vorm van een reeks van een 3D-staafgrafiek. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specificeert dat de staaf-, kolom- of bubbelreeks zijn kleuren moet omkeren als de waarde negatief is. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specificeert dat de staaf-, kolom- of bubbelreeks zijn kleuren moet omkeren als de waarde negatief is. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specificeert omgekeerde effen kleur voor de reeks. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Retourneert een automatische kleur van de reeks gebaseerd op de reeksenindex en grafiekstijl. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Stelt binnenste punten voor. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Stelt binnenste punten voor. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Stelt uitschieterpunten voor. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Stelt uitschieterpunten voor. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Stelt gemiddelde markeringen voor. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Stelt gemiddelde markeringen voor. |
| [getShowMeanLine()](#getShowMeanLine--) | Stelt gemiddelde lijn voor. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Stelt gemiddelde lijn voor. |
| [getQuartileMethod()](#getQuartileMethod--) | Stelt kwartielmethode voor. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Stelt kwartielmethode voor. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Stelt verbindingslijnen voor. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Stelt verbindingslijnen voor. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Stelt de lay-out van bovenliggende categorielabels voor. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Stelt de lay-out van bovenliggende categorielabels voor. |
| [hasUpDownBars()](#hasUpDownBars--) | Bepaalt of een lijn- of aandelen-grafiek op/neer balken heeft. |
| [getGapWidth()](#getGapWidth--) | Specificeert de ruimte tussen staaf- of kolomclusters, als een percentage van de breedte van de staaf of kolom. |
| [getGapDepth()](#getGapDepth--) | Retourneert of stelt de afstand in, als een percentage van de markeerbreedte, tussen de gegevensreeksen in een 3D-grafiek. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specificeert de hoek van het eerste taart- of donuts-gebied in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificeert de grootte van het gat in een donuts-grafiek (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). |
| [getOverlap()](#getOverlap--) | Specificeert hoeveel staaf- en kolommen overlappen in 2D-grafieken, als een percentage (van -100% tot 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificeert de grootte van de tweede taart of staaf van een taart-in-taart of staaf-in-taart grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [hasSeriesLines()](#hasSeriesLines--) | Bepaalt of er reekslijnen zijn voor deze reeks en verwante reeksen. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificeert hoe de bubbelformaatwaarden worden weergegeven op de bubbelgrafiek. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-in-taart of staaf-in-taart grafiek. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-in-taart of staaf-in-taart grafiek. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste splitsingsinformatie voor een taart-in-taart of staaf-in-taart grafiek met een aangepaste splitsing. |
| [isColorVaried()](#isColorVaried--) | Specificeert dat elke datamarker in de reeks een andere kleur heeft. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de bovenliggende grafiek. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retourneert:**
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

De afstand van een geopend taartpunt van het middelpunt van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. Lezen/Schrijven int.

**Retourneert:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

De afstand van een geopend taartpunt van het middelpunt van de taartgrafiek wordt uitgedrukt als een percentage van de taartdiameter. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Stelt curve smoothing voor. Waar als curve smoothing is ingeschakeld voor de lijngrafiek of spreidingsgrafiek. Geldt alleen voor lijngrafieken en spreidingsgrafieken die met lijnen verbonden zijn. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Stelt curve smoothing voor. Waar als curve smoothing is ingeschakeld voor de lijngrafiek of spreidingsgrafiek. Geldt alleen voor lijngrafieken en spreidingsgrafieken die met lijnen verbonden zijn. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Retourneert de naam van de reeks. Alleen-lezen [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Retourneert:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Retourneert de verzameling gegevenspunten van deze reeks. Alleen-lezen [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Retourneert:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

Retourneert een type van deze reeks. Lezen/Schrijven [ChartType](../../com.aspose.slides/charttype).

**Retourneert:**
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

**Retourneert:**
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

**Retourneert:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Retourneert het formaat van een reeks. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

Retourneert de volgorde van een reeks. Lezen/Schrijven int.

**Retourneert:**
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

**Retourneert:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Verzameling van trendlijnen van de reeks. Alleen-lezen [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines zijn beschikbaar (niet null) voor gegevensreeksen in niet-gestapelde 2-D area-, staaf-, kolom-, lijn-, aandelen-, xy- (spreiding-) en bubbelgrafieken. Een trendlijn is niet beschikbaar voor gegevensreeksen in enige grafiektype die gestapeld of 3-D is. Trendlijnen zijn ook niet beschikbaar voor radargrafieken, taart-, oppervlak- of donuts-grafieken.

**Retourneert:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Stelt ErrorBars van de reeks met richtings X voor. Alleen-lezen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars met X-richting zijn beschikbaar voor reeksen van type area, staaf, spreiding en bubbel. Voor alle andere grafiektype-s geeft deze eigenschap null terug (inclusief 3D-grafieken). Bij aangepaste waarden gebruik de DataPoints-verzameling om de waarde te specificeren (met ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap).

**Retourneert:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Stelt ErrorBars van de reeks met richtings Y voor. Alleen-lezen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars met Y-richting zijn beschikbaar voor reeksen van type area, staaf, lijn, spreiding en bubbel. Voor alle andere grafiektype-s geeft deze eigenschap null terug (inclusief 3D-grafieken). Bij aangepaste waarden gebruik de DataPoints-verzameling om de waarde te specificeren (met ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) eigenschap).

**Retourneert:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Stelt legende-item gerelateerd aan deze reeks voor Alleen-lezen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retourneert:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Lezen/Schrijven String.

**Retourneert:**
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

**Retourneert:**
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

**Retourneert:**
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

**Retourneert:**
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

**Retourneert:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Specificeert de vorm van een reeks van een 3D-staafgrafiek. Het wijzigen van de waarde van deze eigenschap kan automatisch het Type van de reeks wijzigen. Lezen/Schrijven [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Retourneert:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Specificeert de vorm van een reeks van een 3D-staafgrafiek. Het wijzigen van de waarde van deze eigenschap kan automatisch het Type van de reeks wijzigen. Lezen/Schrijven [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Specificeert dat de staaf-, kolom- of bubbelreeks hun kleuren moet omkeren als de waarde negatief is. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Specificeert dat de staaf-, kolom- of bubbelreeks hun kleuren moet omkeren als de waarde negatief is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Specificeert omgekeerde effen kleur voor serie. Om de kleuraanpassing toe te passen stelt u serie-indeling **FillType** in op **FillType.Solid**. Lezen/schrijven [ColorFormat](../../com.aspose.slides/colorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```


Retourneert een automatische kleur van serie op basis van serie-index en diagramstijl. Deze kleur wordt standaard gebruikt als **FillType** gelijk is aan **NotDefined**.

**Retour:**
java.awt.Color - Het java.awt.Color-object.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```


Stelt inner points voor. True if inner points are shown on the BoxAndWhisker chart. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/schrijven boolean.

**Retour:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```


Stelt inner points voor. True if inner points are shown on the BoxAndWhisker chart. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```


Stelt outlier points voor. True if outlier points are shown on the BoxAndWhisker chart. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/schrijven boolean.

**Retour:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```


Stelt outlier points voor. True if outlier points are shown on the BoxAndWhisker chart. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```


Stelt mean markers voor. True if mean markers are shown on the BoxAndWhisker chart. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/schrijven boolean.

**Retour:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```


Stelt mean markers voor. True if mean markers are shown on the BoxAndWhisker chart. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```


Stelt mean line voor. True if mean line are shown on the BoxAndWhisker chart. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/schrijven boolean.

**Retour:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```


Stelt mean line voor. True if mean line are shown on the BoxAndWhisker chart. Geldt alleen voor BoxAndWhisker-grafieken. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```


Stelt quartile method voor. Geldt alleen voor BoxAndWhisker-grafieken.

**Retour:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```


Stelt quartile method voor. Geldt alleen voor BoxAndWhisker-grafieken.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```


Stelt connector lines voor. Geldt alleen voor Waterfall-grafieken.

**Retour:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```


Stelt connector lines voor. Geldt alleen voor Waterfall-grafieken.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```


Stelt layout van parent category labels voor. Geldt alleen voor Treemap-grafieken.

**Retour:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```


Stelt layout van parent category labels voor. Geldt alleen voor Treemap-grafieken.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```


Bepaalt of een Line- of Stock-chart up/down-bars heeft. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.UpDownBars.HasUpDownBars** lezen/schrijven om de waarde te wijzigen. Gebruik de eigenschap **ParentSeriesGroup.UpDownBars** voor de opmaak van up/down-bars. Alleen-lezen boolean.

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.UpDownBars.HasUpDownBars**.

**Retour:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```


Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de breedte van de balk of kolom. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.GapWidth** lezen/schrijven om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.GapWidth**.

**Retour:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```


Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensreeksen in een 3D-diagram. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.GapDepth** lezen/schrijven om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.GapDepth**.

**Retour:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```


Specificeert de hoek van het eerste taart- of doughnut-diagramsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.FirstSliceAngle** lezen/schrijven om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.FirstSliceAngle**.

**Retour:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```


Specificeert de grootte van het gat in een doughnut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.DoughnutHoleSize** lezen/schrijven om de waarde te wijzigen. Alleen-lezen byte.

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.DoughnutHoleSize**.

**Retour:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```


Specificeert hoeveel balken en kolommen overlappen in 2-D-diagrammen, als een percentage (van -100 % tot 100 %). Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep. Het is een projectie van de overeenkomstige eigenschap in de bovenliggende series-groep, en daarom is deze eigenschap alleen-lezen. Om de waarde te wijzigen, gebruik de eigenschap **ParentSeriesGroup.Overlap** lezen/schrijven. Alleen-lezen byte.

--------------------

Overlap specificeert de mate van overlapping of spatiëring tussen balken en kolommen als een percentage van hun breedte:
- -100 %: maximale spatiëring (balken zijn volledig gescheiden).
- 0 %: balken staan naast elkaar zonder overlapping of spatiëring.
- 100 %: maximale overlapping (balken overlappen volledig). Dit is een projectie van de eigenschap **ParentSeriesGroup.Overlap**.

**Retour:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```


Specificeert de grootte van de tweede taart of balk van een pie-of-pie-diagram of een bar-of-pie-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.SecondPieSize** lezen/schrijven om de waarde te wijzigen. Alleen-lezen int.

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.SecondPieSize**.

**Retour:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```


Bepaalt of er series-lines zijn voor deze serie en verwante series. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.HasSeriesLines** lezen/schrijven om de waarde te wijzigen. Gebruik de eigenschap **ParentSeriesGroup.SeriesLinesFormat** voor de opmaak van series-lines. Alleen-lezen boolean.

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.HasSeriesLines**.

**Retour:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```


Specificeert hoe de bubbelaantalgroottes worden weergegeven op het bubble-diagram. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.BubbleSizeRepresentation** lezen/schrijven om de waarde te wijzigen.

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.BubbleSizeRepresentation**.

**Retour:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```


Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten in de tweede taart of balk van een pie-of-pie- of bar-of-pie-diagram komen. Wordt samen met de eigenschap **PieSplitBy** gebruikt. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.PieSplitPosition** lezen/schrijven om de waarde te wijzigen. Alleen-lezen double.

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.PieSplitPosition**.

**Retour:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```


Specificeert hoe bepaald wordt welke gegevenspunten in de tweede taart of balk van een pie-of-pie- of bar-of-pie-diagram komen. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap. En daarom is deze eigenschap alleen-lezen. Gebruik de eigenschap **ParentSeriesGroup** voor toegang tot de bovenliggende series-groep. Gebruik de eigenschap **ParentSeriesGroup.PieSplitBy** lezen/schrijven om de waarde te wijzigen. Alleen-lezen [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Dit is de projectie van de eigenschap **ParentSeriesGroup.PieSplitBy**. 2) Als de eigenschapswaarde **PieSplitType.Custom** is, kunt u aangepaste splitsinformatie definiëren met de eigenschap **ParentSeriesGroup.PieSplitCustomPoints**.

**Retour:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


De aangepaste splitsinformatie voor een pie-of-pie- of bar-of-pie-diagram met een aangepaste splitsing. Bevat gegevenspunten die in de tweede taart of balk getekend moeten worden in een pie-of-pie- of bar-of-pie-diagram. Dit is de eigenschap niet alleen van deze serie maar van alle series van de bovenliggende series-groep – dit is een projectie van de overeenkomstige groepseigenschap Alleen-lezen [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Dit is de projectie van de eigenschap **ParentSeriesGroup.PieSplitCustomPoints**.

**Retour:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean.

Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean. 

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**Returns:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```


Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**Returns:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)