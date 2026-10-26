---
title: ChartSeries
second_title: Aspose.Slides Java API hivatkozás
description: Egy diagram sorozatot képvisel.
type: docs
url: /hu/com.aspose.slides/chartseries/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

A diagram sorozatát képviseli.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [getExplosion()](#getExplosion--) | A nyitott kördiagram szelet középponttól mért távolsága a kör átmérőjének százalékában van kifejezve. |
| [setExplosion(int value)](#setExplosion-int-) | A nyitott kördiagram szelet középponttól mért távolsága a kör átmérőjének százalékában van kifejezve. |
| [getSmooth()](#getSmooth--) | A görbe simítását jelöli. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | A görbe simítását jelöli. |
| [getName()](#getName--) | Visszaadja a sorozat nevét. |
| [getDataPoints()](#getDataPoints--) | Visszaadja ennek a sorozatnak az adatpontok gyűjteményét. |
| [getType()](#getType--) | Visszaadja ennek a sorozatnak a típusát. |
| [setType(int value)](#setType-int-) | Visszaadja ennek a sorozatnak a típusát. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Jelzi, hogy ez a sorozat a másodlagos tengelyen van-e ábrázolva. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Jelzi, hogy ez a sorozat a másodlagos tengelyen van-e ábrázolva. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Visszaadja a sorozat formátumát. |
| [getOrder()](#getOrder--) | Visszaadja egy sorozat sorrendjét. |
| [setOrder(int value)](#setOrder-int-) | Visszaadja egy sorozat sorrendjét. |
| [getLabels()](#getLabels--) | Visszaadja a sorozat címkéit. |
| [getTrendLines()](#getTrendLines--) | A sorozat trendvonalainak gyűjteménye. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Az X irányú hibasávokat képviseli a sorozat. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Az Y irányú hibasávokat képviseli a sorozat. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A sorozathoz kapcsolódó jelmagyarázat bejegyzést jelöli. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Megadja a 3-D oszlopdiagram sorozat formáját. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Megadja a 3-D oszlopdiagram sorozat formáját. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Megadja, hogy az oszlop, oszlopdiagram vagy buborék sorozat színei negatív érték esetén megforduljanak. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Megadja, hogy az oszlop, oszlopdiagram vagy buborék sorozat színei negatív érték esetén megforduljanak. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Megadja a sorozat invertált szilárd színét. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Visszaad egy automatikus színt a sorozathoz a sorozat indexe és a diagram stílusa alapján. |
| [getShowInnerPoints()](#getShowInnerPoints--) | A belső pontokat jelöli. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | A belső pontokat jelöli. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | A kiugró pontokat jelöli. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | A kiugró pontokat jelöli. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | A középérték jelzőket jelöli. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | A középérték jelzőket jelöli. |
| [getShowMeanLine()](#getShowMeanLine--) | A középérték vonalat jelöli. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | A középérték vonalat jelöli. |
| [getQuartileMethod()](#getQuartileMethod--) | A kvartilis módszert jelöli. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | A kvartilis módszert jelöli. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Kapcsoló vonalakat jelöli. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Kapcsoló vonalakat jelöli. |
| [getParentLabelLayout()](#getParentLabelLayout--) | A szülő kategória címkék elrendezését jelöli. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | A szülő kategória címkék elrendezését jelöli. |
| [hasUpDownBars()](#hasUpDownBars--) | Meghatározza, hogy a vonal- vagy részvénydiagramnak van-e fel/le oszlopa. |
| [getGapWidth()](#getGapWidth--) | Megadja a sávok vagy oszlopcsoportok közötti távolságot, a sáv vagy oszlop szélességének százalékában. |
| [getGapDepth()](#getGapDepth--) | Visszaadja vagy beállítja a távolságot, a jelölő szélességének százalékában, a 3D diagram adat sorozatai között. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Megadja az első kördiagram vagy fánkdiagram szeletének szögét fokban (az órakör irányában fentről, 0-tól 360 fokig). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Megadja a fánkdiagram lyuk méretét (10 % és 90 % között a plot terület méretéhez képest). |
| [getOverlap()](#getOverlap--) | Megadja, hogy a sávok és oszlopok mennyire fedik át egymást 2-D diagramokban, százalékban (-100 %-től 100 %-ig). |
| [getSecondPieSize()](#getSecondPieSize--) | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5 %-tól 200 %-ig). |
| [hasSeriesLines()](#hasSeriesLines--) | Meghatározza, hogy van-e sorozatsorok ehhez a sorozathoz és kapcsolódó sorozatokhoz. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Megadja, hogy a buborékméret értékek hogyan jelennek meg a buborék diagramon. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Megadja azt az értéket, amely meghatározza, hogy mely adatpontok vannak a második körön vagy sávon egy pie-of-pie vagy bar-of-pie diagramon. |
| [getPieSplitBy()](#getPieSplitBy--) | Megadja, hogyan határozzuk meg, mely adatpontok vannak a második körön vagy sávon egy pie-of-pie vagy bar-of-pie diagramon. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Az egyéni felosztási információ egy egyéni felosztású pie-of-pie vagy bar-of-pie diagramhoz. |
| [isColorVaried()](#isColorVaried--) | Megadja, hogy a sorozat minden adatjelzője különböző színű legyen. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Megadja a skálafaktort a buborék diagram számára (0 %-tól 300 %-ig az alapmérettől). |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülődiaját. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő prezentációját. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. **Csak olvasható** IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a szülő diagramot. **Csak olvasható** [IChart](../../com.aspose.slides/ichart).

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

A nyitott kördiagram szelet középponttól mért távolsága a kör átmérőjének százalékában van kifejezve. **Olvasás/írás** int.

**Visszatérési érték:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

A nyitott kördiagram szelet középponttól mért távolsága a kör átmérőjének százalékában van kifejezve. **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

A görbe simítását jelöli. True, ha a görbe simítása be van kapcsolva vonaldiagramhoz vagy szórásdiagramhoz. Csak vonaldiagramokra és vonalakkal összekapcsolt szórásdiagramokra alkalmazható. **Olvasás/írás** boolean.

**Visszatérési érték:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

A görbe simítását jelöli. True, ha a görbe simítása be van kapcsolva vonaldiagramhoz vagy szórásdiagramhoz. Csak vonaldiagramokra és vonalakkal összekapcsolt szórásdiagramokra alkalmazható. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Visszaadja a sorozat nevét. **Csak olvasható** [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Visszatérési érték:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Visszaadja ennek a sorozatnak az adatpontok gyűjteményét. **Csak olvasható** [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Visszatérési érték:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

Visszaadja ennek a sorozatnak a típusát. **Olvasás/írás** [ChartType](../../com.aspose.slides/charttype).

**Visszatérési érték:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Visszaadja ennek a sorozatnak a típusát. **Olvasás/írás** [ChartType](../../com.aspose.slides/charttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Jelzi, hogy ez a sorozat a másodlagos tengelyen van-e ábrázolva. **Olvasás/írás** boolean.

**Visszatérési érték:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Jelzi, hogy ez a sorozat a másodlagos tengelyen van-e ábrázolva. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. **Csak olvasható** [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Visszatérési érték:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Visszaadja a sorozat formátumát. **Csak olvasható** [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

Visszaadja egy sorozat sorrendjét. **Olvasás/írás** int.

**Visszatérési érték:**
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Visszaadja egy sorozat sorrendjét. **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Visszaadja a sorozat címkéit. **Csak olvasható** [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Visszatérési érték:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

A sorozat trendvonalainak gyűjteménye. **Csak olvasható** [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

A trendvonalak elérhetők (nem null) adat sorozatokhoz a nem halmozott 2-D terület, oszlop, oszlopdiagram, vonal, részvény, xy (szórás) és buborék diagramoknál. Trendvonal nem érhető el halmozott vagy 3-D diagramoknál. A radar, kör, felület és fánk diagramok sem támogatják a trendvonalakat.

**Visszatérési érték:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Az X irányú hibasávokat képviseli a sorozat. **Csak olvasható** [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Az X irányú hibasávok elérhetők area, bar, scatter és bubble típusú sorozatoknál. Más típusú diagramok esetén ez a tulajdonság null értéket ad vissza (beleértve a 3D diagramokat is). Egyedi értékekhez a DataPoints gyűjteményt kell használni a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonsággal.

**Visszatérési érték:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Az Y irányú hibasávokat képviseli a sorozat. **Csak olvasható** [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Az Y irányú hibasávok elérhetők area, bar, line, scatter és bubble típusú sorozatoknál. Más típusú diagramok esetén ez a tulajdonság null értéket ad vissza (beleértve a 3D diagramokat is). Egyedi értékekhez a DataPoints gyűjteményt kell használni a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonsággal.

**Visszatérési érték:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

A sorozathoz kapcsolódó jelmagyarázat bejegyzést jelöli. **Csak olvasható** [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatérési érték:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. **Olvasás/írás** String.

**Visszatérési érték:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. **Olvasás/írás** String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. **Olvasás/írás** String.

**Visszatérési érték:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. **Olvasás/írás** String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. **Olvasás/írás** String.

**Visszatérési érték:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. **Olvasás/írás** String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. **Olvasás/írás** String.

**Visszatérési érték:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. **Olvasás/írás** String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. **Csak olvasható** [IMarker](../../com.aspose.slides/imarker).

**Visszatérési érték:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Megadja a 3-D oszlopdiagram sorozat formáját. Ennek a tulajdonságnak az értékének módosítása automatikusan megváltoztathatja a sorozat típusát. **Olvasás/írás** [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Visszatérési érték:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Megadja a 3-D oszlopdiagram sorozat formáját. Ennek a tulajdonságnak az értékének módosítása automatikusan megváltoztathatja a sorozat típusát. **Olvasás/írás** [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Megadja, hogy az oszlop, oszlopdiagram vagy buborék sorozat színei negatív érték esetén megforduljanak. **Olvasás/írás** boolean.

**Visszatérési érték:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Megadja, hogy az oszlop, oszlopdiagram vagy buborék sorozat színei negatív érték esetén megforduljanak. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Olvasás/írás [ColorFormat](../../com.aspose.slides/colorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

Visszaad egy automatikus színt a sorozathoz a sorozat indexe és a diagram stílusa alapján. Ez a szín az alapértelmezett, ha a FillType értéke NotDefined.

**Visszatér:**
java.awt.Color - A java.awt.Color objektum.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Képviseli a belső pontokat. Igaz, ha a belső pontok megjelennek a BoxAndWhisker diagramon. Csak a BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Képviseli a belső pontokat. Igaz, ha a belső pontok megjelennek a BoxAndWhisker diagramon. Csak a BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Képviseli a kiugró pontokat. Igaz, ha a kiugró pontok megjelennek a BoxAndWhisker diagramon. Csak a BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Képviseli a kiugró pontokat. Igaz, ha a kiugró pontok megjelennek a BoxAndWhisker diagramon. Csak a BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Képviseli az átlagjelzőket. Igaz, ha az átlagjelzők megjelennek a BoxAndWhisker diagramon. Csak a BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Képviseli az átlagjelzőket. Igaz, ha az átlagjelzők megjelennek a BoxAndWhisker diagramon. Csak a BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Képviseli az átlagvonalat. Igaz, ha az átlagvonal megjelenik a BoxAndWhisker diagramon. Csak a BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Képviseli az átlagvonalat. Igaz, ha az átlagvonal megjelenik a BoxAndWhisker diagramon. Csak a BoxAndWhisker diagramokra vonatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Képviseli a kvartilis módszert. Csak a BoxAndWhisker diagramokra vonatkozik.

**Visszatér:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Képviseli a kvartilis módszert. Csak a BoxAndWhisker diagramokra vonatkozik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Képviseli a kapcsolóvonalakat. Csak a Waterfall diagramokra vonatkozik.

**Visszatér:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Képviseli a kapcsolóvonalakat. Csak a Waterfall diagramokra vonatkozik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Képviseli a szülő kategória címkék elrendezését. Csak a Treemap diagramokra vonatkozik.

**Visszatér:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Képviseli a szülő kategória címkék elrendezését. Csak a Treemap diagramokra vonatkozik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Meghatározza, hogy a Vonal- vagy Részvény-diagram rendelkezik-e fel/le oszlopokkal. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.UpDownBars.HasUpDownBars olvasás/írás tulajdonságot. A formázáshoz használja a ParentSeriesGroup.UpDownBars tulajdonságot. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.UpDownBars.HasUpDownBars tulajdonság projekciója.

**Visszatér:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Meghatározza az oszlop- vagy sávcsoportok közötti távolságot a sáv vagy oszlop szélességének százalékában. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.GapWidth olvasás/írás tulajdonságot. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.GapWidth tulajdonság projekciója.

**Visszatér:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Visszaadja vagy állítja be a távolságot a marker szélességének százalékában a 3D diagram adat-sorozatai között. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.GapDepth olvasás/írás tulajdonságot. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.GapDepth tulajdonság projekciója.

**Visszatér:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Meghatározza az első kördiagram vagy gyűrűdiagram szelet szögét fokban (az órával egyező irányban felfelé, 0-tól 360 fokig). Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.FirstSliceAngle olvasás/írás tulajdonságot. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.FirstSliceAngle tulajdonság projekciója.

**Visszatér:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Meghatározza a gyűrűdiagram lyuk méretét (a plot terület méretének 10-90 százaléka lehet). Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.DoughnutHoleSize olvasás/írás tulajdonságot. Csak olvasható byte.

--------------------

Ez a ParentSeriesGroup.DoughnutHoleSize tulajdonság projekciója.

**Visszatér:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Meghatározza, hogy a sávok és oszlopok mennyire fedik egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes. A megfelelő csoporttulajdonság projekciója, ezért ez a tulajdonság csak olvasható. Az érték módosításához használja a ParentSeriesGroup.Overlap olvasás/írás tulajdonságot. Csak olvasható byte.

--------------------

Az átfedés a sávok és oszlopok szélességének százalékában meghatározott átfedést vagy távolságot jelöli:
- -100 %: Maximális távolság (a sávok teljesen el vannak választva).
- 0 %: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül.
- 100 %: Maximális átfedés (a sávok teljesen egymásra fednek). Ez a ParentSeriesGroup.Overlap tulajdonság projekciója.

**Visszatér:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Meghatározza a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagram esetén, az első kör méretének százalékában (5-200 % között lehet). Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.SecondPieSize olvasás/írás tulajdonságot. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.SecondPieSize tulajdonság projekciója.

**Visszatér:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Meghatározza, hogy vannak-e sorozati vonalak ennél a sorozatnál és a kapcsolódó sorozatoknál. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.HasSeriesLines olvasás/írás tulajdonságot. A sorozati vonalak formázásához használja a ParentSeriesGroup.SeriesLinesFormat tulajdonságot. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.HasSeriesLines tulajdonság projekciója.

**Visszatér:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Meghatározza, hogy a buborékdiagramon a buborék méretértékek hogyan jelennek meg. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.BubbleSizeRepresentation olvasás/írás tulajdon

--------------------

Ez a ParentSeriesGroup.BubbleSizeRepresentation tulajdonság projekciója.

**Visszatér:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Meghatároz egy értéket, amelyet a pie-of-pie vagy bar-of-pie diagram második kör / sáv adatpontjainak meghatározásához használnak. A PieSplitBy tulajdonsággal együtt használatos. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.PieSplitPosition olvasás/írás tulajdonságot. Csak olvasható double.

--------------------

Ez a ParentSeriesGroup.PieSplitPosition tulajdonság projekciója.

**Visszatér:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Meghatározza, hogyan határozzuk meg, mely adatpontok kerülnek a második körbe vagy sávba egy pie-of-pie vagy bar-of-pie diagramon. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Ezért a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.PieSplitBy olvasás/írás tulajdonságot. Csak olvasható [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Ez a ParentSeriesGroup.PieSplitBy tulajdonság projekciója. 2) Ha a tulajdonság értéke PieSplitType.Custom, akkor a ParentSeriesGroup.PieSplitCustomPoints tulajdonsággal adhat meg egyéni felosztást.

**Visszatér:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Az egyéni felosztási információ egy pie-of-pie vagy bar-of-pie diagramhoz, amely egyedi felosztást használ. Az adatpontokat tartalmazza, amelyek a második körben vagy sávban jelennek meg egy pie-of-pie vagy bar-of-pie diagramon. Ez a tulajdonság nem csak ennél a sorozatnál, hanem a szülő sorozatcsoport összes sorozatánál is érvényes – ez a megfelelő csoporttulajdonság projekciója. Csak olvasható [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Ez a ParentSeriesGroup.PieSplitCustomPoints tulajdonság projekciója.

**Visszatér:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Megadja, hogy a sorozat minden adatjelzője különböző színnel rendelkezik. Ez a tulajdonság nem csak erre a sorozatra vonatkozik, hanem a szülő sorozatcsoport összes sorozatára – ez a megfelelő csoporttulajdonság kivetítése. Ezért ez a tulajdonság csak olvasható. Használja a ParentSeriesGroup tulajdonságot a szülő sorozatcsoport eléréséhez. A érték módosításához használja a ParentSeriesGroup.IsColorVaried írás/olvasás tulajdonságot. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.IsColorVaried tulajdonság kivetítése.

**Visszatérési érték:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Megadja a buborékurva méretezési tényezőjét (0 és az alapméret 300 százaléka között lehet). Ez a tulajdonság nem csak erre a sorozatra vonatkozik, hanem a szülő sorozatcsoport összes sorozatára – ez a megfelelő csoporttulajdonság kivetítése. Ezért ez a tulajdonság csak olvasható. Használja a ParentSeriesGroup tulajdonságot a szülő sorozatcsoport eléréséhez. A módosításhoz használja a ParentSeriesGroup.BubbleSizeScale írás/olvasás tulajdonságot.

--------------------

Ez a ParentSeriesGroup.BubbleSizeScale tulajdonság kivetítése.

**Visszatérési érték:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja egy FillFormat szülő diát. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja egy FillFormat szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)