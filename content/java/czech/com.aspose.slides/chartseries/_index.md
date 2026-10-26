---
title: ChartSeries
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje sérii grafu.
type: docs
url: /cs/com.aspose.slides/chartseries/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Představuje sérii grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [getExplosion()](#getExplosion--) | Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena jako procento průměru koláče. |
| [setExplosion(int value)](#setExplosion-int-) | Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena jako procento průměru koláče. |
| [getSmooth()](#getSmooth--) | Zastupuje vyhlazování křivky. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Zastupuje vyhlazování křivky. |
| [getName()](#getName--) | Vrací název série. |
| [getDataPoints()](#getDataPoints--) | Vrací kolekci datových bodů této série. |
| [getType()](#getType--) | Vrací typ této série. |
| [setType(int value)](#setType-int-) | Vrací typ této série. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indikuje, zda je tato série vykreslena na sekundární ose. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indikuje, zda je tato série vykreslena na sekundární ose. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Vrací formát série. |
| [getOrder()](#getOrder--) | Vrací pořadí série. |
| [setOrder(int value)](#setOrder-int-) | Vrací pořadí série. |
| [getLabels()](#getLabels--) | Vrací popisky série. |
| [getTrendLines()](#getTrendLines--) | Kolekce trendových čar série. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Zastupuje ErrorBars série se směrem X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Zastupuje ErrorBars série se směrem Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Zastupuje položku legendy související s touto sérií Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Určuje tvar série 3D sloupcového grafu. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Určuje tvar série 3D sloupcového grafu. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Určuje, že série sloupců, sloupců nebo bublin má invertovat své barvy, pokud je hodnota záporná. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Určuje, že série sloupců, sloupců nebo bublin má invertovat své barvy, pokud je hodnota záporná. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Určuje invertovanou plnou barvu pro sérii. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Vrací automatickou barvu série na základě indexu série a stylu grafu. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Zastupuje vnitřní body. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Zastupuje vnitřní body. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Zastupuje odlehlé body. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Zastupuje odlehlé body. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Zastupuje značky průměru. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Zastupuje značky průměru. |
| [getShowMeanLine()](#getShowMeanLine--) | Zastupuje čáru průměru. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Zastupuje čáru průměru. |
| [getQuartileMethod()](#getQuartileMethod--) | Zastupuje metodu kvartilu. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Zastupuje metodu kvartilu. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Zastupuje spojovací čáry. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Zastupuje spojovací čáry. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Zastupuje rozvržení popisků nadřazené kategorie. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Zastupuje rozvržení popisků nadřazené kategorie. |
| [hasUpDownBars()](#hasUpDownBars--) | Určuje, zda má čárový nebo akciový graf sloupce nahoru/dolů. |
| [getGapWidth()](#getGapWidth--) | Určuje prostor mezi shluky sloupců nebo sloupců jako procento šířky sloupce. |
| [getGapDepth()](#getGapDepth--) | Vrací nebo nastavuje vzdálenost, jako procento šířky značky, mezi datovými sériemi ve 3D grafu. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Určuje úhel prvního výseku koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Určuje velikost otvoru v prstencovém grafu (může být mezi 10 a 90 procenty velikosti vykreslovací oblasti). |
| [getOverlap()](#getOverlap--) | Určuje, jak moc se sloupce a sloupy překrývají ve 2D grafech, jako procento (od -100 % do 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Určuje velikost druhého výseku nebo sloupce v grafu koláč-v-koláči nebo sloupec-v-koláči, jako procento velikosti prvního výseku (může být mezi 5 a 200 procenty). |
| [hasSeriesLines()](#hasSeriesLines--) | Určuje, zda existují řádky série pro tuto sérii a související série. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bublinovém grafu. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Určuje hodnotu, která bude použita k určení, které datové body jsou ve druhém výseku nebo sloupci v grafu koláč-v-koláči nebo sloupec-v-koláči. |
| [getPieSplitBy()](#getPieSplitBy--) | Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v grafu koláč-v-koláči nebo sloupec-v-koláči. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Vlastní informace o rozdělení pro graf koláč-v-koláči nebo sloupec-v-koláči s vlastním rozdělením. |
| [isColorVaried()](#isColorVaried--) | Určuje, že každý datový marker v sérii má jinou barvu. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Určuje faktor měřítka pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci FillFormat. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací nadřazený graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena jako procento průměru koláče. Čtení/Zápis int.

**Vrací:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena jako procento průměru koláče. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Zastupuje vyhlazování křivky. True pokud je vyhlazování křivky zapnuto pro čárový graf nebo bodový graf. Používá se pouze pro čárové a bodové grafy spojené čárami. Čtení/Zápis boolean.

**Vrací:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Zastupuje vyhlazování křivky. True pokud je vyhlazování křivky zapnuto pro čárový graf nebo bodový graf. Používá se pouze pro čárové a bodové grafy spojené čárami. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Vrací název série. Pouze pro čtení [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Vrací:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Vrací kolekci datových bodů této série. Pouze pro čtení [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Vrací:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

Vrací typ této série. Čtení/Zápis [ChartType](../../com.aspose.slides/charttype).

**Vrací:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Vrací typ této série. Čtení/Zápis [ChartType](../../com.aspose.slides/charttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indikuje, zda je tato série vykreslena na sekundární ose. Čtení/Zápis boolean.

**Vrací:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Indikuje, zda je tato série vykreslena na sekundární ose. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Pouze pro čtení [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Vrací:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Vrací formát série. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

Vrací pořadí série. Čtení/Zápis int.

**Vrací:**
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Vrací pořadí série. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Vrací popisky série. Pouze pro čtení [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Vrací:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Kolekce trendových čar série. Pouze pro čtení [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines jsou k dispozici (nejsou null) pro datové série ve vrstvených 2-D oblastech, sloupcových, sloupcových, čárových, akciových, xy (scatter) a bublinových grafech. Trendline není k dispozici pro datové série v jakémkoli typu grafu, který je vrstvený nebo 3-D. Trendlines nejsou také k dispozici pro radar, koláč, povrchové ani prstencové grafy.

**Vrací:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Zastupuje ErrorBars série se směrem X. Pouze pro čtení [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars se směrem X jsou dostupné pro série typu oblast, sloupec, scatter a bublina. Pro jakékoli jiné typy grafu tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Vrací:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Zastupuje ErrorBars série se směrem Y. Pouze pro čtení [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars se směrem Y jsou dostupné pro serie typu oblast, sloupec, čára, scatter a bublina. Pro jakékoli jiné typy grafu tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Vrací:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Zastupuje položku legendy související s touto sérií Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getMarker() {#getMarker--}
```java
public final IMarker getMarker()
```

Marker. Pouze pro čtení [IMarker](../../com.aspose.slides/imarker).

**Vrací:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Určuje tvar série 3D sloupcového grafu. Změna hodnoty této vlastnosti může způsobit automatickou změnu typu série. Čtení/Zápis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Vrací:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Určuje tvar série 3D sloupcového grafu. Změna hodnoty této vlastnosti může způsobit automatickou změnu typu série. Čtení/Zápis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Určuje, že série sloupců, sloupců nebo bublin má invertovat své barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Vrací:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Určuje, že série sloupců, sloupců nebo bublin má invertovat své barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Specifikuje invertovanou plnou barvu pro sérii. Pro aplikaci nastavení barvy nastavte formát série FillType na FillType.Solid. Čtení/zápis [ColorFormat](../../com.aspose.slides/colorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```


Vrací automatickou barvu série na základě indexu série a stylu grafu. Tato barva se použije jako výchozí, pokud je FillType roven NotDefined.

**Vrací:**
java.awt.Color - Objekt java.awt.Color.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```


Zastupuje vnitřní body. True, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```


Zastupuje vnitřní body. True, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```


Zastupuje odlehlé body. True, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```


Zastupuje odlehlé body. True, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```


Zastupuje značky průměru. True, pokud jsou značky průměru zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```


Zastupuje značky průměru. True, pokud jsou značky průměru zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```


Zastupuje čáru průměru. True, pokud je čára průměru zobrazena v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```


Zastupuje čáru průměru. True, pokud je čára průměru zobrazena v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```


Zastupuje metodu kvartilu. Použitelné pouze pro grafy BoxAndWhisker.

**Vrací:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```


Zastupuje metodu kvartilu. Použitelné pouze pro grafy BoxAndWhisker.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```


Zastupuje spojovací čáry. Použitelné pouze pro grafy Waterfall.

**Vrací:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```


Zastupuje spojovací čáry. Použitelné pouze pro grafy Waterfall.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```


Zastupuje rozložení štítků nadřazených kategorií. Použitelné pouze pro grafy Treemap.

**Vrací:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```


Zastupuje rozložení štítků nadřazených kategorií. Použitelné pouze pro grafy Treemap.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```


Určuje, zda má graf Line nebo Stock pruhy nahoru/dolů. Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – jde o projekci příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.UpDownBars.HasUpDownBars s možností čtení a zápisu pro změnu hodnoty. Použijte vlastnost ParentSeriesGroup.UpDownBars pro formátování pruhů nahoru/dolů. Pouze pro čtení boolean.

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Vrací:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```


Určuje prostor mezi shluky sloupců nebo pruhů jako procento šířky sloupce či pruhu. Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.GapWidth s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení int.

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.GapWidth.

**Vrací:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```


Vrací nebo nastavuje vzdálenost jako procento šířky značky mezi datovými sériemi ve 3D grafu. Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.GapDepth s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení int.

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.GapDepth.

**Vrací:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```


Určuje úhel první výseče koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.FirstSliceAngle s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení int.

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.FirstSliceAngle.

**Vrací:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```


Určuje velikost díry v prstencovém grafu (může být mezi 10 a 90 procenty velikosti oblasti vykreslování). Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.DoughnutHoleSize s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení byte.

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.DoughnutHoleSize.

**Vrací:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```


Určuje, jak moc se sloupce a pruhy překrývají v 2-D grafech, jako procento (od –100 % do 100 %). Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií. Je to projekce příslušné vlastnosti v nadřazené skupině sérií a tak je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.Overlap s možností čtení a zápisu. Pouze pro čtení byte.

--------------------

Overlap specifikuje míru překrytí nebo mezery mezi sloupci a pruhy jako procento jejich šířky: –100 %: maximální mezera (sloupce jsou zcela oddělené). 0 %: sloupce jsou umístěny vedle sebe bez překrytí nebo mezery. 100 %: maximální překrytí (sloupce se zcela překrývají). Toto je projekce vlastnosti ParentSeriesGroup.Overlap.

**Vrací:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```


Určuje velikost druhé výseče nebo pruhu v grafu „pie-of-pie“ nebo „bar-of-pie“ jako procento velikosti první výseče (může být mezi 5 a 200 procenty). Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.SecondPieSize s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení int.

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.SecondPieSize.

**Vrací:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```


Určuje, zda existují čáry sérií pro tuto sérii a související série. Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.HasSeriesLines s možností čtení a zápisu pro změnu hodnoty. Použijte vlastnost ParentSeriesGroup.SeriesLinesFormat pro formátování čar sérií. Pouze pro čtení boolean.

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.HasSeriesLines.

**Vrací:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```


Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.BubbleSizeRepresentation s možností čtení a zápisu pro změnu hodnoty.

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.BubbleSizeRepresentation.

**Vrací:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```


Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu „pie-of-pie“ či „bar-of-pie“. Používá se spolu s vlastností PieSplitBy. Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.PieSplitPosition s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení double.

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.PieSplitPosition.

**Vrací:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```


Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu „pie-of-pie“ či „bar-of-pie“. Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.PieSplitBy s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Toto je projekce vlastnosti ParentSeriesGroup.PieSplitBy. 2) Pokud je hodnota vlastnosti PieSplitType.Custom, můžete definovat vlastní rozdělení pomocí vlastnosti ParentSeriesGroup.PieSplitCustomPoints.

**Vrací:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


Vlastní informace o rozdělení pro graf „pie-of-pie“ nebo „bar-of-pie“ s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém koláči nebo pruhu v grafu „pie-of-pie“ či „bar-of-pie“. Jedná se o vlastnost nejen této série, ale všech sérií nadřazené skupiny sérií – projekce příslušné skupinové vlastnosti Pouze pro čtení [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Toto je projekce vlastnosti ParentSeriesGroup.PieSplitCustomPoints.

**Vrací:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Určuje, že každý datový značník v řadě má jinou barvu. Toto je vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jedná se o projekci odpovídající vlastnosti skupiny. Tato vlastnost je tedy jen pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.IsColorVaried pro čtení/zápis pro změnu hodnoty. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.IsColorVaried.

**Vrací:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Toto je vlastnost nejen této řady, ale všech řad v nadřazené skupině řad – jedná se o projekci odpovídající vlastnosti skupiny. Tato vlastnost je tedy jen pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.BubbleSizeScale pro čtení/zápis pro změnu hodnoty.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.BubbleSizeScale.

**Vrací:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek objektu FillFormat. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci objektu FillFormat. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)