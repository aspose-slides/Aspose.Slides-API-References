---
title: IChartSeries
second_title: Aspose.Slides Androidhoz a Java API hivatkozásán keresztül
description: Diagram sorozatot képvisel.
type: docs
url: /hu/com.aspose.slides/ichartseries/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Egy diagram sorozatot képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getExplosion()](#getExplosion--) | A nyitott kördiagram szelet távolsága a kör középpontjától a kör átmérőjének százalékában van kifejezve. |
| [setExplosion(int value)](#setExplosion-int-) | A nyitott kördiagram szelet távolsága a kör középpontjától a kör átmérőjének százalékában van kifejezve. |
| [getSmooth()](#getSmooth--) | A görbe simítást képviseli. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | A görbe simítást képviseli. |
| [getMarker()](#getMarker--) | Visszaadja a sorozat jelölőt. |
| [getBar3DShape()](#getBar3DShape--) | Megadja egy 3D oszlopdiagram sorozatának alakját. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Megadja egy 3D oszlopdiagram sorozatának alakját. |
| [getName()](#getName--) | Visszaadja a sorozat nevét. |
| [getDataPoints()](#getDataPoints--) | Visszaadja ennek a sorozatnak az adatpontok gyűjteményét. |
| [getType()](#getType--) | Visszaadja a sorozat típusát. |
| [setType(int value)](#setType-int-) | Visszaadja a sorozat típusát. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Visszaadja a szülő sorozatcsoportot. |
| [getFormat()](#getFormat--) | Visszaadja a sorozat formátumát. |
| [getOrder()](#getOrder--) | Visszaadja a sorozat sorrendjét. |
| [setOrder(int value)](#setOrder-int-) | Visszaadja a sorozat sorrendjét. |
| [getLabels()](#getLabels--) | Visszaadja a sorozat címkéit. |
| [getTrendLines()](#getTrendLines--) | A sorozat trendvonalak gyűjteménye Csak olvasható [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | A sorozat X irányú hibasávjait képviseli. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | A sorozat Y irányú hibasávjait képviseli. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Jeleníti, hogy ez a sorozat a második érték tengelyen van-e ábrázolva. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Jeleníti, hogy ez a sorozat a második érték tengelyen van-e ábrázolva. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Visszaadja vagy beállítja a sorozat értékeinek számformátumát. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Visszaadja vagy beállítja a sorozat értékeinek számformátumát. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Visszaadja vagy beállítja a sorozat x értékeinek számformátumát. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Visszaadja vagy beállítja a sorozat x értékeinek számformátumát. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Visszaadja vagy beállítja a sorozat y értékeinek számformátumát. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Visszaadja vagy beállítja a sorozat y értékeinek számformátumát. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Visszaadja vagy beállítja a sorozat buborékméreteinek számformátumát. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Visszaadja vagy beállítja a sorozat buborékméreteinek számformátumát. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Megadja, hogy a sáv, oszlop vagy buborék sorozat negatív érték esetén megfordítsa színeit. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Megadja, hogy a sáv, oszlop vagy buborék sorozat negatív érték esetén megfordítsa színeit. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Megadja a sorozat szilárd színének invertálását. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A sorozathoz kapcsolódó jelmagyarázat bejegyzést képviseli Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Visszaad egy automatikus színt a sorozathoz a sorozat index és a diagram stílus alapján. |
| [getShowInnerPoints()](#getShowInnerPoints--) | A belső pontokat képviseli. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | A belső pontokat képviseli. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | A kiugró pontokat képviseli. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | A kiugró pontokat képviseli. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Az átlagjeleket képviseli. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Az átlagjeleket képviseli. |
| [getShowMeanLine()](#getShowMeanLine--) | Az átlagjeleket képviseli. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Az átlagjeleket képviseli. |
| [getQuartileMethod()](#getQuartileMethod--) | A kvartilis módszert képviseli. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | A kvartilis módszert képviseli. |
| [getShowConnectorLines()](#getShowConnectorLines--) | A csatlakozó vonalakat képviseli. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | A csatlakozó vonalakat képviseli. |
| [getParentLabelLayout()](#getParentLabelLayout--) | A szülő kategória címkék elrendezését képviseli. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | A szülő kategória címkék elrendezését képviseli. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Megadja a méretezési tényezőt a buborékdiagramhoz (0 és az alapméret 300 százaléka között). |
| [hasUpDownBars()](#hasUpDownBars--) | Megállapítja, hogy vonal- vagy részvény-diagram rendelkezik-e fel/le oszlopokkal. |
| [getGapWidth()](#getGapWidth--) | Megadja a sáv vagy oszlop csoportok közötti távolságot a sáv vagy oszlop szélességének százalékában. |
| [getGapDepth()](#getGapDepth--) | Visszaadja vagy beállítja a távolságot, a marker szélességének százalékában, a 3D diagram adat sorozatai között. |
| [isColorVaried()](#isColorVaried--) | Megadja, hogy a sorozat minden adatjelzője más színű legyen. |
| [hasSeriesLines()](#hasSeriesLines--) | Megállapítja, hogy vannak-e sorozatvonalak ehhez a sorozathoz és rokon sorozatokhoz. |
| [getOverlap()](#getOverlap--) | Megadja, hogy a sávok és oszlopok mennyire fedik át egymást 2D diagramokban, százalékban (–100%-tól 100%-ig). |
| [getSecondPieSize()](#getSecondPieSize--) | Megadja a második kör vagy sáv méretét egy kör-kör vagy sáv-kör diagramban, az első kör méretének százalékában (5 és 200 százalék között). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Megad egy értéket, amely alapján meghatározzák, hogy mely adatpontok szerepelnek a második körben vagy sávban egy kör-kör vagy sáv-kör diagramban. |
| [getPieSplitBy()](#getPieSplitBy--) | Megadja, hogyan határozzák meg, hogy mely adatpontok vannak a második körben vagy sávban egy kör-kör vagy sáv-kör diagramon. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Megadja a lyuk méretét egy fánkdiagramban (10 és 90 százalék között a rajzterület méretéhez képest). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Megadja az első kör vagy fánk diagram szeletének szögét fokban (óramutató járásával megegyező irányba felfelé, 0-tól 360 fokig). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Az egyéni felosztási információ egy kör-kör vagy sáv-kör diagramhoz egy egyedi felosztással. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Megadja, hogy a buborék méret értékek hogyan jelennek meg a buborékdiagramon. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

A nyitott kördiagram szelet távolsága a kör középpontjától a kör átmérőjének százalékában van kifejezve. Olvasás/írás int.

**Visszatér:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

A nyitott kördiagram szelet távolsága a kör középpontjától a kör átmérőjének százalékában van kifejezve. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

A görbe simítást képviseli. True ha a görbe simítás be van kapcsolva vonaldiagramhoz vagy szórásdiagramhoz. Csak vonaldiagramokra és vonalakkal összekapcsolt szórásdiagramokra vonatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

A görbe simítást képviseli. True ha a görbe simítás be van kapcsolva vonaldiagramhoz vagy szórásdiagramhoz. Csak vonaldiagramokra és vonalakkal összekapcsolt szórásdiagramokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Visszaadja a sorozat jelölőt. Csak olvasható [IMarker](../../com.aspose.slides/imarker).

**Visszatér:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Megadja egy 3D oszlopdiagram sorozatának alakját. Az érték módosítása automatikusan megváltoztathatja a sorozat típusát. Olvasás/írás [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Visszatér:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Megadja egy 3D oszlopdiagram sorozatának alakját. Az érték módosítása automatikusan megváltoztathatja a sorozat típusát. Olvasás/írás [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Visszaadja a sorozat nevét. Csak olvasható [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Visszatér:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Visszaadja ennek a sorozatnak az adatpontok gyűjteményét. Csak olvasható [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Visszatér:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

Visszaadja a sorozat típusát. Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Visszatér:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Visszaadja a sorozat típusát. Olvasás/írás [ChartType](../../com.aspose.slides/charttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Visszaadja a szülő sorozatcsoportot. Csak olvasható [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Visszatér:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Visszaadja a sorozat formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Visszaadja a sorozat sorrendjét. Olvasás/írás int.

**Visszatér:**
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

**Visszatér:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

A sorozat trendvonalak gyűjteménye Csak olvasható [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Visszatér:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

A sorozat X irányú hibasávjait képviseli. Csak olvasható [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Az X irányú hibasávok elérhetők a area, bar, scatter és bubble típusú sorozatoknál. Más diagramtípusoknál ez a tulajdonság null értéket ad (beleértve a 3D diagramokat). Egyéni értékek esetén a DataPoints gyűjteményt használja az érték megadására ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) tulajdonsággal).

**Visszatér:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

A sorozat Y irányú hibasávjait képviseli. Csak olvasható [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Az Y irányú hibasávok elérhetők a area, bar, line, scatter és bubble típusú sorozatoknál. Más diagramtípusoknál ez a tulajdonság null értéket ad (beleértve a 3D diagramokat). Egyéni értékek esetén a DataPoints gyűjteményt használja az érték megadására ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) tulajdonsággal).

**Visszatér:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Jelzi, hogy ez a sorozat a második érték tengelyen van-e ábrázolva. Olvasás/írás boolean.

**Visszatér:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Jelzi, hogy ez a sorozat a második érték tengelyen van-e ábrázolva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Visszaadja vagy beállítja a sorozat értékeinek számformátumát. Olvasás/írás String.

**Visszatér:**
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

**Visszatér:**
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

**Visszatér:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
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

Visszaadja vagy beállítja a sorozat buborékméreteinek számformátumát. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Visszaadja vagy beállítja a sorozat buborékméreteinek számformátumát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Megadja, hogy a sáv, oszlop vagy buborék sorozat negatív érték esetén megfordítsa színeit. Olvasás/írás boolean.

**Visszatér:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Megadja, hogy a sáv, oszlop vagy buborék sorozat negatív érték esetén megfordítsa színeit. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Megadja a sorozat szilárd színének invertálását. A szín beállításához a sorozat formátumának FillType tulajdonságát FillType.Solid-ra állítsa. Olvasás/írás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

A sorozathoz kapcsolódó jelmagyarázat bejegyzést képviseli Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatér:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Visszaad egy automatikus színt a sorozathoz a sorozat index és a diagram stílus alapján. Ez a szín alapértelmezésként használatos, ha a FillType értéke NotDefined.

**Visszatér:**
java.lang.Integer - Automatic color of series java.lang.Integer
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

A belső pontokat képviseli. Igaz, ha a belső pontok megjelennek a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

A belső pontokat képviseli. Igaz, ha a belső pontok megjelennek a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

A kiugró pontokat képviseli. Igaz, ha a kiugró pontok megjelennek a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

A kiugró pontokat képviseli. Igaz, ha a kiugró pontok megjelennek a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Az átlagjeleket képviseli. Igaz, ha az átlagjelölők megjelennek a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Az átlagjeleket képviseli. Igaz, ha az átlagjelölők megjelennek a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Az átlagjeleket képviseli. Igaz, ha az átlagvonal megjelenik a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Az átlagjeleket képviseli. Igaz, ha az átlagvonal megjelenik a BoxAndWhisker diagramon. Csak BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

A kvartilis módszert képviseli. Csak BoxAndWhisker diagramokra vonatkozik.

**Visszatér:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

A kvartilis módszert képviseli. Csak BoxAndWhisker diagramokra vonatkozik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

A csatlakozó vonalakat képviseli. Csak Waterfall diagramokra vonatkozik.

**Visszatér:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

A csatlakozó vonalakat képviseli. Csak Waterfall diagramokra vonatkozik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

A szülő kategória címkék elrendezését képviseli. Csak Treemap diagramokra vonatkozik.

**Visszatér:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

A szülő kategória címkék elrendezését képviseli. Csak Treemap diagramokra vonatkozik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Megadja a méretezési tényezőt a buborékdiagramhoz (0 és az alapméret 300 százaléka között). Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.BubbleSizeScale olvasás/írás tulajdonságot használja az érték módosításához.

--------------------

Ez a ParentSeriesGroup.BubbleSizeScale tulajdonság projekciója.

**Visszatér:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Megállapítja, hogy vonal- vagy részvény-diagram rendelkezik-e fel/le oszlopokkal. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.UpDownBars.HasUpDownBars olvasás/írás tulajdonságot használja az érték módosításához. A ParentSeriesGroup.UpDownBars tulajdonságot használja a fel/le oszlopok formátumához. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.UpDownBars.HasUpDownBars tulajdonság projekciója.

**Visszatér:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Megadja a sáv vagy oszlop csoportok közötti távolságot a sáv vagy oszlop szélességének százalékában. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.GapWidth olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.GapWidth tulajdonság projekciója.

**Visszatér:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Visszaadja vagy beállítja a távolságot, a marker szélességének százalékában, a 3D diagram adat sorozatai között. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.GapDepth olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.GapDepth tulajdonság projekciója.

**Visszatér:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Megadja, hogy a sorozat minden adatjelzője más színű legyen. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.IsColorVaried olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.IsColorVaried tulajdonság projekciója.

**Visszatér:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Megállapítja, hogy vannak-e sorozatvonalak ehhez a sorozathoz és rokon sorozatokhoz. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.HasSeriesLines olvasás/írás tulajdonságot használja az érték módosításához. A ParentSeriesGroup.SeriesLinesFormat tulajdonságot használja a sorozatvonalak formázásához. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.HasSeriesLines tulajdonság projekciója.

**Visszatér:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Megadja, hogy a sávok és oszlopok mennyire fedik át egymást 2D diagramokban, százalékban (–100%-tól 100%-ig). Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes. Ez a megfelelő csoporttulajdonság projekciója, ezért ez a tulajdonság csak olvasható. Az érték módosításához használja a ParentSeriesGroup.Overlap olvasás/írás tulajdonságot. Csak olvasható byte .

--------------------

Az átfedés meghatározza a sávok és oszlopok közti átfedés vagy távolság mértékét a szélességük százalékában: –100%: maximális távolság (sávok teljesen elválnak). 0%: sávok egymás mellett, átfedés vagy távolság nélkül. 100%: maximális átfedés (sávok teljesen átfedik egymást). Ez a ParentSeriesGroup.Overlap tulajdonság projekciója.

**Visszatér:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Megadja a második kör vagy sáv méretét egy kör-kör vagy sáv-kör diagramban, az első kör méretének százalékában (5 és 200 százalék között). Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.SecondPieSize olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.SecondPieSize tulajdonság projekciója.

**Visszatér:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public
```

Megad egy értéket, amely alapján meghatározzák, hogy mely adatpontok vannak a második körben vagy sávban egy kör-kör vagy sáv-kör diagramon. A PieSplitBy tulajdonsággal együtt használatos. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.PieSplitPosition olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható double.

--------------------

Ez a ParentSeriesGroup.PieSplitPosition tulajdonság projekciója.

**Visszatér:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Megadja, hogyan határozzák meg, hogy mely adatpontok vannak a második körben vagy sávban egy kör-kör vagy sáv-kör diagramon. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.PieSplitBy olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Ez a ParentSeriesGroup.PieSplitBy tulajdonság projekciója. 2) Ha a tulajdonság értéke PieSplitType.Custom, akkor egyéni felosztási információt adhat meg a ParentSeriesGroup.PieSplitCustomPoints tulajdonsággal.

**Visszatér:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Megadja a lyuk méretét egy fánkdiagramban (10 és 90 százalék között a rajzterület méretéhez képest). Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.DoughnutHoleSize olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható byte.

--------------------

Ez a ParentSeriesGroup.DoughnutHoleSize tulajdonság projekciója.

**Visszatér:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Megadja az első kör vagy fánk diagram szeletének szögét fokban (óramutató járásával megegyező irányba felfelé, 0-tól 360 fokig). Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.FirstSliceAngle olvasás/írás tulajdonságot használja az érték módosításához. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.FirstSliceAngle tulajdonság projekciója.

**Visszatér:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Az egyéni felosztási információ egy kör-kör vagy sáv-kör diagramhoz egy egyedi felosztással. Tartalmazza azokat az adatpontokat, amelyeket a második körben vagy sávban kell megjeleníteni. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója Csak olvasható [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Ez a ParentSeriesGroup.PieSplitCustomPoints tulajdonság projekciója.

**Visszatér:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Megadja, hogy a buborék méret értékek hogyan jelennek meg a buborékdiagramon. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál érvényes – ez a megfelelő csoporttulajdonság projekciója. Így ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A ParentSeriesGroup.BubbleSizeRepresentation olvasás/írás tulajdonságot használja az érték módosításához.

--------------------

Ez a ParentSeriesGroup.BubbleSizeRepresentation tulajdonság projekciója.

**Visszatér:**
int