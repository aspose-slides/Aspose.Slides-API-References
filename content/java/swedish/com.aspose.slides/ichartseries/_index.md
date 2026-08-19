---
title: IChartSeries
second_title: Aspose.Slides för Java API-referens
description: Representerar en diagramserie.
type: docs
url: /sv/com.aspose.slides/ichartseries/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Representerar en diagramserie.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExplosion()](#getExplosion--) | Avståndet för en öppen pajskiva från mitten av pajdiagrammet uttrycks som en procentandel av pajens diameter. |
| [setExplosion(int value)](#setExplosion-int-) | Avståndet för en öppen pajskiva från mitten av pajdiagrammet uttrycks som en procentandel av pajens diameter. |
| [getSmooth()](#getSmooth--) | Representerar kurvutjämning. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Representerar kurvutjämning. |
| [getMarker()](#getMarker--) | Returnerar seriesmarkör. |
| [getBar3DShape()](#getBar3DShape--) | Anger formen för en serie i ett 3D-stapeldiagram. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Anger formen för en serie i ett 3D-stapeldiagram. |
| [getName()](#getName--) | Returnerar serienamn. |
| [getDataPoints()](#getDataPoints--) | Returnerar samling av datapunkter för denna serie. |
| [getType()](#getType--) | Returnerar en typ av denna serie. |
| [setType(int value)](#setType-int-) | Returnerar en typ av denna serie. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Returnerar föräldra-seriegrupp. |
| [getFormat()](#getFormat--) | Returnerar formatet för en serie. |
| [getOrder()](#getOrder--) | Returnerar ordningen för en serie. |
| [setOrder(int value)](#setOrder-int-) | Returnerar ordningen för en serie. |
| [getLabels()](#getLabels--) | Returnerar etiketterna för en serie. |
| [getTrendLines()](#getTrendLines--) | Samling av serietrendlinjer Skrivskyddad [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Representerar felstaplar för serie med riktning X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Representerar felstaplar för serie med riktning Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Anger om denna serie är plottrad på sekundär värdeaxel. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Anger om denna serie är plottrad på sekundär värdeaxel. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Returnerar eller anger talformatet för serievärden. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Returnerar eller anger talformatet för serievärden. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Returnerar eller anger talformatet för serie-x-värden. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Returnerar eller anger talformatet för serie-x-värden. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Returnerar eller anger talformatet för serie-y-värden. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Returnerar eller anger talformatet för serie-y-värden. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Returnerar eller anger talformatet för seriesbubblestorlekar. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Returnerar eller anger talformatet för seriesbubblestorlekar. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Anger att stapel-, kolumn- eller bubbelseerien ska invertera sina färger om värdet är negativt. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Anger att stapel-, kolumn- eller bubbelseerien ska invertera sina färger om värdet är negativt. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Anger inverterad solid färg för serien. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representerar legendpost relaterad till denna serie Skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Returnerar en automatisk färg för serien baserat på serieindex och diagramstil. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Representerar interna punkter. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Representerar interna punkter. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Representerar avvikande punkter. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Representerar avvikande punkter. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Representerar medelvärdesmarkörer. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Representerar medelvärdesmarkörer. |
| [getShowMeanLine()](#getShowMeanLine--) | Representerar medelvärdesmarkörer. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Representerar medelvärdesmarkörer. |
| [getQuartileMethod()](#getQuartileMethod--) | Representerar kvartilsmetod. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Representerar kvartilsmetod. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Representerar anslutningslinjer. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Representerar anslutningslinjer. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Representerar layouten för föräldrakategori-etiketter. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Representerar layouten för föräldrakategori-etiketter. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Anger skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). |
| [hasUpDownBars()](#hasUpDownBars--) | Avgör om linje- eller aktiediagram har upp/ner-staplar. |
| [getGapWidth()](#getGapWidth--) | Anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. |
| [getGapDepth()](#getGapDepth--) | Returnerar eller anger avståndet, som en procentandel av markörbredden, mellan dataserier i ett 3D-diagram. |
| [isColorVaried()](#isColorVaried--) | Anger att varje datamarkör i serien har en annan färg. |
| [hasSeriesLines()](#hasSeriesLines--) | Avgör om det finns serielinjer för denna serie och närliggande serier. |
| [getOverlap()](#getOverlap--) | Anger hur mycket staplar och kolumner överlappar i 2-D-diagram, som en procentandel (från -100 % till 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Anger storleken på den andra pajen eller stapeln i ett paj-i-paj-diagram eller stapel-i-paj-diagram, som en procentandel av den första pajens storlek (kan vara mellan 5 och 200 procent). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Anger ett värde som ska användas för att bestämma vilka datapunkter som ingår i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Anger hur man bestämmer vilka datapunkter som ingår i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Anger storleken på hålet i ett ringdiagram (kan vara mellan 10 och 90 procent av plottytans storlek). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Anger vinkeln för den första paj- eller ringdiagramskivan, i grader (medurs från toppen, från 0 till 360 grader). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Den anpassade split-informationen för ett paj-i-paj- eller stapel-i-paj-diagram med en anpassad split. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Anger hur bubbelförstorleksvärdena representeras i bubbeldiagrammet. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Avståndet för en öppen pajskiva från mitten av pajdiagrammet uttrycks som en procentandel av pajens diameter. Läs/skriv int.

**Returnerar:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Avståndet för en öppen pajskiva från mitten av pajdiagrammet uttrycks som en procentandel av pajens diameter. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Representerar kurvutjämning. Sant om kurvutjämning är påslagen för linjediagrammet eller spriddiagrammet. Gäller endast linje- och spriddiagram som är kopplade med linjer. Läs/skriv boolean.

**Returnerar:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Representerar kurvutjämning. Sant om kurvutjämning är påslagen för linjediagrammet eller spriddiagrammet. Gäller endast linje- och spriddiagram som är kopplade med linjer. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Returnerar seriesmarkör. Skrivskyddad [IMarker](../../com.aspose.slides/imarker).

**Returnerar:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Anger formen för en serie i ett 3D-stapeldiagram. Ändring av detta egenskapsvärde kan automatiskt ändra serietyp. Läs/skriv [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returnerar:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Anger formen för en serie i ett 3D-stapeldiagram. Ändring av detta egenskapsvärde kan automatiskt ändra serietyp. Läs/skriv [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Returnerar serienamn. Skrivskyddad [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returnerar:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Returnerar samling av datapunkter för denna serie. Skrivskyddad [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Returnerar:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Returnerar en typ av denna serie. Läs/skriv [ChartType](../../com.aspose.slides/charttype).

**Returnerar:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Returnerar en typ av denna serie. Läs/skriv [ChartType](../../com.aspose.slides/charttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Returnerar föräldra-seriegrupp. Skrivskyddad [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Returnerar:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Returnerar formatet för en serie. Skrivskyddad [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Returnerar ordningen för en serie. Läs/skriv int.

**Returnerar:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Returnerar ordningen för en serie. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Returnerar etiketterna för en serie. Skrivskyddad [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Returnerar:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Samling av serietrendlinjer Skrivskyddad [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Returnerar:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Representerar felstaplar för serie med riktning X. Skrivskyddad [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Felstaplar med X-riktning är tillgängliga för serier av typen area, bar, scatter och bubble. För alla andra diagramtyper returnerar egenskapen null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samlingen för att ange värdet (med ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) egenskapen).

**Returnerar:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Representerar felstaplar för serie med riktning Y. Skrivskyddad [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Felstaplar med Y-riktning är tillgängliga för serier av typen area, bar, line, scatter och bubble. För alla andra diagramtyper returnerar egenskapen null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samlingen för att ange värdet (med ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) egenskapen).

**Returnerar:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Anger om denna serie är plottrad på sekundär värdeaxel. Läs/skriv boolean.

**Returnerar:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Anger om denna serie är plottrad på sekundär värdeaxel. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Returnerar eller anger talformatet för serievärden. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Returnerar eller anger talformatet för serievärden. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Returnerar eller anger talformatet för serie-x-värden. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Returnerar eller anger talformatet för serie-x-värden. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Returnerar eller anger talformatet för serie-y-värden. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Returnerar eller anger talformatet för serie-y-värden. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Returnerar eller anger talformatet för seriesbubblestorlekar. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Returnerar eller anger talformatet för seriesbubblestorlekar. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Anger att stapel-, kolumn- eller bubbelseerien ska invertera sina färger om värdet är negativt. Läs/skriv boolean.

**Returnerar:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Anger att stapel-, kolumn- eller bubbelseerien ska invertera sina färger om värdet är negativt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Anger inverterad solid färg för serien. För att tillämpa färginställning, sätt series format FillType till FillType.Solid. Läs/skriv [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Representerar legendpost relaterad till denna serie Skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Returns en automatisk färg för serien baserat på serieindex och diagramstil. Denna färg används som standard om FillType är lika med NotDefined.

**Returnerar:**
java.awt.Color - Automatisk färg för serien java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Representerar inre punkter. Sant om inre punkter visas på BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Representerar inre punkter. Sant om inre punkter visas på BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Representerar avvikande punkter. Sant om avvikande punkter visas på BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Representerar avvikande punkter. Sant om avvikande punkter visas på BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Representerar medelvärdesmarkörer. Sant om medelvärdesmarkörer visas på BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Representerar medelvärdesmarkörer. Sant om medelvärdesmarkörer visas på BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Representerar medelvärdeslinjer. Sant om medellinjen visas på BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Representerar medelvärdeslinjer. Sant om medellinjen visas på BoxAndWhisker-diagrammet. Gäller endast för BoxAndWhisker-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Representerar kvartilmets metod. Gäller endast för BoxAndWhisker-diagram.

**Returnerar:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Representerar kvartilmets metod. Gäller endast för BoxAndWhisker-diagram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Representerar anslutningslinjer. Gäller endast för Waterfall-diagram.

**Returnerar:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Representerar anslutningslinjer. Gäller endast för Waterfall-diagram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Representerar layout för föräldrakategori-etiketter. Gäller endast för Treemap-diagram.

**Returnerar:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Representerar layout för föräldrakategori-etiketter. Gäller endast för Treemap-diagram.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Anger skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.BubbleSizeScale läs/skriv egenskap för att ändra värdet.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.BubbleSizeScale.

**Returnerar:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Bestämmer om linje- eller stapeldiagram har upp-/ned-staplar. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.UpDownBars.HasUpDownBars läs/skriv egenskap för att ändra värdet. Använd ParentSeriesGroup.UpDownBars-egenskap för att formatera upp-/ned-staplar. Skrivskyddad boolean.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Returnerar:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Anger avståndet mellan stapel- eller kolumnkluster, som procent av stapel- eller kolumnbredden. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.GapWidth läs/skriv egenskap för att ändra värdet. Skrivskyddad int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.GapWidth.

**Returnerar:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Returnerar eller anger avståndet, som procent av markörbredden, mellan dataserier i ett 3D-diagram. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.GapDepth läs/skriv egenskap för att ändra värdet. Skrivskyddad int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.GapDepth.

**Returnerar:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Anger att varje datamarkör i serien har en annan färg. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.IsColorVaried läs/skriv egenskap för att ändra värdet. Skrivskyddad boolean.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.IsColorVaried.

**Returnerar:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Bestämmer om det finns serielinjer för denna serie och besläktade serier. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.HasSeriesLines läs/skriv egenskap för att ändra värdet. Använd ParentSeriesGroup.SeriesLinesFormat-egenskap för att formatera serielinjer. Skrivskyddad boolean.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.HasSeriesLines.

**Returnerar:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Anger hur mycket staplar och kolumner överlappar i 2-D-diagram, som procent (från -100 % till 100 %). Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen. Det är en projektion av den lämpliga egenskapen i den överordnade serieggruppen, och därför är denna egenskap skrivskyddad. För att ändra värdet, använd ParentSeriesGroup.Overlap läs/skriv egenskap. Skrivskyddad byte.

--------------------

Overlap anger graden av överlappning eller avstånd mellan staplar och kolumner som procent av deras bredd:
- -100 %: Maximalt avstånd (staplar är helt separerade).
- 0 %: Staplar placeras sida vid sida utan överlappning eller avstånd.
- 100 %: Maximal överlappning (staplar överlappar helt varandra).
Detta är en projektion av egenskapen ParentSeriesGroup.Overlap.

**Returnerar:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Anger storleken på den andra pajen eller stapeln i ett paj-i-paj-diagram eller stapel-i-paj-diagram, som procent av den första pajens storlek (kan vara mellan 5 och 200 procent). Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.SecondPieSize läs/skriv egenskap för att ändra värdet. Skrivskyddad int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.SecondPieSize.

**Returnerar:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som hamnar i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Används tillsammans med PieSplitBy-egenskapen. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.PieSplitPosition läs/skriv egenskap för att ändra värdet. Skrivskyddad double.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.PieSplitPosition.

**Returnerar:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Anger hur man bestämmer vilka datapunkter som hamnar i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.PieSplitBy läs/skriv egenskap för att ändra värdet. Skrivskyddad [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Detta är projektionen av egenskapen ParentSeriesGroup.PieSplitBy. 2) Om egenskapsvärdet är PieSplitType.Custom kan du definiera anpassad split-information med ParentSeriesGroup.PieSplitCustomPoints-egenskapen.

**Returnerar:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Anger storleken på hålet i ett munk-diagram (kan vara mellan 10 och 90 procent av plot-områdets storlek). Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.DoughnutHoleSize läs/skriv egenskap för att ändra värdet. Skrivskyddad byte.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.DoughnutHoleSize.

**Returnerar:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Anger vinkeln för det första paj- eller munk-diagram-segmentet, i grader (medurs från upp, från 0 till 360 grader). Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup-egenskap för åtkomst till den överordnade serieggruppen. Använd ParentSeriesGroup.FirstSliceAngle läs/skriv egenskap för att ändra värdet. Skrivskyddad int.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.FirstSliceAngle.

**Returnerar:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Den anpassade split-informationen för ett paj-i-paj- eller stapel-i-paj-diagram med anpassad split. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Detta är en egenskap som inte bara gäller denna serie utan alla serier i den överordnade serieggruppen - detta är en projektion av lämplig grupp-egenskap Skrivskyddad [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.PieSplitCustomPoints.

**Returnerar:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Anger hur värdena för bubbelförstorlek representeras i bubbeldiagrammet. Detta är egenskapen inte bara för den här serien utan för alla serier i den överordnade serieggruppen – det är en projektion av lämplig gruppegenskap. Och därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till den överordnade serieggruppen. Använd egenskapen ParentSeriesGroup.BubbleSizeRepresentation läs/skriv för att ändra värdet.

--------------------

Detta är projektionen av egenskapen ParentSeriesGroup.BubbleSizeRepresentation.

**Returns:**
int