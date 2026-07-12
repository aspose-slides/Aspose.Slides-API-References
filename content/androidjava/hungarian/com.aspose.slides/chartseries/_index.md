---
title: ChartSeries
second_title: Aspose.Slides Android számára Java API referencia
description: Diagram sorozatot képvisel.
type: docs
url: /hu/com.aspose.slides/chartseries/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Egy diagram sorozatot képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [getExplosion()](#getExplosion--) | A nyitott körszelet középponttól való távolsága a kör átmérőjének százalékában van megadva. |
| [setExplosion(int value)](#setExplosion-int-) | A nyitott körszelet középponttól való távolsága a kör átmérőjének százalékában van megadva. |
| [getSmooth()](#getSmooth--) | Görbe simítást ábrázol. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Görbe simítást ábrázol. |
| [getName()](#getName--) | Visszaadja a sorozat nevét. |
| [getDataPoints()](#getDataPoints--) | Visszaadja ennek a sorozatnak az adatpontok gyűjteményét. |
| [getType()](#getType--) | Visszaadja ennek a sorozatnak a típusát. |
| [setType(int value)](#setType-int-) | Visszaadja ennek a sorozatnak a típusát. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Jelzi, hogy a sorozat a másodlagos tengelyen van-e ábrázolva. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Jelzi, hogy a sorozat a másodlagos tengelyen van-e ábrázolva. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Visszaadja a sorozat formátumát. |
| [getOrder()](#getOrder--) | Visszaadja a sorozat sorrendjét. |
| [setOrder(int value)](#setOrder-int-) | Visszaadja a sorozat sorrendjét. |
| [getLabels()](#getLabels--) | Visszaadja a sorozat címkéit. |
| [getTrendLines()](#getTrendLines--) | Sorozat trendvonalak gyűjteménye. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X irányú hibasávokat ábrázol a sorozatra vonatkozóan. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y irányú hibasávokat ábrázol a sorozatra vonatkozóan. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A sorozathoz kapcsolódó jelmagyarázat bejegyzést ábrázol. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Meghatározza egy 3-D oszlopdiagram sorozat alakját. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Meghatározza egy 3-D oszlopdiagram sorozat alakját. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Meghatározza, hogy az oszlop, oszlop vagy buboréksorozat negatív érték esetén megfordítsa-e a színeket. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Meghatározza, hogy az oszlop, oszlop vagy buboréksorozat negatív érték esetén megfordítsa-e a színeket. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Meghatározza a sorozat invertált szilárd színét. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Visszaad egy automatikus színt a sorozat indexe és a diagram stílusa alapján. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Belső pontokat ábrázol. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Belső pontokat ábrázol. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Kiugró pontokat ábrázol. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Kiugró pontokat ábrázol. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Átlagjelölőket ábrázol. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Átlagjelölőket ábrázol. |
| [getShowMeanLine()](#getShowMeanLine--) | Átlagvonalat ábrázol. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Átlagvonalat ábrázol. |
| [getQuartileMethod()](#getQuartileMethod--) | Kvartilis módszert ábrázol. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Kvartilis módszert ábrázol. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Kapcsolóvonalakat ábrázol. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Kapcsolóvonalakat ábrázol. |
| [getParentLabelLayout()](#getParentLabelLayout--) | A szülő kategória címkéinek elrendezését ábrázolja. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | A szülő kategória címkéinek elrendezését ábrázolja. |
| [hasUpDownBars()](#hasUpDownBars--) | Meghatározza, hogy a vonal- vagy részvénydiagram rendelkezik-e fel-levonallal. |
| [getGapWidth()](#getGapWidth--) | Megadja a oszlop- vagy sávcsoportok közti távolságot a szélesség százalékában. |
| [getGapDepth()](#getGapDepth--) | Visszaadja vagy beállítja a távolságot a marker szélességének százalékában, a 3D diagram sorozatai között. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Megadja az első kör- vagy fánkdiagram szeletének szögét fokban (az óramutató járásával megegyező irányban fentről, 0-tól 360 fokig). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Megadja a fánkdiagram középpontjának méretét (10-90 % a rajzterület méretétől). |
| [getOverlap()](#getOverlap--) | Megadja, hogy a sávok és oszlopok mennyire fednek-ek egymást 2-D diagramokban, százalékban (-100 %-tól 100 %-ig). |
| [getSecondPieSize()](#getSecondPieSize--) | Megadja a második kör vagy sáv méretét egy kör-kör vagy sáv-kör diagramon, a első kör méretének százalékában (5-200 % között). |
| [hasSeriesLines()](#hasSeriesLines--) | Meghatározza, hogy vannak-e sorozatvonalak a sorozat és rokon sorozatok számára. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Meghatározza, hogyan jelennek meg a buborékméret-értékek a buborékdiagramon. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Megad egy értéket, amely meghatározza, mely adatpontok vannak a második körben vagy sávban egy kör-kör vagy sáv-kör diagramon. |
| [getPieSplitBy()](#getPieSplitBy--) | Meghatározza, hogyan kell meghatározni, mely adatpontok vannak a második körben vagy sávban egy kör-kör vagy sáv-kör diagramon. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Az egyéni felosztási információ egy egyéni felosztással rendelkező kör-kör vagy sáv-kör diagramhoz. |
| [isColorVaried()](#isColorVaried--) | Meghatározza, hogy a sorozat minden adatjelölője különböző színű legyen. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Meghatározza a buborékdiagram léptékfaktorát (0-300 % az alapmérettől). |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülődiáját. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülőprezentációját. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a szülő diagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatér:**
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

A nyitott körszelet középponttól való távolsága a kör átmérőjének százalékában van megadva. Olvasható/írható int.

**Visszatér:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

A nyitott körszelet középponttól való távolsága a kör átmérőjének százalékában van megadva. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Görbe simítást ábrázol. True, ha a görbe simítás be van kapcsolva vonaldiagramoknál vagy pontdiagramoknál. Csak vonaldiagramok és vonallal összekötött pontdiagramok esetén érvényes. Olvasható/írható boolean.

**Visszatér:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Görbe simítást ábrázol. True, ha a görbe simítás be van kapcsolva vonaldiagramoknál vagy pontdiagramoknál. Csak vonaldiagramok és vonallal összekötött pontdiagramok esetén érvényes. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Visszaadja a sorozat nevét. Csak olvasható [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Visszatér:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Visszaadja ennek a sorozatnak az adatpontok gyűjteményét. Csak olvasható [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Visszatér:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

Visszaadja a sorozat típusát. Olvasható/írható [ChartType](../../com.aspose.slides/charttype).

**Visszatér:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Visszaadja a sorozat típusát. Olvasható/írható [ChartType](../../com.aspose.slides/charttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Jelzi, hogy a sorozat a másodlagos tengelyen van-e ábrázolva. Olvasható/írható boolean.

**Visszatér:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Jelzi, hogy a sorozat a másodlagos tengelyen van-e ábrázolva. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Csak olvasható [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Visszatér:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Visszaadja a sorozat formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

Visszaadja a sorozat sorrendjét. Olvasható/írható int.

**Visszatér:**
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Visszaadja a sorozat sorrendjét. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Visszaadja a sorozat címkéit. Csak olvasható [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Visszatér:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Sorozat trendvonalak gyűjteménye. Csak olvasható [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

A trendvonalak elérhetők (nem null) olyan adat sorozatokhoz, amelyek nem halmozott 2-D terület, oszlop, sáv, vonal, részvény, XY (szórás) és buborék diagramokban. Trendvonal nem elérhető halmozott vagy 3-D diagramokhoz. Trendvonal nem érhető el radar, kör, felület vagy fánk diagramokhoz sem.

**Visszatér:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

X irányú hibasávokat ábrázol a sorozatra vonatkozóan. Csak olvasható [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

X irányú hibasávok elérhetők area, bar, scatter és bubble típusú sorozatokhoz. Más diagramtípusok esetén ez a tulajdonság null értéket ad (beleértve a 3D diagramokat). Egyéni értékek esetén használja a DataPoints gyűjteményt a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonsággal.

**Visszatér:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Y irányú hibasávokat ábrázol a sorozatra vonatkozóan. Csak olvasható [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

Y irányú hibasávok elérhetők area, bar, line, scatter és bubble típusú sorozatokhoz. Más diagramtípusok esetén ez a tulajdonság null értéket ad (beleértve a 3D diagramokat). Egyéni értékek esetén használja a DataPoints gyűjteményt a ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) tulajdonsággal.

**Visszatér:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

A sorozathoz kapcsolódó jelmagyarázat bejegyzést ábrázol. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatér:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Olvasható/írható String.

**Visszatér:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Csak olvasható [IMarker](../../com.aspose.slides/imarker).

**Visszatér:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Meghatározza egy 3-D oszlopdiagram sorozat alakját. Ennek a tulajdonságnak az értékének módosítása automatikusan megváltoztathatja a sorozat típusát. Olvasható/írható [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Visszatér:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Meghatározza egy 3-D oszlopdiagram sorozat alakját. Ennek a tulajdonságnak az értékének módosítása automatikusan megváltoztathatja a sorozat típusát. Olvasható/írható [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Meghatározza, hogy az oszlop, oszlop vagy buboréksorozat negatív érték esetén megfordítsa-e a színeket. Olvasható/írható boolean.

**Visszatér:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Meghatározza, hogy az oszlop, oszlop vagy buboréksorozat negatív érték esetén megfordítsa-e a színeket. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Meghatározza a sorozat invertált szilárd színét. Szín beállításához állítsa a sorozat formátumának FillType-ját FillType.Solid-ra. Olvasható/írható [ColorFormat](../../com.aspose.slides/colorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Visszaad egy automatikus színt a sorozat indexe és a diagram stílusa alapján. Ez a szín alapértelmezésként használatos, ha a FillType NotDefined értékű.

**Visszatér:**
java.lang.Integer - A java.lang.Integer objektum.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Belső pontokat ábrázol. True, ha a BoxAndWhisker diagramon belső pontok jelennek meg. Csak BoxAndWhisker diagramokra érvényes. Olvasható/írható boolean.

**Visszatér:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Belső pontokat ábrázol. True, ha a BoxAndWhisker diagramon belső pontok jelennek meg. Csak BoxAndWhisker diagramokra érvényes. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Kiugró pontokat ábrázol. True, ha a BoxAndWhisker diagramon kiugró pontok jelennek meg. Csak BoxAndWhisker diagramokra érvényes. Olvasható/írható boolean.

**Visszatér:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Kiugró pontokat ábrázol. True, ha a BoxAndWhisker diagramon kiugró pontok jelennek meg. Csak BoxAndWhisker diagramokra érvényes. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Átlagjelölőket ábrázol. True, ha a BoxAndWhisker diagramon átlagjelölők jelennek meg. Csak BoxAndWhisker diagramokra érvényes. Olvasható/írható boolean.

**Visszatér:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Átlagjelölőket ábrázol. True, ha a BoxAndWhisker diagramon átlagjelölők jelennek meg. Csak BoxAndWhisker diagramokra érvényes. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Átlagvonalat ábrázol. True, ha a BoxAndWhisker diagramon átlagvonal jelenik meg. Csak BoxAndWhisker diagramokra érvényes. Olvasható/írható boolean.

**Visszatér:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Átlagvonalat ábrázol. True, ha a BoxAndWhisker diagramon átlagvonal jelenik meg. Csak BoxAndWhisker diagramokra érvényes. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Kvartilis módszert ábrázol. Csak BoxAndWhisker diagramokra érvényes.

**Visszatér:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Kvartilis módszert ábrázol. Csak BoxAndWhisker diagramokra érvényes.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Kapcsolóvonalakat ábrázol. Csak Waterfall diagramokra érvényes.

**Visszatér:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Kapcsolóvonalakat ábrázol. Csak Waterfall diagramokra érvényes.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

A szülő kategória címkéinek elrendezését ábrázolja. Csak Treemap diagramokra érvényes.

**Visszatér:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

A szülő kategória címkéinek elrendezését ábrázolja. Csak Treemap diagramokra érvényes.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Meghatározza, hogy a vonal- vagy részvénydiagram rendelkezik-e fel-le-vonallal. Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. A fel-le-vonalak értékének módosításához használja a ParentSeriesGroup.UpDownBars.HasUpDownBars olvasható/írható tulajdonságot. A fel-le-vonalak formázásához használja a ParentSeriesGroup.UpDownBars tulajdonságot. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.UpDownBars.HasUpDownBars tulajdonság projekciója.

**Visszatér:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Megadja a oszlop- vagy sávcsoportok közti távolságot a szélesség százalékában. Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.GapWidth olvasható/írható tulajdonságot. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.GapWidth tulajdonság projekciója.

**Visszatér:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Visszaadja vagy beállítja a távolságot a marker szélességének százalékában, a 3D diagram sorozatai között. Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.GapDepth olvasható/írható tulajdonságot. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.GapDepth tulajdonság projekciója.

**Visszatér:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Megadja az első kör- vagy fánkdiagram szeletének szögét fokban (az óramutató járásával megegyező irányban fentről, 0-tól 360 fokig). Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.FirstSliceAngle olvasható/írható tulajdonságot. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.FirstSliceAngle tulajdonság projekciója.

**Visszatér:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Megadja a fánkdiagram középpontjának méretét (10-90 % a rajzterület méretétől). Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.DoughnutHoleSize olvasható/írható tulajdonságot. Csak olvasható byte.

--------------------

Ez a ParentSeriesGroup.DoughnutHoleSize tulajdonság projekciója.

**Visszatér:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Megadja, hogy a sávok és oszlopok mennyire fednek-ek egymást 2-D diagramokban, százalékban (-100 %-tól 100 %-ig). Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik. A megfelelő csoport tulajdonság projekciója, ezért ez a tulajdonság csak olvasható. Az érték módosításához használja a ParentSeriesGroup.Overlap olvasható/írható tulajdonságot. Csak olvasható byte.

--------------------

Az átfedés a sávok és oszlopok szélességének százalékában meghatározott átfedési vagy távolsági fokot jelenti:
- -100 %: Maximális távolság (a sávok teljesen szét vannak választva).
- 0 %: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül.
- 100 %: Maximális átfedés (a sávok teljesen átfedik egymást).

Ez a ParentSeriesGroup.Overlap tulajdonság projekciója.

**Visszatér:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Megadja a második kör vagy sáv méretét egy kör-kör vagy sáv-kör diagramon, a első kör méretének százalékában (5-200 % között). Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.SecondPieSize olvasható/írható tulajdonságot. Csak olvasható int.

--------------------

Ez a ParentSeriesGroup.SecondPieSize tulajdonság projekciója.

**Visszatér:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Meghatározza, hogy vannak-e sorozatvonalak a sorozat és rokon sorozatok számára. Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.HasSeriesLines olvasható/írható tulajdonságot. A sorozatvonalak formázásához használja a ParentSeriesGroup.SeriesLinesFormat tulajdonságot. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.HasSeriesLines tulajdonság projekciója.

**Visszatér:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Meghatározza, hogyan jelennek meg a buborékméret-értékek a buborékdiagramon. Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.BubbleSizeRepresentation olvasható/írható tulajdonságot.

--------------------

Ez a ParentSeriesGroup.BubbleSizeRepresentation tulajdonság projekciója.

**Visszatér:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Megad egy értéket, amelyet a második kör vagy sáv meghatározásához használnak egy kör-kör vagy sáv-kör diagramon. A PieSplitBy tulajdonsággal együtt használatos. Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.PieSplitPosition olvasható/írható tulajdonságot. Csak olvasható double.

--------------------

Ez a ParentSeriesGroup.PieSplitPosition tulajdonság projekciója.

**Visszatér:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Meghatározza, hogyan kell meghatározni, mely adatpontok vannak a második körben vagy sávban egy kör-kör vagy sáv-kör diagramon. Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.PieSplitBy olvasható/írható tulajdonságot. Csak olvasható [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Ez a ParentSeriesGroup.PieSplitBy tulajdonság projekciója. 2) Ha a tulajdonság értéke PieSplitType.Custom, egyéni felosztási információ definiálható a ParentSeriesGroup.PieSplitCustomPoints tulajdonsággal.

**Visszatér:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

A egyéni felosztási információ egy egyéni felosztással rendelkező kör-kör vagy sáv-kör diagramhoz. Az adatpontokat, amelyek a második körben vagy sávban jelennek meg, tartalmazza. Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója Csak olvasható [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Ez a ParentSeriesGroup.PieSplitCustomPoints tulajdonság projekciója.

**Visszatér:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Meghatározza, hogy a sorozat minden adatjelölője különböző színű legyen. Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.IsColorVaried olvasható/írható tulajdonságot. Csak olvasható boolean.

--------------------

Ez a ParentSeriesGroup.IsColorVaried tulajdonság projekciója.

**Visszatér:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Meghatározza a buborékdiagram léptékfaktorát (0-300 % az alapmérettől). Ez a tulajdonság nem csak a sorozatra, hanem a szülő sorozatcsoport összes sorozatára vonatkozik – ez a megfelelő csoport tulajdonságának projekciója. Ez a tulajdonság csak olvasható. A szülő sorozatcsoport eléréséhez használja a ParentSeriesGroup tulajdonságot. Az érték módosításához használja a ParentSeriesGroup.BubbleSizeScale olvasható/írható tulajdonságot.

--------------------

Ez a ParentSeriesGroup.BubbleSizeScale tulajdonság projekciója.

**Visszatér:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülődiáját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülőprezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)