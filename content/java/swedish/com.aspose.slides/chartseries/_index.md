---
title: ChartSeries
second_title: Aspose.Slides för Java API-referens
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
| [getExplosion()](#getExplosion--) | Avståndet för en öppen tårtbit från centrum av tårtdiagrammet uttrycks som en procentandel av tårtdiametern. |
| [setExplosion(int value)](#setExplosion-int-) | Avståndet för en öppen tårtbit från centrum av tårtdiagrammet uttrycks som en procentandel av tårtdiametern. |
| [getSmooth()](#getSmooth--) | Representerar kurvutjämning. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Representerar kurvutjämning. |
| [getName()](#getName--) | Returnerar seriens namn. |
| [getDataPoints()](#getDataPoints--) | Returnerar en samling av datapunkter för denna serie. |
| [getType()](#getType--) | Returnerar en typ för denna serie. |
| [setType(int value)](#setType-int-) | Returnerar en typ för denna serie. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indikerar om denna serie ritas på sekundär axel. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indikerar om denna serie ritas på sekundär axel. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Returnerar formatet för en serie. |
| [getOrder()](#getOrder--) | Returnerar ordningen för en serie. |
| [setOrder(int value)](#setOrder-int-) | Returnerar ordningen för en serie. |
| [getLabels()](#getLabels--) | Returnerar etiketter för en serie. |
| [getTrendLines()](#getTrendLines--) | Samling av seriens trendlina. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Representerar felstaplar för serien med riktning X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Representerar felstaplar för serien med riktning Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representerar legendpost relaterad till denna serie. Skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Anger formen för en serie i ett 3-D stapeldiagram. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Anger formen för en serie i ett 3-D stapeldiagram. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Anger att stapel-, kolumn- eller bubbelseien ska invertera färgerna om värdet är negativt. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Anger att stapel-, kolumn- eller bubbelseien ska invertera färgerna om värdet är negativt. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Anger inverterad solid färg för serien. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Returnerar en automatisk färg för serien baserat på serieindex och diagramstil. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Representerar inre punkter. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Representerar inre punkter. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Representerar avvikande punkter. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Representerar avvikande punkter. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Representerar medelvärdesmarkörer. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Representerar medelvärdesmarkörer. |
| [getShowMeanLine()](#getShowMeanLine--) | Representerar medellinje. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Representerar medellinje. |
| [getQuartileMethod()](#getQuartileMethod--) | Representerar kvartilmethode. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Representerar kvartilmethode. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Representerar anslutningslinjer. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Representerar anslutningslinjer. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Representerar layout för föräldrakategorietiketter. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Representerar layout för föräldrakategorietiketter. |
| [hasUpDownBars()](#hasUpDownBars--) | Avgör om linje- eller stapeldiagram har upp/ner-staplar. |
| [getGapWidth()](#getGapWidth--) | Anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapelns eller kolumnens bredd. |
| [getGapDepth()](#getGapDepth--) | Returnerar eller anger avståndet, som en procentandel av markörens bredd, mellan dataserier i ett 3D-diagram. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Anger vinkeln för den första biten i ett tårta- eller munkdiagram, i grader (medurs från upp, 0 till 360 grader). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Anger storleken på hålet i ett munkdiagram (kan vara mellan 10 och 90 procent av plottområdet). |
| [getOverlap()](#getOverlap--) | Anger hur mycket staplar och kolumner överlappar i 2-D-diagram, i procent (från -100 % till 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Anger storleken på den andra tårtan eller stapeln i ett pie-of-pie-diagram eller bar-of-pie-diagram, som en procentandel av den första tårtans storlek (kan vara mellan 5 och 200 procent). |
| [hasSeriesLines()](#hasSeriesLines--) | Avgör om det finns serielinjer för denna serie och närstående serier. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Anger hur bubbelstorleksvärden representeras i bubbeldiagrammet. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Anger hur man bestämmer vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Den anpassade delningsinformationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad delning. |
| [isColorVaried()](#isColorVaried--) | Anger att varje datamarkör i serien har en annan färg. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). |
| [getSlide()](#getSlide--) | Returnerar föräldra-bilden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar föräldrapresentationen för ett FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar föräldradiagrammet. Skrivskyddad [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Avståndet för en öppen tårtbit från centrum av tårtdiagrammet uttrycks som en procentandel av tårtdiametern. Läs/skriv int.

**Returnerar:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Avståndet för en öppen tårtbit från centrum av tårtdiagrammet uttrycks som en procentandel av tårtdiametern. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Representerar kurvutjämning. Sant om kurvutjämning är påslagen för linjediagrammet eller spridningsdiagrammet. Gäller endast för linje- och spridningsdiagram som är kopplade med linjer. Läs/skriv boolean.

**Returnerar:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Representerar kurvutjämning. Sant om kurvutjämning är påslagen för linjediagrammet eller spridningsdiagrammet. Gäller endast för linje- och spridningsdiagram som är kopplade med linjer. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Returnerar seriens namn. Skrivskyddad [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returnerar:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Returnerar en samling av datapunkter för denna serie. Skrivskyddad [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

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

Indikerar om denna serie ritas på sekundär axel. Läs/skriv boolean.

**Returnerar:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Indikerar om denna serie ritas på sekundär axel. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Skrivskyddad [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Returnerar:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Returnerar formatet för en serie. Skrivskyddad [IFormat](../../com.aspose.slides/iformat).

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

Returnerar etiketter för en serie. Skrivskyddad [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Returnerar:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Samling av seriens trendlina. Skrivskyddad [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

---

Trendlina är tillgängliga (inte null) för dataserier i icke-staplade 2-D-områdes-, stapel-, kolumn-, linje-, aktie-, xy- (spridnings-) och bubbeldiagram. En trendlinje är inte tillgänglig för dataserier i någon diagramtyp som är staplad eller 3-D. Trendlina är också inte tillgängliga för radardiagram, tårt-, ytdiagram eller munkdiagram.

**Returnerar:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Representerar felstaplar för serien med riktning X. Skrivskyddad [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

---

Felstaplar med X-riktning är tillgängliga för serier av typen område, stapel, spridning och bubbla. För alla andra diagramtyper returnerar denna egenskap null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samlingen för att ange värdet (med ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) egenskapen).

**Returnerar:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Representerar felstaplar för serien med riktning Y. Skrivskyddad [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

---

Felstaplar med Y-riktning är tillgängliga för serier av typen område, stapel, linje, spridning och bubbla. För alla andra diagramtyper returnerar denna egenskap null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samlingen för att ange värdet (med ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) egenskapen).

**Returnerar:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Representerar legendpost relaterad till denna serie. Skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Marker. Skrivskyddad [IMarker](../../com.aspose.slides/imarker).

**Returnerar:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Anger formen för en serie i ett 3-D stapeldiagram. Ändring av detta värde kan automatiskt ändra typ av serie. Läs/skriv [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returnerar:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Anger formen för en serie i ett 3-D stapeldiagram. Ändring av detta värde kan automatiskt ändra typ av serie. Läs/skriv [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Anger att stapel-, kolumn- eller bubbelseien ska invertera färgerna om värdet är negativt. Läs/skriv boolean.

**Returnerar:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Anger att stapel-, kolumn- eller bubbelseien ska invertera färgerna om värdet är negativt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Anger inverterad fast färg för serien. För att tillämpa färginställningen, sätt series format FillType till FillType.Solid. Läs/skriv [ColorFormat](../../com.aspose.slides/colorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

Returnerar en automatisk färg för serien baserat på serieindex och diagramstil. Denna färg används som standard om FillType är lika med NotDefined.

**Returnerar:**
java.awt.Color - java.awt.Color-objektet.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Representerar inre punkter. Sant om inre punkter visas på BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Representerar inre punkter. Sant om inre punkter visas på BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Representerar avvikande punkter. Sant om avvikande punkter visas på BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Representerar avvikande punkter. Sant om avvikande punkter visas på BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Representerar medelvärdesmarkörer. Sant om medelvärdesmarkörer visas på BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Representerar medelvärdesmarkörer. Sant om medelvärdesmarkörer visas på BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Representerar medellinje. Sant om medellinje visas på BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Representerar medellinje. Sant om medellinje visas på BoxAndWhisker-diagrammet. Gäller endast BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Representerar kvartilmethode. Gäller endast BoxAndWhisker-diagram.

**Returnerar:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Representerar kvartilmethode. Gäller endast BoxAndWhisker-diagram.

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

Representerar layout för föräldrakategori-etiketter. Gäller endast Treemap-diagram.

**Returnerar:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Representerar layout för föräldrakategori-etiketter. Gäller endast Treemap-diagram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Bestämmer om Line- eller Stock-diagram har upp/ner-staplar. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.UpDownBars.HasUpDownBars läs/skriv-egenskap för att ändra värdet. Använd ParentSeriesGroup.UpDownBars-egenskapen för att formatera upp/ner-staplar. Skrivskyddad boolean.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Returnerar:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.GapWidth läs/skriv-egenskap för att ändra värdet. Skrivskyddad int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.GapWidth.

**Returnerar:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Returnerar eller anger avståndet, som en procentandel av markörbredden, mellan dataserier i ett 3D-diagram. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.GapDepth läs/skriv-egenskap för att ändra värdet. Skrivskyddad int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.GapDepth.

**Returnerar:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Anger vinkeln för den första sektorn i ett paj- eller munkdiagram, i grader (medurs från upp, från 0 till 360 grader). Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.FirstSliceAngle läs/skriv-egenskap för att ändra värdet. Skrivskyddad int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.FirstSliceAngle.

**Returnerar:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Anger storleken på hålet i ett munkdiagram (kan vara mellan 10 och 90 procent av storleken på plotområdet). Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.DoughnutHoleSize läs/skriv-egenskap för att ändra värdet. Skrivskyddad byte.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.DoughnutHoleSize.

**Returnerar:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Anger hur mycket staplar och kolumner överlappar på 2-D-diagram, som en procentandel (från -100 % till 100 %). Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen. Det är en projektion av den lämpliga egenskapen i den överordnade serieggruppen, och därför är egenskapen skrivskyddad. För att ändra värdet, använd ParentSeriesGroup.Overlap läs/skriv-egenskap. Skrivskyddad byte.

Overlap specificerar graden av överlappning eller avstånd mellan staplar och kolumner som en procentandel av deras bredd: - -100 %: Maximal avstånd (staplarna är helt separerade). - 0 %: Staplarna placeras sida vid sida utan överlappning eller avstånd. - 100 %: Maximal överlappning (staplarna överlappar helt varandra). Detta är en projektion av egenskapen ParentSeriesGroup.Overlap.

--------------------

**Returnerar:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Anger storleken på den andra pajen eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procentandel av storleken på den första pajen (kan vara mellan 5 och 200 procent). Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.SecondPieSize läs/skriv-egenskap för att ändra värdet. Skrivskyddad int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.SecondPieSize.

**Returnerar:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Bestämmer om det finns serielinjer för denna serie och närbesläktade serier. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.HasSeriesLines läs/skriv-egenskap för att ändra värdet. Använd ParentSeriesGroup.SeriesLinesFormat-egenskap för att formatera serielinjer. Skrivskyddad boolean.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.HasSeriesLines.

**Returnerar:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Anger hur bubbelstorleksvärdena representeras i bubbeldiagrammet. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.BubbleSizeRepresentation läs/skriv-egenskap för att ändra värdet.

--------------------

**Returnerar:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som ingår i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med egenskapen PieSplitBy. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.PieSplitPosition läs/skriv-egenskap för att ändra värdet. Skrivskyddad double.

--------------------

**Returnerar:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Anger hur man bestämmer vilka datapunkter som ingår i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Därför är egenskapen skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.PieSplitBy läs/skriv-egenskap för att ändra värdet. Skrivskyddad [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------
1) Detta är projektionen av egenskapen ParentSeriesGroup.PieSplitBy. 2) Om egenskapsvärdet är PieSplitType.Custom kan du definiera anpassad delningsinformation med egenskapen ParentSeriesGroup.PieSplitCustomPoints.

**Returnerar:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Den anpassade delningsinformationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad delning. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen – detta är en projektion av lämplig grupp-egenskap. Skrivskyddad [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------
Detta är projektionen av egenskapen ParentSeriesGroup.PieSplitCustomPoints.

**Returnerar:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Anger att varje datamarkör i serien har en annan färg. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade seriesgruppen – detta är projektion av lämplig gruppproperty. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriesgruppen. Använd ParentSeriesGroup.IsColorVaried läs/skriv-egenskap för att ändra värdet. Skrivskyddad boolean.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.IsColorVaried.

**Returnerar:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade seriesgruppen – detta är projektion av lämplig gruppproperty. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriesgruppen. Använd ParentSeriesGroup.BubbleSizeScale läs/skriv-egenskap för att ändra värdet.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.BubbleSizeScale.

**Returnerar:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för en FillFormat. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för en FillFormat. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)