---
title: IChartSeries
second_title: Aspose.Slides for Java API referenciája
description: Egy diagram sorozatot képvisel.
type: docs
url: /hu/com.aspose.slides/ichartseries/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

A diagram sorozatát ábrázolja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getExplosion()](#getExplosion--) | A nyitott tortaszelet középponttól való távolsága a torta átmérőjének százalékában van megadva. |
| [setExplosion(int value)](#setExplosion-int-) | A nyitott tortaszelet középponttól való távolsága a torta átmérőjének százalékában van megadva. |
| [getSmooth()](#getSmooth--) | A görbe simítását jelöli. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | A görbe simítását jelöli. |
| [getMarker()](#getMarker--) | Visszaadja a sorozat markerét. |
| [getBar3DShape()](#getBar3DShape--) | Megadja egy 3-D bar chart sorozatának alakját. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Megadja egy 3-D bar chart sorozatának alakját. |
| [getName()](#getName--) | Visszaadja a sorozat nevét. |
| [getDataPoints()](#getDataPoints--) | Visszaadja ennek a sorozatnak az adatpontok gyűjteményét. |
| [getType()](#getType--) | Visszaad egy típust ehhez a sorozathoz. |
| [setType(int value)](#setType-int-) | Visszaad egy típust ehhez a sorozathoz. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Visszaadja a szülő sorozatcsoportot. |
| [getFormat()](#getFormat--) | Visszaadja a sorozat formátumát. |
| [getOrder()](#getOrder--) | Visszaadja a sorozat sorrendjét. |
| [setOrder(int value)](#setOrder-int-) | Visszaadja a sorozat sorrendjét. |
| [getLabels()](#getLabels--) | Visszaadja a sorozat címkéit. |
| [getTrendLines()](#getTrendLines--) | A sorozat trendvonalainak gyűjteménye, csak olvasható [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Az X irányú hibasávokat ábrázolja a sorozatban. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Az Y irányú hibasávokat ábrázolja a sorozatban. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Jelzi, hogy a sorozat a második érték tengelyen van-e ábrázolva. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Jelzi, hogy a sorozat a második érték tengelyen van-e ábrázolva. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Visszaadja vagy beállítja a sorozat értékeinek számformátumát. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Visszaadja vagy beállítja a sorozat értékeinek számformátumát. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Visszaadja vagy beállítja a sorozat x értékeinek számformátumát. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Visszaadja vagy beállítja a sorozat x értékeinek számformátumát. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Visszaadja vagy beállítja a sorozat y értékeinek számformátumát. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Visszaadja vagy beállítja a sorozat y értékeinek számformátumát. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Visszaadja vagy beállítja a sorozat buborékméretének számformátumát. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Visszaadja vagy beállítja a sorozat buborékméretének számformátumát. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Megadja, hogy a sáv, oszlop vagy buborék sorozat színe negatív érték esetén invertálódik-e. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Megadja, hogy a sáv, oszlop vagy buborék sorozat színe negatív érték esetén invertálódik-e. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Megadja a sorozat invertált szilárd színét. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A sorozathoz kapcsolódó jelmagyarázat bejegyzést jelöli, csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Visszaad egy automatikus színt a sorozathoz a sorozat index és a diagram stílus alapján. |
| [getShowInnerPoints()](#getShowInnerPoints--) | A belső pontokat jelöli. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | A belső pontokat jelöli. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | A kiugró pontokat jelöli. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | A kiugró pontokat jelöli. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | A középérték jelzőket jelöli. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | A középérték jelzőket jelöli. |
| [getShowMeanLine()](#getShowMeanLine--) | A középérték jelzőket jelöli. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | A középérték jelzőket jelöli. |
| [getQuartileMethod()](#getQuartileMethod--) | A kvartilis módszert jelöli. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | A kvartilis módszert jelöli. |
| [getShowConnectorLines()](#getShowConnectorLines--) | A csatlakozó vonalakat jelöli. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | A csatlakozó vonalakat jelöli. |
| [getParentLabelLayout()](#getParentLabelLayout--) | A szülő kategória címkéinek elrendezését jelöli. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | A szülő kategória címkéinek elrendezését jelöli. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Megadja a buborékdiagram skálázási tényezőjét (0-300 % az alapmérettől). |
| [hasUpDownBars()](#hasUpDownBars--) | Meghatározza, hogy a vonal- vagy részvénydiagram rendelkezik-e fel-le csíkokkal. |
| [getGapWidth()](#getGapWidth--) | Megadja a sáv- vagy oszloptömbök közti távolságot, a sáv vagy oszlop szélességének százalékában. |
| [getGapDepth()](#getGapDepth--) | Visszaadja vagy beállítja a távolságot, a marker szélességének százalékában, a 3D diagram adat sorozatai között. |
| [isColorVaried()](#isColorVaried--) | Megadja, hogy a sorozat minden adatmarkerének más színe legyen. |
| [hasSeriesLines()](#hasSeriesLines--) | Meghatározza, hogy vannak-e sorozatvonalak ehhez a sorozathoz és kapcsolódó sorozatokhoz. |
| [getOverlap()](#getOverlap--) | Megadja, hogy a sávok és oszlopok mennyire fedik egymást 2-D diagramokban, százalékban (-100 %-tól +100 %-ig). |
| [getSecondPieSize()](#getSecondPieSize--) | Megadja a második torta vagy sáv méretét egy torta-torta vagy sáv-torta diagramban, a első torta méretének százalékában (5-200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Megad egy értéket, amely meghatározza, mely adatpontok vannak a második tortában vagy sávban egy torta-torta vagy sáv-torta diagramon. |
| [getPieSplitBy()](#getPieSplitBy--) | Meghatározza, hogy milyen módon dönthető el, mely adatpontok vannak a második tortában vagy sávban egy torta-torta vagy sáv-torta diagramon. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Megadja a lyuk méretét egy fánk diagramban (10-90 % a plotterület méretétől). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Megadja az első torta vagy fánk szelet szögét fokban (az órától óramutató járásával megegyező irányban, 0-tól 360 fokig). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Egy torta-torta vagy sáv-torta diagram egyedi felosztási információja. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Megadja, hogy a buborékméret értékek hogyan jelennek meg a buborékdiagramon. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

A nyitott tortaszelet középponttól való távolsága a torta átmérőjének százalékában van megadva. Olvasás/írás int.

**Visszaad:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

A nyitott tortaszelet középponttól való távolsága a torta átmérőjének százalékában van megadva. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

A görbe simítását jelöli. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Olvasás/írás boolean.

**Visszaad:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

A görbe simítását jelöli. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Visszaadja a sorozat markerét. Csak olvasható [IMarker](../../com.aspose.slides/imarker).

**Visszaad:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Megadja egy 3-D bar chart sorozatának alakját. Changing of value of this property can cause to automatically changing Type of series. Olvasás/írás [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Visszaad:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Megadja egy 3-D bar chart sorozatának alakját. Changing of value of this property can cause to automatically changing Type of series. Olvasás/írás [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Visszaadja a sorozat nevét. Csak olvasható [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Visszaad:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Visszaadja ennek a sorozatnak az adatpontok gyűjteményét. Csak olvasható [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Visszaad:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

Visszaad egy típust ehhez a sorozathoz. Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Visszaad:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Visszaad egy típust ehhez a sorozathoz. Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Visszaadja a szülő sorozatcsoportot. Csak olvasható [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Visszaad:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Visszaadja a sorozat formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszaad:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Visszaadja a sorozat sorrendjét. Olvasás/írás int.

**Visszaad:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Visszaadja a sorozat sorrendjét. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Visszaadja a sorozat címkéit. Csak olvasható [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Visszaad:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

A sorozat trendvonalainak gyűjteménye, csak olvasható [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Visszaad:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Az X irányú hibasávokat ábrázolja a sorozatban. Csak olvasható [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Visszaad:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Az Y irányú hibasávokat ábrázolja a sorozatban. Csak olvasható [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Visszaad:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Jelzi, hogy a sorozat a második érték tengelyen van-e ábrázolva. Olvasás/írás boolean.

**Visszaad:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Jelzi, hogy a sorozat a második érték tengelyen van-e ábrázolva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Visszaadja vagy beállítja a sorozat értékeinek számformátumát. Olvasás/írás String.

**Visszaad:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Visszaadja vagy beállítja a sorozat értékeinek számformátumát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Visszaadja vagy beállítja a sorozat x értékeinek számformátumát. Olvasás/írás String.

**Visszaad:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Visszaadja vagy beállítja a sorozat x értékeinek számformátumát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Visszaadja vagy beállítja a sorozat y értékeinek számformátumát. Olvasás/írás String.

**Visszaad:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberOfValues(String value)
```

Visszaadja vagy beállítja a sorozat y értékeinek számformátumát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Visszaadja vagy beállítja a sorozat buborékméretének számformátumát. Olvasás/írás String.

**Visszaad:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Visszaadja vagy beállítja a sorozat buborékméretének számformátumát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Megadja, hogy a sáv, oszlop vagy buborék sorozat színe negatív érték esetén invertálódik-e. Olvasás/írás boolean.

**Visszaad:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Megadja, hogy a sáv, oszlop vagy buborék sorozat színe negatív érték esetén invertálódik-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Megadja a sorozat invertált szilárd színét. To apply color setting set series format FillType to FillType.Solid. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszaad:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

A sorozathoz kapcsolódó jelmagyarázat bejegyzést jelöli, csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszaad:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined.

**Visszatérési érték:**  
java.awt.Color - A sorozat automatikus színe java.awt.Color

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Represents inner points. Igaz, ha a belső pontok megjelennek a BoxAndWhisker charton. Csak a BoxAndWhisker chartokra vonatkozik. Olvasás/írás boolean.

**Visszatérési érték:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Represents inner points. Igaz, ha a belső pontok megjelennek a BoxAndWhisker charton. Csak a BoxAndWhisker chartokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Represents outlier points. Igaz, ha a kiugró pontok megjelennek a BoxAndWhisker charton. Csak a BoxAndWhisker chartokra vonatkozik. Olvasás/írás boolean.

**Visszatérési érték:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Represents outlier points. Igaz, ha a kiugró pontok megjelennek a BoxAndWhisker charton. Csak a BoxAndWhisker chartokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Represents mean markers. Igaz, ha az átlagjelölők megjelennek a BoxAndWhisker charton. Csak a BoxAndWhisker chartokra vonatkozik. Olvasás/írás boolean.

**Visszatérési érték:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Represents mean markers. Igaz, ha az átlagjelölők megjelennek a BoxAndWhisker charton. Csak a BoxAndWhisker chartokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Represents mean markers. Igaz, ha az átlagvonal megjelenik a BoxAndWhisker charton. Csak a BoxAndWhisker chartokra vonatkozik. Olvasás/írás boolean.

**Visszatérési érték:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Represents mean markers. Igaz, ha az átlagvonal megjelenik a BoxAndWhisker charton. Csak a BoxAndWhisker chartokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Represents quartile method. Csak a BoxAndWhisker chartokra vonatkozik.

**Visszatérési érték:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Represents quartile method. Csak a BoxAndWhisker chartokra vonatkozik.

**Paraméterek:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Represents connector lines. Csak a Waterfall chartokra vonatkozik.

**Visszatérési érték:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Represents connector lines. Csak a Waterfall chartokra vonatkozik.

**Paraméterek:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Represents layout of parent category labels. Csak a Treemap chartokra vonatkozik.

**Visszatérési érték:**  
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Represents layout of parent category labels. Csak a Treemap chartokra vonatkozik.

**Paraméterek:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

Ez a ParentSeriesGroup.BubbleSizeScale tulajdonság projekciója.

**Visszatérési érték:**  
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Determines whether Line- or Stock-chart has a up/down bars. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.UpDownBars.HasUpDownBars read/write property for change value. Use ParentSeriesGroup.UpDownBars property for format up/down bars. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.UpDownBars.HasUpDownBars tulajdonság projekciója.

**Visszatérési érték:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Specifies the space between bar or column clusters, as a percentage of the bar or column width. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapWidth read/write property for change value. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.GapWidth tulajdonság projekciója.

**Visszatérési érték:**  
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.GapDepth read/write property for change value. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.GapDepth tulajdonság projekciója.

**Visszatérési érték:**  
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.IsColorVaried tulajdonság projekciója.

**Visszatérési érték:**  
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Determines whether there are series lines for this series and kindred series. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.HasSeriesLines read/write property for change value. Use ParentSeriesGroup.SeriesLinesFormat property for format series lines. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.HasSeriesLines tulajdonság projekciója.

**Visszatérési érték:**  
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). This is the property not only of this series but of all series of parent series group. It is a projection of the appropriate property in the parent series group, and so this property is read-only. To change the value, use the ParentSeriesGroup.Overlap read/write property. Csak olvasható byte.

--------------------

Az Overlap a sávok és oszlopok átfedésének vagy távolságának százalékos megadása: -100%: maximális távolság (a sávok teljesen szét vannak). 0%: a sávok találkoznak átfedés vagy távolság nélkül. 100%: maximális átfedés (a sávok teljesen egymásra fedik). Ez a ParentSeriesGroup.Overlap tulajdonság projekciója.

**Visszatérési érték:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.SecondPieSize read/write property for change value. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.SecondPieSize tulajdonság projekciója.

**Visszatérési érték:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. Is used together with PieSplitBy property. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitPosition read/write property for change value. Csak olvasható double.

--------------------

Ez a ParentSeriesGroup.PieSplitPosition tulajdonság projekciója.

**Visszatérési érték:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.PieSplitBy read/write property for change value. Csak olvasható [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Ez a ParentSeriesGroup.PieSplitBy tulajdonság projekciója. 2) Ha a tulajdonság értéke PieSplitType.Custom, akkor egyedi szétválasztási információt adhat meg a ParentSeriesGroup.PieSplitCustomPoints tulajdonsággal.

**Visszatérési érték:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.DoughnutHoleSize read/write property for change value. Csak olvasható byte.

--------------------

Ez a ParentSeriesGroup.DoughnutHoleSize tulajdonság projekciója.

**Visszatérési érték:**  
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Specifies the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.FirstSliceAngle read/write property for change value. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.FirstSliceAngle tulajdonság projekciója.

**Visszatérési érték:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. Contains data points that shall be drawn in the second pie or bar in a pie-of-pie or bar-of-pie chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property Csak olvasható [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Ez a ParentSeriesGroup.PieSplitCustomPoints tulajdonság projekciója.

**Visszatérési érték:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Meghatározza, hogy a buborékméret értékek hogyan jelennek meg a buborékdiagramon. Ez a tulajdonság nem csak az adott sorozatra vonatkozik, hanem a szülő sorozatcsoport összes sorozatára - ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. Használja a ParentSeriesGroup tulajdonságot a szülő sorozatcsoport eléréséhez. Használja a ParentSeriesGroup.BubbleSizeRepresentation olvasható/írható tulajdonságot az érték módosításához.

--------------------

Ez a ParentSeriesGroup.BubbleSizeRepresentation tulajdonság projekciója.

**Visszatérési érték:**
int