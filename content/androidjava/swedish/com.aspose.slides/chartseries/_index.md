---
title: ChartSeries
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en diagramserie.
type: docs
url: /sv/com.aspose.slides/chartseries/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Representerar en diagramserie.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returnerar föräldradiagrammet. |
| [getExplosion()](#getExplosion--) | Avståndet för en öppen pajskiva från diagrammets centrum uttrycks som en procentandel av pajens diameter. |
| [setExplosion(int value)](#setExplosion-int-) | Avståndet för en öppen pajskiva från diagrammets centrum uttrycks som en procentandel av pajens diameter. |
| [getSmooth()](#getSmooth--) | Representerar kurvutjämning. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Representerar kurvutjämning. |
| [getName()](#getName--) | Returnerar seriesnamn. |
| [getDataPoints()](#getDataPoints--) | Returnerar samlingen av datapunkter för denna serie. |
| [getType()](#getType--) | Returnerar en typ för denna serie. |
| [setType(int value)](#setType-int-) | Returnerar en typ för denna serie. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Anger om denna serie ritas på sekundäraxeln. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Anger om denna serie ritas på sekundäraxeln. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Returnerar formatet för en serie. |
| [getOrder()](#getOrder--) | Returnerar ordningen för en serie. |
| [setOrder(int value)](#setOrder-int-) | Returnerar ordningen för en serie. |
| [getLabels()](#getLabels--) | Returnerar etiketterna för en serie. |
| [getTrendLines()](#getTrendLines--) | Samling av serietrendlinjer. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Representerar felstaplar för serien med riktning X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Representerar felstaplar för serien med riktning Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representerar förklaringspost relaterad till denna serie Endast läsning [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Specificerar formen på en serie i ett 3D stapeldiagram. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Specificerar formen på en serie i ett 3D stapeldiagram. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Anger att stapel-, kolumn- eller bubbelsekvensen ska invertera färgerna om värdet är negativt. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Anger att stapel-, kolumn- eller bubbelsekvensen ska invertera färgerna om värdet är negativt. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Specificerar inverterad solid färg för serien. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Returnerar en automatisk färg för serien baserat på seriens index och diagramstil. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Representerar innerpunkter. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Representerar innerpunkter. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Representerar avvikande punkter. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Representerar avvikande punkter. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Representerar medelvärdesmarkörer. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Representerar medelvärdesmarkörer. |
| [getShowMeanLine()](#getShowMeanLine--) | Representerar medellinje. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Representerar medellinje. |
| [getQuartileMethod()](#getQuartileMethod--) | Representerar kvartilsmetod. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Representerar kvartilsmetod. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Representerar anslutningslinjer. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Representerar anslutningslinjer. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Representerar layout av föräldrakategori-etiketter. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Representerar layout av föräldrakategori-etiketter. |
| [hasUpDownBars()](#hasUpDownBars--) | Bestämmer om linje- eller aktiediagram har upp/ner-staplar. |
| [getGapWidth()](#getGapWidth--) | Specificerar avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. |
| [getGapDepth()](#getGapDepth--) | Returnerar eller ställer in avståndet, som en procentandel av markörbredden, mellan dataserier i ett 3D-diagram. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Specificerar vinkeln för den första paj- eller munkskivan i grader (medurs från toppen, 0 till 360 grader). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificerar storleken på hålet i ett munkdiagram (kan vara mellan 10 och 90 % av grafens yta). |
| [getOverlap()](#getOverlap--) | Specificerar hur mycket staplar och kolumner överlappar i 2-D-diagram, som en procentandel (från -100 % till 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificerar storleken på den andra pajen eller stapeln i ett paj-i-paj-diagram eller stapel-i-paj-diagram, som en procentandel av den första pajens storlek (kan vara mellan 5 och 200 %). |
| [hasSeriesLines()](#hasSeriesLines--) | Bestämmer om det finns serielinjer för denna serie och närstående serier. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificerar hur bubbelstorleksvärdena representeras i bubbeldiagrammet. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificerar ett värde som ska användas för att bestämma vilka datapunkter som är i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificerar hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Den anpassade delningsinformationen för ett paj-i-paj- eller stapel-i-paj-diagram med en anpassad delning. |
| [isColorVaried()](#isColorVaried--) | Specificerar att varje datamarkör i serien har en annan färg. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificerar skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 % av standardstorleken). |
| [getSlide()](#getSlide--) | Returnerar föräldradesliden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar föräldrapresentationen för ett FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Endast läsning IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar föräldradiagrammet. Endast läsning [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Avståndet för en öppen pajskiva från diagrammets centrum uttrycks som en procentandel av pajens diameter. Läs/skriv int.

**Returnerar:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Avståndet för en öppen pajskiva från diagrammets centrum uttrycks som en procentandel av pajens diameter. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Representerar kurvutjämning. Sant om kurvutjämning är aktiverad för linjediagrammet eller spridningsdiagrammet. Gäller endast för linje- och spridningsdiagram som är anslutna med linjer. Läs/skriv boolean.

**Returnerar:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Representerar kurvutjämning. Sant om kurvutjämning är aktiverad för linjediagrammet eller spridningsdiagrammet. Gäller endast för linje- och spridningsdiagram som är anslutna med linjer. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Returnerar seriesnamn. Endast läsning [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returnerar:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Returnerar samlingen av datapunkter för denna serie. Endast läsning [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Returnerar:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Returnerar en typ för denna serie. Läs/skriv [ChartType](../../com.aspose.slides/charttype).

**Returnerar:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Returnerar en typ för denna serie. Läs/skriv [ChartType](../../com.aspose.slides/charttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Anger om denna serie ritas på sekundäraxeln. Läs/skriv boolean.

**Returnerar:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Anger om denna serie ritas på sekundäraxeln. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Endast läsning [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Returnerar:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Returnerar formatet för en serie. Endast läsning [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Returnerar ordningen för en serie. Läs/skriv int.

**Returnerar:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Returnerar ordningen för en serie. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Returnerar etiketterna för en serie. Endast läsning [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Returnerar:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Samling av serietrendlinjer. Endast läsning [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

Trendlinjer är tillgängliga (inte null) för dataserier i stapelfria 2-D-area-, stapel-, kolumn-, linje-, aktie-, xy-(spridnings)- och bubbeldiagram. En trendlinje är inte tillgänglig för dataserier i någon diagramtyp som är staplad eller 3-D. Trendlinjer är också inte tillgängliga för radar-, paj-, yta- eller munkdiagram.

**Returnerar:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Representerar felstaplar för serien med riktning X. Endast läsning [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Felstaplar med X-riktning är tillgängliga för serier av typ area, stapel, spridning och bubbla. För alla andra diagramtyper returnerar denna egenskap null (inklusive 3D-diagram). Vid anpassade värden används DataPoints-samlingen för att specificera värdet (med ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) egenskap).

**Returnerar:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Representerar felstaplar för serien med riktning Y. Endast läsning [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Felstaplar med Y-riktning är tillgängliga för serier av typ area, stapel, linje, spridning och bubbla. För alla andra diagramtyper returnerar denna egenskap null (inklusive 3D-diagram). Vid anpassade värden används DataPoints-samlingen för att specificera värdet (med ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) egenskap).

**Returnerar:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Representerar förklaringspost relaterad till denna serie Endast läsning [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Endast läsning [IMarker](../../com.aspose.slides/imarker).

**Returnerar:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Specificerar formen på en serie i ett 3D stapeldiagram. Ändring av detta värde kan leda till att serietypen automatiskt ändras. Läs/skriv [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returnerar:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Specificerar formen på en serie i ett 3D stapeldiagram. Ändring av detta värde kan leda till att serietypen automatiskt ändras. Läs/skriv [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Anger att stapel-, kolumn- eller bubbelsekvensen ska invertera färgerna om värdet är negativt. Läs/skriv boolean.

**Returnerar:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Anger att stapel-, kolumn- eller bubbelsekvensen ska invertera färgerna om värdet är negativt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Specificerar inverterad solid färg för serien. För att tillämpa färginställningen sätt FillFormat-formatet till FillType.Solid. Läs/skriv [ColorFormat](../../com.aspose.slides/colorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Returnerar en automatisk färg för serien baserat på seriens index och diagramstil. Denna färg används som standard om FillType är NotDefined.

**Returnerar:**
java.lang.Integer - java.lang.Integer-objektet.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Representerar innerpunkter. Sant om innerpunkter visas i BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Representerar innerpunkter. Sant om innerpunkter visas i BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Representerar avvikande punkter. Sant om avvikande punkter visas i BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Representerar avvikande punkter. Sant om avvikande punkter visas i BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Representerar medelvärdesmarkörer. Sant om medelvärdesmarkörer visas i BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Representerar medelvärdesmarkörer. Sant om medelvärdesmarkörer visas i BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Representerar medellinje. Sant om medellinje visas i BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Representerar medellinje. Sant om medellinje visas i BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Representerar kvartilsmetod. Gäller endast BoxAndWhisker-diagram.

**Returnerar:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Representerar kvartilsmetod. Gäller endast BoxAndWhisker-diagram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Representerar anslutningslinjer. Gäller endast Waterfall-diagram.

**Returnerar:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Representerar anslutningslinjer. Gäller endast Waterfall-diagram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Representerar layout av föräldrakategori-etiketter. Gäller endast Treemap-diagram.

**Returnerar:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Representerar layout av föräldrakategori-etiketter. Gäller endast Treemap-diagram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Bestämmer om linje- eller aktiediagram har upp/ner-staplar. Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.UpDownBars.HasUpDownBars Läs/skriv-egenskap för att ändra värdet. Använd ParentSeriesGroup.UpDownBars-egenskap för format på upp/ner-staplar. Endast läsning boolean.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Returnerar:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Specificerar avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.GapWidth Läs/skriv-egenskap för att ändra värdet. Endast läsning int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.GapWidth.

**Returnerar:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Returnerar eller ställer in avståndet, som en procentandel av markörbredden, mellan dataserier i ett 3D-diagram. Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.GapDepth Läs/skriv-egenskap för att ändra värdet. Endasta läsning int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.GapDepth.

**Returnerar:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Specificerar vinkeln för den första paj- eller munkskivan i grader (medurs från toppen, 0 till 360 grader). Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.FirstSliceAngle Läs/skriv-egenskap för att ändra värdet. Endast läsning int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.FirstSliceAngle.

**Returnerar:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Specificerar storleken på hålet i ett munkdiagram (kan vara mellan 10 och 90 % av grafens yta). Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.DoughnutHoleSize Läs/skriv-egenskap för att ändra värdet. Endast läsning byte.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.DoughnutHoleSize.

**Returnerar:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Specificerar hur mycket staplar och kolumner överlappar i 2-D-diagram, som en procentandel (från -100 % till 100 %). Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen. Det är en projektion av motsvarande egenskap i föräldraserieggruppen, så egenskapen är Endast läsning. För att ändra värdet, använd ParentSeriesGroup.Overlap Läs/skriv-egenskap. Endast läsning byte.

--------------------

Overlap specificerar graden av överlappning eller avstånd mellan staplar och kolumner som en procentandel av deras bredd:
- -100 %: maximal avstånd (staplar helt separerade).
- 0 %: staplar placerade sida vid sida utan överlappning eller avstånd.
- 100 %: maximal överlappning (staplar helt överlappande).

Detta är en projektion av egenskapen ParentSeriesGroup.Overlap.

**Returnerar:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Specificerar storleken på den andra pajen eller stapeln i ett paj-i-paj-diagram eller stapel-i-paj-diagram, som en procentandel av den första pajens storlek (kan vara mellan 5 och 200 %). Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.SecondPieSize Läs/skriv-egenskap för att ändra värdet. Endast läsning int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.SecondPieSize.

**Returnerar:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Bestämmer om det finns serielinjer för denna serie och närstående serier. Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.HasSeriesLines Läs/skriv-egenskap för att ändra värdet. Använd ParentSeriesGroup.SeriesLinesFormat-egenskap för format av serielinjer. Endast läsning boolean.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.HasSeriesLines.

**Returnerar:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Specificerar hur bubbelstorleksvärdena representeras i bubbeldiagrammet. Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.BubbleSizeRepresentation Läs/skriv-egenskap för att ändra värdet.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.BubbleSizeRepresentation.

**Returnerar:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Specificerar ett värde som ska användas för att bestämma vilka datapunkter som är i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Används tillsammans med PieSplitBy-egenskapen. Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.PieSplitPosition Läs/skriv-egenskap för att ändra värdet. Endast läsning double.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.PieSplitPosition.

**Returnerar:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Specificerar hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.PieSplitBy Läs/skriv-egenskap för att ändra värdet. Endast läsning [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Detta är projektionen av egenskapen ParentSeriesGroup.PieSplitBy. 2) Om egenskapsvärdet är PieSplitType.Custom kan du definiera anpassad delningsinformation med ParentSeriesGroup.PieSplitCustomPoints-egenskap.

**Returnerar:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Den anpassade delningsinformationen för ett paj-i-paj- eller stapel-i-paj-diagram med en anpassad delning. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap Endast läsning [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.PieSplitCustomPoints.

**Returnerar:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Specificerar att varje datamarkör i serien har en annan färg. Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.IsColorVaried Läs/skriv-egenskap för att ändra värdet. Endast läsning boolean.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.IsColorVaried.

**Returnerar:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specificerar skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 % av standardstorleken). Detta är en egenskap som inte bara tillhör denna serie utan även alla serier i föräldraserieggruppen – den är en projektion av motsvarande grupp-egenskap. Därför är egenskapen Endast läsning. Använd ParentSeriesGroup-egenskapen för åtkomst till föräldraserieggruppen. Använd ParentSeriesGroup.BubbleSizeScale Läs/skriv-egenskap för att ändra värdet.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.BubbleSizeScale.

**Returnerar:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar föräldradesliden för ett FillFormat. Endast läsning [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar föräldrapresentationen för ett FillFormat. Endänd läsning [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)