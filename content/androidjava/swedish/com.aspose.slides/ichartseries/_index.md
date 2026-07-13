---
title: IChartSeries
second_title: Aspose.Slides för Android via Java API-referens
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

| Method | Description |
| --- | --- |
| [getExplosion()](#getExplosion--) | Avståndet för en öppen tårtbit från centrum av pajdiagrammet uttrycks som en procentandel av pajens diameter. |
| [setExplosion(int value)](#setExplosion-int-) | Avståndet för en öppen tårtbit från centrum av pajdiagrammet uttrycks som en procentandel av pajens diameter. |
| [getSmooth()](#getSmooth--) | Representerar kurvutjämning. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Representerar kurvutjämning. |
| [getMarker()](#getMarker--) | Returnerar seriemarkör. |
| [getBar3DShape()](#getBar3DShape--) | Anger formen för en serie i ett 3D-stapeldiagram. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Anger formen för en serie i ett 3D-stapeldiagram. |
| [getName()](#getName--) | Returnerar seriens namn. |
| [getDataPoints()](#getDataPoints--) | Returnerar en samling datapunkter för denna serie. |
| [getType()](#getType--) | Returnerar en typ av denna serie. |
| [setType(int value)](#setType-int-) | Returnerar en typ av denna serie. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Returnerar den överordnade seriegrouppen. |
| [getFormat()](#getFormat--) | Returnerar formatet för en serie. |
| [getOrder()](#getOrder--) | Returnerar ordningen för en serie. |
| [setOrder(int value)](#setOrder-int-) | Returnerar ordningen för en serie. |
| [getLabels()](#getLabels--) | Returnerar etiketterna för en serie. |
| [getTrendLines()](#getTrendLines--) | Samling av serietrendlinjer skrivskyddad [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Representerar felstaplar för serien med riktning X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Representerar felstaplar för serien med riktning Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indikerar om denna serie plottas på sekundär värdeaxel. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indikerar om denna serie plottas på sekundär värdeaxel. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Returnerar eller anger talformatet för seriens värden. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Returnerar eller anger talformatet för seriens värden. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Returnerar eller anger talformatet för serie X-värden. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Returnerar eller anger talformatet för serie X-värden. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Returnerar eller anger talformatet för serie Y-värden. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Returnerar eller anger talformatet för serie Y-värden. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Returnerar eller anger talformatet för seriens bubbeltstorlekar. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Returnerar eller anger talformatet för seriens bubbeltstorlekar. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Anger att stapel-, kolumn- eller bubbelserie ska invertera sina färger om värdet är negativt. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Anger att stapel-, kolumn- eller bubbelserie ska invertera sina färger om värdet är negativt. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Anger inverterad solid färg för serien. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representerar legendpost relaterad till denna serie skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Returnerar en automatisk färg för serien baserat på seriens index och diagramstil. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Representerar innerpunkter. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Representerar innerpunkter. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Representerar avvikande punkter. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Representerar avvikande punkter. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Representerar medelmarkörer. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Representerar medelmarkörer. |
| [getShowMeanLine()](#getShowMeanLine--) | Representerar medelmarkörer. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Representerar medelmarkörer. |
| [getQuartileMethod()](#getQuartileMethod--) | Representerar kvartilmetod. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Representerar kvartilmetod. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Representerar anslutningslinjer. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Representerar anslutningslinjer. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Representerar layout för föräldrakategorietiketter. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Representerar layout för föräldrakategorietiketter. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Anger skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). |
| [hasUpDownBars()](#hasUpDownBars--) | Avgör om linje- eller aktiediagram har upp/ner-staplar. |
| [getGapWidth()](#getGapWidth--) | Anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapelns eller kolumnens bredd. |
| [getGapDepth()](#getGapDepth--) | Returnerar eller anger avståndet, som en procentandel av markörens bredd, mellan dataserier i ett 3D-diagram. |
| [isColorVaried()](#isColorVaried--) | Anger att varje datamarkör i serien har en annan färg. |
| [hasSeriesLines()](#hasSeriesLines--) | Avgör om det finns serielinjer för denna serie och relaterade serier. |
| [getOverlap()](#getOverlap--) | Anger hur mycket staplar och kolumner överlappar på 2-D-diagram, som en procentandel (från -100 % till 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Anger storleken på den andra pajen eller stapeln i ett paj-i-paj-diagram eller stapel-i-paj-diagram, som en procentandel av storleken på den första pajen (kan vara mellan 5 och 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Anger storleken på hålet i ett donutdiagram (kan vara mellan 10 och 90 % av storleken på plotområdet). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Anger vinkeln för den första paj- eller donutdiagramdelen, i grader (medurs från upprätt, från 0 till 360 grader). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Den anpassade split-informationen för ett paj-i-paj- eller stapel-i-paj-diagram med anpassad split. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Anger hur bubbeltstorleksvärdena representeras i bubbeldiagrammet. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Avståndet för en öppen tårtbit från centrum av pajdiagrammet uttrycks som en procentandel av pajens diameter. Läs/skriv int.

**Returnerar:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Avståndet för en öppen tårtbit från centrum av pajdiagrammet uttrycks som en procentandel av pajens diameter. Läs/skriv int.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Representerar kurvutjämning. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Läs/skriv boolean.

**Returnerar:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Representerar kurvutjämning. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Returnerar seriemarkör. Skrivskyddad [IMarker](../../com.aspose.slides/imarker).

**Returnerar:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Anger formen för en serie i ett 3D-stapeldiagram. Changing of value of this property can cause to automatically changing Type of series. Läs/skriv [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Returnerar:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Anger formen för en serie i ett 3D-stapeldiagram. Changing of value of this property can cause to automatically changing Type of series. Läs/skriv [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Returnerar seriens namn. Skrivskyddad [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Returnerar:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Returnerar en samling datapunkter för denna serie. Skrivskyddad [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Returnerar den överordnade seriegrouppen. Skrivskyddad [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

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
| Parameter | Type | Description |
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

Samling av serietrendlinjer skrivskyddad [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Returnerar:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Representerar felstaplar för serien med riktning X. Skrivskyddad [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Returnerar:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Representerar felstaplar för serien med riktning Y. Skrivskyddad [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Returnerar:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indikerar om denna serie plottas på sekundär värdeaxel. Läs/skriv boolean.

**Returnerar:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Indikerar om denna serie plottas på sekundär värdeaxel. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Returnerar eller anger talformatet för seriens värden. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Returnerar eller anger talformatet för seriens värden. Läs/skriv String.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Returnerar eller anger talformatet för serie X-värden. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Returnerar eller anger talformatet för serie X-värden. Läs/skriv String.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Returnerar eller anger talformatet för serie Y-värden. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Returnerar eller anger talformatet för serie Y-värden. Läs/skriv String.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Returnerar eller anger talformatet för seriens bubbeltstorlekar. Läs/skriv String.

**Returnerar:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Returnerar eller anger talformatet för seriens bubbeltstorlekar. Läs/skriv String.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Anger att stapel-, kolumn- eller bubbelserie ska invertera sina färger om värdet är negativt. Läs/skriv boolean.

**Returnerar:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Anger att stapel-, kolumn- eller bubbelserie ska invertera sina färger om värdet är negativt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Anger inverterad solid färg för serien. To apply color setting set series format FillType to FillType.Solid. Läs/skriv [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Representerar legendpost relaterad till denna serie skrivskyddad [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returnerar:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Returnerar en automatisk färg för serien baserat på seriens index och diagramstil. This color is used by default if FillType equals NotDefined.

**Returnerar:**
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Representerar innerpunkter. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Läs/skriv boolean.

**Returnerar:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Representerar innerpunkter. True if inner points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Representerar avvikande punkter. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Läs/skriv boolean.

**Returnerar:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Representerar avvikande punkter. True if outlier points are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Representerar medelmarkörer. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Läs/skriv boolean.

**Returnerar:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Representerar medelmarkörer. True if mean markers are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Representerar medelmarkörer. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Läs/skriv boolean.

**Returnerar:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Representerar medelmarkörer. True if mean line are shown on the BoxAndWhisker chart. Applies only to BoxAndWhisker charts. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Representerar kvartilmetod. Applies only to BoxAndWhisker charts.

**Returnerar:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Representerar kvartilmetod. Applies only to BoxAndWhisker charts.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Representerar anslutningslinjer. Applies only to Waterfall charts.

**Returnerar:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Representerar anslutningslinjer. Applies only to Waterfall charts.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Representerar layout för föräldrakategorietiketter. Applies only to Treemap charts.

**Returnerar:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Representerar layout för föräldrakategorietiketter. Applies only to Treemap charts.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Anger skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**Returnerar:**
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Avgör om linje- eller aktiediagram har upp/ner-staplar. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Skrivskyddad boolean.

--------------------

This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Returnerar:**
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapelns eller kolumnens bredd. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Skrivskyddad int.

--------------------

This is the projection of the property ParentSeriesGroup.GapWidth.

**Returnerar:**
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Returnerar eller anger avståndet, som en procentandel av markörens bredd, mellan dataserier i ett 3D-diagram. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Skrivskyddad int.

--------------------

This is the projection of the property ParentSeriesGroup.GapDepth.

**Returnerar:**
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Anger att varje datamarkör i serien har en annan färg. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Skrivskyddad boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**Returnerar:**
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Avgör om det finns serielinjer för denna serie och relaterade serier. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Skrivskyddad boolean.

--------------------

This is the projection of the property ParentSeriesGroup.HasSeriesLines.

**Returnerar:**
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Anger hur mycket staplar och kolumner överlappar på 2-D-diagram, som en procentandel (från -100 % till 100 %). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the ParentSeriesGroup.Overlap read/write property. Skrivskyddad byte .

--------------------

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width: - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This is a projection of the property ParentSeriesGroup.Overlap.

**Returnerar:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Anger storleken på den andra pajen eller stapeln i ett paj-i-paj-diagram eller stapel-i-paj-diagram, som en procentandel av storleken på den första pajen (kan vara mellan 5 och 200 %). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Skrivskyddad int.

--------------------

This is the projection of the property ParentSeriesGroup.SecondPieSize.

**Returnerar:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Skrivskyddad double.

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitPosition.

**Returnerar:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Skrivskyddad [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property.

**Returnerar:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Anger storleken på hålet i ett donutdiagram (kan vara mellan 10 och 90 % av storleken på plotområdet). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Skrivskyddad byte.

--------------------

This is the projection of the property ParentSeriesGroup.DoughnutHoleSize.

**Returnerar:**
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Anger vinkeln för den första paj- eller donutdiagramdelen, i grader (medurs från upprätt, från 0 till 360 grader). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Skrivskyddad int.

--------------------

This is the projection of the property ParentSeriesGroup.FirstSliceAngle.

**Returnerar:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Den anpassade split-informationen för ett paj-i-paj- eller stapel-i-paj-diagram med anpassad split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Read-only [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints.

**Returnerar:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Anger hur bubbeltstorleksvärdena representeras i bubbeldiagrammet. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation.

**Returnerar:**
int