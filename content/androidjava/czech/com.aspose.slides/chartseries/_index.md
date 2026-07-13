---
title: ChartSeries
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje sérii grafu.
type: docs
url: /cs/com.aspose.slides/chartseries/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Reprezentuje sérii grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [getExplosion()](#getExplosion--) | Vzdálenost otevřeného výseku koláčového diagramu od středu koláčového diagramu je vyjádřena v procentech průměru koláče. |
| [setExplosion(int value)](#setExplosion-int-) | Vzdálenost otevřeného výseku koláčového diagramu od středu koláčového diagramu je vyjádřena v procentech průměru koláče. |
| [getSmooth()](#getSmooth--) | Zastupuje vyhlazování křivky. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Zastupuje vyhlazování křivky. |
| [getName()](#getName--) | Vrací název série. |
| [getDataPoints()](#getDataPoints--) | Vrací kolekci datových bodů této série. |
| [getType()](#getType--) | Vrací typ této série. |
| [setType(int value)](#setType-int-) | Vrací typ této série. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Určuje, zda je tato série vykreslena na sekundární ose. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Určuje, zda je tato série vykreslena na sekundární ose. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Vrací formát série. |
| [getOrder()](#getOrder--) | Vrací pořadí série. |
| [setOrder(int value)](#setOrder-int-) | Vrací pořadí série. |
| [getLabels()](#getLabels--) | Vrací štítky série. |
| [getTrendLines()](#getTrendLines--) | Kolekce trendových čar série. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Zastupuje chybové pruhy série v směru X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Zastupuje chybové pruhy série v směru Y. |
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
| [getBar3DShape()](#getBar3DShape--) | Určuje tvar série ve 3D sloupcovém diagramu. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Určuje tvar série ve 3D sloupcovém diagramu. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Určuje, že sloupcová, sloupcová nebo bublinová série má invertovat barvy, pokud je hodnota záporná. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Určuje, že sloupcová, sloupcová nebo bublinová série má invertovat barvy, pokud je hodnota záporná. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Určuje invertovanou plnou barvu pro sérii. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Vrací automatickou barvu série na základě indexu série a stylu grafu. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Zastupuje vnitřní body. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Zastupuje vnitřní body. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Zastupuje odlehlé body. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Zastupuje odlehlé body. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Zastupuje středové značky. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Zastupuje středové značky. |
| [getShowMeanLine()](#getShowMeanLine--) | Zastupuje středovou čáru. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Zastupuje středovou čáru. |
| [getQuartileMethod()](#getQuartileMethod--) | Zastupuje kvantilovou metodu. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Zastupuje kvantilovou metodu. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Zastupuje spojovací čáry. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Zastupuje spojovací čáry. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Zastupuje rozložení štítků nadřazené kategorie. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Zastupuje rozložení štítků nadřazené kategorie. |
| [hasUpDownBars()](#hasUpDownBars--) | Určuje, zda má čárový nebo akciový graf sloupce nahoru/dolů. |
| [getGapWidth()](#getGapWidth--) | Určuje prostor mezi shluky sloupců či pruhů jako procento šířky sloupce či pruhu. |
| [getGapDepth()](#getGapDepth--) | Vrací nebo nastavuje vzdálenost, vyjádřenou v procentech šířky značky, mezi datovými sériemi ve 3D diagramu. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Určuje úhel prvního výseku koláčového nebo prstencového diagramu ve stupních (ve směru hodinových ručiček od horní polohy, od 0 do 360°). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Určuje velikost otvoru v prstencovém diagramu (může být mezi 10 a 90 % velikosti vykreslené oblasti). |
| [getOverlap()](#getOverlap--) | Určuje, jak moc se sloupce a pruhy překrývají v 2D diagramech, jako procento (od -100 % do 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Určuje velikost druhého výseku nebo sloupce v diagramu koláč-dvojice nebo sloupec-dvojice jako procento velikosti prvního výseku (může být mezi 5 a 200 %). |
| [hasSeriesLines()](#hasSeriesLines--) | Určuje, zda existují řádky série pro tuto sérii a související série. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Určuje, jak jsou hodnoty velikosti bublin zobrazovány v bublinovém diagramu. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém výseku nebo sloupci v diagramu koláč-dvojice nebo sloupec-dvojice. |
| [getPieSplitBy()](#getPieSplitBy--) | Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v diagramu koláč-dvojice nebo sloupec-dvojice. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Vlastní informace o rozdělení pro diagram koláč-dvojice nebo sloupec-dvojice s vlastním rozdělením. |
| [isColorVaried()](#isColorVaried--) | Určuje, že každý datový marker v sérii má jinou barvu. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Určuje měřítkový faktor pro bublinový diagram (může být mezi 0 a 300 % výchozí velikosti). |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |

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

Vzdálenost otevřeného výseku koláčového diagramu od středu koláčového diagramu je vyjádřena v procentech průměru koláče. Čtení/Zápis int.

**Vrací:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Vzdálenost otevřeného výseku koláčového diagramu od středu koláčového diagramu je vyjádřena v procentech průměru koláče. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Zastupuje vyhlazování křivky. Pravda, pokud je vyhlazování křivky zapnuté pro čárový nebo rozptylový graf. Použitelné pouze pro čárové a rozptylové grafy spojené čarami. Čtení/Zápis boolean.

**Vrací:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Zastupuje vyhlazování křivky. Pravda, pokud je vyhlazování křivky zapnuté pro čárový nebo rozptylový graf. Použitelné pouze pro čárové a rozptylové grafy spojené čarami. Čtení/Zápis boolean.

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

Určuje, zda je tato série vykreslena na sekundární ose. Čtení/Zápis boolean.

**Vrací:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Určuje, zda je tato série vykreslena na sekundární ose. Čtení/Zápis boolean.

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

Vrací štítky série. Pouze pro čtení [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Vrací:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Kolekce trendových čar série. Pouze pro čtení [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines jsou dostupné (nejsou null) pro datové série v neuspořádaných 2-D plošných, sloupcových, sloupcových, čárových, akciových, xy (rozptylových) a bublinových grafech. Trendová čára není dostupná pro datové série v jakémkoli typu grafu, který je uspořádaný (stacked) nebo 3-D. TrendLines také nejsou dostupné pro radarové, koláčové, povrchové ani prstencové grafy.

**Vrací:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Zastupuje chybové pruhy série v směru X. Pouze pro čtení [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars s X-směrem jsou dostupné pro série typu area, bar, scatter a bubble. Pro ostatní typy grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Vrací:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Zastupuje chybové pruhy série v směru Y. Pouze pro čtení [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars s Y-směrem jsou dostupné pro série typu area, bar, line, scatter a bubble. Pro ostatní typy grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

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
```
public final IMarker getMarker()
```

Marker. Pouze pro čtení [IMarker](../../com.aspose.slides/imarker).

**Vrací:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Určuje tvar série ve 3D sloupcovém diagramu. Změna hodnoty této vlastnosti může automaticky změnit typ série. Čtení/Zápis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Vrací:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Určuje tvar série ve 3D sloupcovém diagramu. Změna hodnoty této vlastnosti může automaticky změnit typ série. Čtení/Zápis [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Určuje, že sloupcová, sloupcová nebo bublinová série má invertovat barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Vrací:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Určuje, že sloupcová, sloupcová nebo bublinová série má invertovat barvy, pokud je hodnota záporná. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Určuje invertovanou plnou barvu pro sérii. Pro použití nastavení barvy nastavte FillType formátu série na FillType.Solid. Čtení/Zápis [ColorFormat](../../com.aspose.slides/colorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Vrací automatickou barvu série na základě indexu série a stylu grafu. Tato barva se použije jako výchozí, pokud FillType je NotDefined.

**Vrací:**
java.lang.Integer - Objekt java.lang.Integer.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Zastupuje vnitřní body. Pravda, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro BoxAndWhisker grafy. Čtení/Zápis boolean.

**Vrací:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Zastupuje vnitřní body. Pravda, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro BoxAndWhisker grafy. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Zastupuje odlehlé body. Pravda, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro BoxAndWhisker grafy. Čtení/Zápis boolean.

**Vrací:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Zastupuje odlehlé body. Pravda, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro BoxAndWhisker grafy. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Zastupuje středové značky. Pravda, pokud jsou středové značky zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro BoxAndWhisker grafy. Čtení/Zápis boolean.

**Vrací:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Zastupuje středové značky. Pravda, pokud jsou středové značky zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro BoxAndWhisker grafy. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Zastupuje středovou čáru. Pravda, pokud je středová čára zobrazena v grafu BoxAndWhisker. Použitelné pouze pro BoxAndWhisker grafy. Čtení/Zápis boolean.

**Vrací:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Zastupuje středovou čáru. Pravda, pokud je středová čára zobrazena v grafu BoxAndWhisker. Použitelné pouze pro BoxAndWhisker grafy. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Zastupuje kvantilovou metodu. Použitelné pouze pro BoxAndWhisker grafy.

**Vrací:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Zastupuje kvantilovou metodu. Použitelné pouze pro BoxAndWhisker grafy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Zastupuje spojovací čáry. Použitelné pouze pro Waterfall grafy.

**Vrací:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Zastupuje spojovací čáry. Použitelné pouze pro Waterfall grafy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public     [  ---  ---  --- --- ---  
```

Zastupuje rozložení štítků nadřazené kategorie. Použitelné pouze pro Treemap grafy.

**Vrací:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Zastupuje rozložení štítků nadřazené kategorie. Použitelné pouze pro Treemap grafy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Určuje, zda má čárový nebo akciový graf sloupce nahoru/dolů. Toto není pouze vlastnost této série, ale všech sérií v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup ke skupině sérií. Pro změnu hodnoty použijte ParentSeriesGroup.UpDownBars.HasUpDownBars. Pro formátování použijte ParentSeriesGroup.UpDownBars. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Vrací:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Určuje prostor mezi shluky sloupců či pruhů jako procento šířky sloupce či pruhu. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.GapWidth. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.GapWidth.

**Vrací:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Vrací nebo nastavuje vzdálenost, vyjádřenou v procentech šířky značky, mezi datovými sériemi ve 3D diagramu. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.GapDepth. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.GapDepth.

**Vrací:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Určuje úhel prvního výseku koláčového nebo prstencového diagramu ve stupních (ve směru hodinových ručiček od horní polohy, od 0 do 360°). Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.FirstSliceAngle. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.FirstSliceAngle.

**Vrací:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Určuje velikost otvoru v prstencovém diagramu (může být mezi 10 a 90 % velikosti vykreslené oblasti). Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.DoughnutHoleSize. Pouze pro čtení byte.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.DoughnutHoleSize.

**Vrací:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Určuje, jak moc se sloupce a pruhy překrývají v 2-D diagramech, jako procento (od -100 % do 100 %). Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině. Jedná se o projekci příslušné vlastnosti ve skupině, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte ParentSeriesGroup.Overlap. Pouze pro čtení byte.

--------------------

Overlap specifikuje míru překrytí nebo mezery mezi sloupci a pruhy jako procento jejich šířky:
- -100 %: Maximální mezera (sloupce jsou zcela oddělené).
- 0 %: Sloupce jsou vedle sebe bez překrytí i mezery.
- 100 %: Maximální překrytí (sloupce se úplně překrývají).

Jedná se o projekci vlastnosti ParentSeriesGroup.Overlap.

**Vrací:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Určuje velikost druhého výseku nebo sloupce v diagramu koláč-dvojice nebo sloupec-dvojice jako procento velikosti prvního výseku (může být mezi 5 a 200 %). Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.SecondPieSize. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.SecondPieSize.

**Vrací:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Určuje, zda existují řádky série pro tuto sérii a související série. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.HasSeriesLines. Pro formátování použijte ParentSeriesGroup.SeriesLinesFormat. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.HasSeriesLines.

**Vrací:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Určuje, jak jsou hodnoty velikosti bublin zobrazovány v bublinovém diagramu. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.BubbleSizeRepresentation.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.BubbleSizeRepresentation.

**Vrací:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém výseku nebo sloupci v diagramu koláč-dvojice nebo sloupec-dvojice. Používá se spolu s vlastností PieSplitBy. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.PieSplitPosition. Pouze pro čtení double.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitPosition.

**Vrací:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v diagramu koláč-dvojice nebo sloupec-dvojice. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.PieSplitBy. Pouze pro čtení [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitBy. 2) Pokud je hodnota vlastnosti PieSplitType.Custom, můžete definovat vlastní informace o rozdělení pomocí vlastnosti ParentSeriesGroup.PieSplitCustomPoints.

**Vrací:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Vlastní informace o rozdělení pro diagram koláč-dvojice nebo sloupec-dvojice s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém výseku nebo sloupci. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti Pouze pro čtení [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitCustomPoints.

**Vrací:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Určuje, že každý datový marker v sérii má jinou barvu. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.IsColorVaried. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.IsColorVaried.

**Vrací:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Určuje měřítkový faktor pro bublinový diagram (může být mezi 0 a 300 % výchozí velikosti). Tato vlastnost není jen pro tuto sérii, ale pro všechny série v rodičovské skupině – je to projekce příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Pro přístup ke skupině použijte ParentSeriesGroup. Pro změnu hodnoty použijte ParentSeriesGroup.BubbleSizeScale.

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