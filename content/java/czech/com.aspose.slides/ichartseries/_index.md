---
title: IChartSeries
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje sérii grafu.
type: docs
url: /cs/com.aspose.slides/ichartseries/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Representuje sérii grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getExplosion()](#getExplosion--) | Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena v procentech průměru koláče. |
| [setExplosion(int value)](#setExplosion-int-) | Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena v procentech průměru koláče. |
| [getSmooth()](#getSmooth--) | Reprezentuje vyhlazování křivky. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Reprezentuje vyhlazování křivky. |
| [getMarker()](#getMarker--) | Vrací značku řady. |
| [getBar3DShape()](#getBar3DShape--) | Určuje tvar řady ve 3D sloupcovém grafu. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Určuje tvar řady ve 3D sloupcovém grafu. |
| [getName()](#getName--) | Vrací název řady. |
| [getDataPoints()](#getDataPoints--) | Vrací kolekci datových bodů této řady. |
| [getType()](#getType--) | Vrací typ této řady. |
| [setType(int value)](#setType-int-) | Vrací typ této řady. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Vrací nadřazenou skupinu řad. |
| [getFormat()](#getFormat--) | Vrací formát řady. |
| [getOrder()](#getOrder--) | Vrací pořadí řady. |
| [setOrder(int value)](#setOrder-int-) | Vrací pořadí řady. |
| [getLabels()](#getLabels--) | Vrací popisky řady. |
| [getTrendLines()](#getTrendLines--) | Kolekce trendových čar řady Jen pro čtení [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Reprezentuje chybové úsečky řady s orientací X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Reprezentuje chybové úsečky řady s orientací Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indikuje, zda je tato řada vykreslena na druhé ose hodnot. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indikuje, zda je tato řada vykreslena na druhé ose hodnot. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Vrací nebo nastavuje číselný formát hodnot řady. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Vrací nebo nastavuje číselný formát hodnot řady. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Vrací nebo nastavuje číselný formát hodnot x řady. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Vrací nebo nastavuje číselný formát hodnot x řady. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Vrací nebo nastavuje číselný formát hodnot y řady. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Vrací nebo nastavuje číselný formát hodnot y řady. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Vrací nebo nastavuje číselný formát velikostí bublin řady. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Vrací nebo nastavuje číselný formát velikostí bublin řady. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Určuje, že sloupcová, sloupcová nebo bublinová řada invertuje barvy, pokud je hodnota záporná. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Určuje, že sloupcová, sloupcová nebo bublinová řada invertuje barvy, pokud je hodnota záporná. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Určuje invertování plné barvy řady. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Reprezentuje položku legendy související s touto řadou Jen pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Vrací automatickou barvu řady na základě indexu řady a stylu grafu. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Reprezentuje vnitřní body. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Reprezentuje vnitřní body. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Reprezentuje odlehlé body. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Reprezentuje odlehlé body. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Reprezentuje značky průměru. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Reprezentuje značky průměru. |
| [getShowMeanLine()](#getShowMeanLine--) | Reprezentuje značky průměru. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Reprezentuje značky průměru. |
| [getQuartileMethod()](#getQuartileMethod--) | Reprezentuje kvartilovou metodu. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Reprezentuje kvartilovou metodu. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Reprezentuje čáry spojnice. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Reprezentuje čáry spojnice. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Reprezentuje rozložení štítků nadřazených kategorií. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Reprezentuje rozložení štítků nadřazených kategorií. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). |
| [hasUpDownBars()](#hasUpDownBars--) | Určuje, zda má čárový nebo akciový graf svislé pruhy. |
| [getGapWidth()](#getGapWidth--) | Určuje prostor mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. |
| [getGapDepth()](#getGapDepth--) | Vrací nebo nastavuje vzdálenost, jako procento šířky značky, mezi datovými řadami ve 3D grafu. |
| [isColorVaried()](#isColorVaried--) | Určuje, že každá datová značka v řadě má jinou barvu. |
| [hasSeriesLines()](#hasSeriesLines--) | Určuje, zda existují čáry řad pro tuto řadu a související řady. |
| [getOverlap()](#getOverlap--) | Určuje, jak moc se sloupce a pruhy překrývají v 2D grafech, jako procento (od -100 % do 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Určuje velikost druhého výseku nebo sloupce v grafu koláč-v-koláči nebo sloupec-v-koláči jako procento velikosti prvního výseku (může být mezi 5 a 200 procenty). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Určuje hodnotu, která bude použita k určení, které datové body jsou ve druhém výseku nebo sloupci v grafu koláč-v-koláči nebo sloupec-v-koláči. |
| [getPieSplitBy()](#getPieSplitBy--) | Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v grafu koláč-v-koláči nebo sloupec-v-koláči. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Určuje velikost díry v prstencovém grafu (může být mezi 10 a 90 procenty velikosti vykreslovací oblasti). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Určuje úhel prvního výseku koláčového nebo prstencového grafu ve stupních (po směru hodinových ručiček od shora, od 0 do 360 stupňů). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Informace o vlastním rozdělení pro graf koláč-v-koláči nebo sloupec-v-koláči s vlastním rozdělením. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena v procentech průměru koláče. Čtení/Zápis int.

**Vrací:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena v procentech průměru koláče. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Reprezentuje vyhlazování křivky. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Čtení/Zápis boolean.

**Vrací:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Reprezentuje vyhlazování křivky. True if curve smoothing is turned on for the line chart or scatter chart. Applies only to line and scatter connected by lines charts. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Vrací značku řady. Jen pro čtení [IMarker](../../com.aspose.slides/imarker).

**Vrací:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Určuje tvar řady ve 3D sloupcovém grafu. Changing of value of this property can cause to automatically changing Type of series. Čtení/Zápis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Vrací:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Určuje tvar řady ve 3D sloupcovém grafu. Changing of value of this property can cause to automatically changing Type of series. Čtení/Zápis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Vrací název řady. Jen pro čtení [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Vrací:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Vrací kolekci datových bodů této řady. Jen pro čtení [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Vrací:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

Vrací typ této řady. Čtení/Zápis [ChartType](../../com.aspose.slides/charttype).

**Vrací:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Vrací typ této řady. Čtení/Zápis [ChartType](../../com.aspose.slides/charttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Vrací nadřazenou skupinu řad. Jen pro čtení [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Vrací:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Vrací formát řady. Jen pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Vrací pořadí řady. Čtení/Zápis int.

**Vrací:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Vrací pořadí řady. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Vrací popisky řady. Jen pro čtení [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Vrací:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Kolekce trendových čar řady Jen pro čtení [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Vrací:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Reprezentuje chybové úsečky řady s orientací X. Jen pro čtení [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Vrací:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Reprezentuje chybové úsečky řady s orientací Y. Jen pro čtení [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**Vrací:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indikuje, zda je tato řada vykreslena na druhé ose hodnot. Čtení/Zápis boolean.

**Vrací:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Indikuje, zda je tato řada vykreslena na druhé ose hodnot. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Vrací nebo nastavuje číselný formát hodnot řady. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Vrací nebo nastavuje číselný formát hodnot řady. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Vrací nebo nastavuje číselný formát hodnot x řady. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Vrací nebo nastavuje číselný formát hodnot x řady. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Vrací nebo nastavuje číselný formát hodnot y řady. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Vrací nebo nastavuje číselný formát hodnot y řady. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Vrací nebo nastavuje číselný formát velikostí bublin řady. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Vrací nebo nastavuje číselný formát velikostí bublin řady. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Určuje, že sloupcová, sloupcová nebo bublinová řada invertuje barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Vrací:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Určuje, že sloupcová, sloupcová nebo bublinová řada invertuje barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Určuje invertování plné barvy řady. To apply color setting set series format FillType to FillType.Solid. Čtení/Zápis [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Reprezentuje položku legendy související s touto řadou Jen pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Vrací automatickou barvu řady na základě indexu řady a stylu grafu. Tato barva se používá ve výchozím nastavení, pokud FillType je roven NotDefined.

**Vrací:**
java.awt.Color - Automatická barva řady java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Zastupuje vnitřní body. True, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Zastupuje vnitřní body. True, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Zastupuje odlehlé body. True, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Zastupuje odlehlé body. True, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Zastupuje středové značky. True, pokud jsou středové značky zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Zastupuje středové značky. True, pokud jsou středové značky zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Zastupuje středovou linii. True, pokud je středová linie zobrazena v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Zastupuje středovou linii. True, pokud je středová linie zobrazena v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Zastupuje metodu kvartilu. Použitelné pouze pro grafy BoxAndWhisker.

**Vrací:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Zastupuje metodu kvartilu. Použitelné pouze pro grafy BoxAndWhisker.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Zastupuje spojovací čáry. Použitelné pouze pro grafy Waterfall.

**Vrací:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Zastupuje spojovací čáry. Použitelné pouze pro grafy Waterfall.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Zastupuje rozložení popisků nadřazených kategorií. Použitelné pouze pro grafy Treemap.

**Vrací:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Zastupuje rozložení popisků nadřazených kategorií. Použitelné pouze pro grafy Treemap.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Určuje faktor měřítka pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.BubbleSizeScale s možností čtení/zápisu.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.BubbleSizeScale.

**Vrací:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Určuje, zda má Line- nebo Stock-graf svislé pruhy nahoru/dolů. Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.UpDownBars.HasUpDownBars s možností čtení/zápisu. Pro formátování svislých pruhů použijte vlastnost ParentSeriesGroup.UpDownBars. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Vrací:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Určuje mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.GapWidth s možností čtení/zápisu. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.GapWidth.

**Vrací:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Vrací nebo nastavuje vzdálenost, jako procento šířky značky, mezi datovými řadami ve 3D grafu. Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.GapDepth s možností čtení/zápisu. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.GapDepth.

**Vrací:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Určuje, že každý datový marker v řadě má jinou barvu. Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.IsColorVaried s možností čtení/zápisu. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.IsColorVaried.

**Vrací:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Určuje, zda existují řádkové čáry pro tuto řadu a související řady. Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.HasSeriesLines s možností čtení/zápisu. Pro formátování řádkových čar použijte vlastnost ParentSeriesGroup.SeriesLinesFormat. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.HasSeriesLines.

**Vrací:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Určuje, jak moc se sloupce a pruhy překrývají v 2-D grafech, jako procento (od –100 % do 100 %). Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad. Je to projekce příslušné vlastnosti v nadřazené skupině řad, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.Overlap s možností čtení/zápisu. Pouze pro čtení byte.

--------------------

Overlap určuje míru překrytí nebo mezeru mezi sloupci a pruhy jako procento jejich šířky:
- –100 %: Maximální mezera (sloupce jsou zcela oddělené).
- 0 %: Sloupce jsou umístěny vedle sebe bez překrytí nebo mezery.
- 100 %: Maximální překrytí (sloupce se zcela překrývají).

Jedná se o projekci vlastnosti ParentSeriesGroup.Overlap.

**Vrací:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Určuje velikost druhého výseku nebo sloupce v grafu „pie-of-pie“ či „bar-of-pie“ jako procento velikosti prvního výseku (může být mezi 5 a 200 %). Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.SecondPieSize s možností čtení/zápisu. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.SecondPieSize.

**Vrací:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Určuje hodnotu, která se má použít k určení, které datové body jsou ve druhém výseku nebo sloupci v grafu „pie-of-pie“ či „bar-of-pie“. Používá se společně s vlastností PieSplitBy. Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.PieSplitPosition s možností čtení/zápisu. Pouze pro čtení double.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitPosition.

**Vrací:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v grafu „pie-of-pie“ či „bar-of-pie“. Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.PieSplitBy s možností čtení/zápisu. Pouze pro čtení [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitBy. 2) Pokud je hodnota vlastnosti PieSplitType.Custom, můžete definovat vlastní rozdělení pomocí vlastnosti ParentSeriesGroup.PieSplitCustomPoints.

**Vrací:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Určuje velikost díry v prstencovém grafu (může být mezi 10 a 90 % velikosti vykreslovací oblasti). Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.DoughnutHoleSize s možností čtení/zápisu. Pouze pro čtení byte.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.DoughnutHoleSize.

**Vrací:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Určuje úhel prvního výseku v prstencovém nebo koláčovém grafu v stupních (ve směru hodinových ručiček od vrchu, od 0 do 360 °). Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je proto pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.FirstSliceAngle s možností čtení/zápisu. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.FirstSliceAngle.

**Vrací:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Vlastní informace o rozdělení pro graf „pie-of-pie“ nebo „bar-of-pie“ s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém výseku nebo sloupci. Jedná se o vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jde o projekci příslušné skupinové vlastnosti. Pouze pro čtení [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitCustomPoints.

**Vrací:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bublinovém grafu. Jedná se o vlastnost nejen této řady, ale všech řad ze skupiny nadřazených řad - jedná se o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost jen pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.BubbleSizeRepresentation s možností čtení/zápisu pro změnu hodnoty.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.BubbleSizeRepresentation.

**Vrací:**
int