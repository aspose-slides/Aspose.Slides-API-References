---
title: IChartSeries
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje řadu grafu.
type: docs
url: /cs/com.aspose.slides/ichartseries/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Represents a chart series.
## Metody

| Metoda | Popis |
| --- | --- |
| [getExplosion()](#getExplosion--) | Vzdálenost otevřeného výseku koláče od středu koláčového diagramu je vyjádřena v procentech průměru koláče. |
| [setExplosion(int value)](#setExplosion-int-) | Vzdálenost otevřeného výseku koláče od středu koláčového diagramu je vyjádřena v procentech průměru koláče. |
| [getSmooth()](#getSmooth--) | Reprezentuje vyhlazování křivky. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Reprezentuje vyhlazování křivky. |
| [getMarker()](#getMarker--) | Vrací značku řady. |
| [getBar3DShape()](#getBar3DShape--) | Určuje tvar řady 3-D sloupcového diagramu. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Určuje tvar řady 3-D sloupcového diagramu. |
| [getName()](#getName--) | Vrací název řady. |
| [getDataPoints()](#getDataPoints--) | Vrací kolekci datových bodů této řady. |
| [getType()](#getType--) | Vrací typ této řady. |
| [setType(int value)](#setType-int-) | Vrací typ této řady. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Vrací skupinu nadřazených řad. |
| [getFormat()](#getFormat--) | Vrací formát řady. |
| [getOrder()](#getOrder--) | Vrací pořadí řady. |
| [setOrder(int value)](#setOrder-int-) | Vrací pořadí řady. |
| [getLabels()](#getLabels--) | Vrací Labels řady. |
| [getTrendLines()](#getTrendLines--) | Kolekce trendových čar řady Pouze pro čtení [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Reprezentuje ErrorBars řady s orientací X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Reprezentuje ErrorBars řady s orientací Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Určuje, zda je tato řada vykreslena na druhé hodnotové ose. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Určuje, zda je tato řada vykreslena na druhé hodnotové ose. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Vrací nebo nastavuje formát čísel pro hodnoty řady. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Vrací nebo nastavuje formát čísel pro hodnoty řady. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Vrací nebo nastavuje formát čísel pro x-hodnoty řady. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Vrací nebo nastavuje formát čísel pro x-hodnoty řady. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Vrací nebo nastavuje formát čísel pro y-hodnoty řady. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Vrací nebo nastavuje formát čísel pro y-hodnoty řady. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Vrací nebo nastavuje formát čísel pro velikosti bublin řady. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Vrací nebo nastavuje formát čísel pro velikosti bublin řady. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Určuje, že sloupcová, sloupcová nebo bublinová řada má invertovat barvy, pokud je hodnota záporná. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Určuje, že sloupcová, sloupcová nebo bublinová řada má invertovat barvy, pokud je hodnota záporná. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Určuje invertování plné barvy řady. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Reprezentuje legendární položku související s touto řadou Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Vrací automatickou barvu řady na základě indexu řady a stylu diagramu. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Reprezentuje vnitřní body. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Reprezentuje vnitřní body. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Reprezentuje odlehlé body. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Reprezentuje odlehlé body. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Reprezentuje průměrné značky. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Reprezentuje průměrné značky. |
| [getShowMeanLine()](#getShowMeanLine--) | Reprezentuje průměrné značky. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Reprezentuje průměrné značky. |
| [getQuartileMethod()](#getQuartileMethod--) | Reprezentuje metodu kvartilu. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Reprezentuje metodu kvartilu. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Reprezentuje spojovací čáry. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Reprezentuje spojovací čáry. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Reprezentuje rozložení nadřazených popisků kategorií. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Reprezentuje rozložení nadřazených popisků kategorií. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Určuje škálovací faktor pro bublinový diagram (může být mezi 0 a 300 % výchozí velikosti). |
| [hasUpDownBars()](#hasUpDownBars--) | Určuje, zda má Line- nebo Stock-diagram svislé/nahoru-dolů pruhy. |
| [getGapWidth()](#getGapWidth--) | Určuje prostor mezi shluky sloupců nebo sloupců jako procento šířky sloupce. |
| [getGapDepth()](#getGapDepth--) | Vrací nebo nastavuje vzdálenost, jako procento šířky značky, mezi datovými řadami ve 3D diagramu. |
| [isColorVaried()](#isColorVaried--) | Určuje, že každý datový marker v řadě má jinou barvu. |
| [hasSeriesLines()](#hasSeriesLines--) | Určuje, zda existují řádkové čáry pro tuto řadu a související řady. |
| [getOverlap()](#getOverlap--) | Určuje, jak moc se sloupce a sloupce překrývají v 2-D diagramech, jako procento (od −100 % do 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Určuje velikost druhého výseku nebo sloupce v diagramu pie-of-pie nebo bar-of-pie jako procento velikosti prvního výseku (může být mezi 5 a 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém výseku nebo sloupci v diagramu pie-of-pie nebo bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v diagramu pie-of-pie nebo bar-of-pie. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Určuje velikost díry v donut diagramu (může být mezi 10 a 90 % velikosti vykreslovací oblasti). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Určuje úhel prvního výseku v koláčovém nebo donut diagramu ve stupních (od 0 do 360 °, po směru hodinových ručiček od horní pozice). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Vlastní informace o rozdělení pro diagram pie-of-pie nebo bar-of-pie s vlastním rozdělením. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém diagramu. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Vzdálenost otevřeného výseku koláče od středu koláčového diagramu je vyjádřena v procentech průměru koláče. Číst/Zapisovat int.

**Vrací:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Vzdálenost otevřeného výseku koláče od středu koláčového diagramu je vyjádřena v procentech průměru koláče. Číst/Zapisovat int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Reprezentuje vyhlazování křivky. True pokud je vyhlazování křivky zapnuto pro line chart nebo scatter chart. Používá se pouze u line a scatter diagramů spojených čarami. Číst/Zapisovat boolean.

**Vrací:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Reprezentuje vyhlazování křivky. True pokud je vyhlazování křivky zapnuto pro line chart nebo scatter chart. Používá se pouze u line a scatter diagramů spojených čarami. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Vrací značku řady. Pouze pro čtení [IMarker](../../com.aspose.slides/imarker).

**Vrací:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Určuje tvar řady 3-D sloupcového diagramu. Změna hodnoty této vlastnosti může automaticky změnit typ řady. Číst/Zapisovat [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Vrací:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Určuje tvar řady 3-D sloupcového diagramu. Změna hodnoty této vlastnosti může automaticky změnit typ řady. Číst/Zapisovat [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Vrací název řady. Pouze pro čtení [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Vrací:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Vrací kolekci datových bodů této řady. Pouze pro čtení [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Vrací:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Vrací typ této řady. Číst/Zapisovat [ChartType](../../com.aspose.slides/charttype).

**Vrací:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Vrací typ této řady. Číst/Zapisovat [ChartType](../../com.aspose.slides/charttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Vrací skupinu nadřazených řad. Pouze pro čtení [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Vrací:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Vrací formát řady. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Vrací pořadí řady. Číst/Zapisovat int.

**Vrací:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Vrací pořadí řady. Číst/Zapisovat int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Vrací Labels řady. Pouze pro čtení [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Vrací:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Kolekce trendových čar řady Pouze pro čtení [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Vrací:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Reprezentuje ErrorBars řady s orientací X. Pouze pro čtení [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars se směrem X jsou k dispozici pro řady typu area, bar, scatter a bubble. Pro jiné typy diagramů tato vlastnost vrací null (včetně 3D diagramů). Při použití vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Vrací:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Reprezentuje ErrorBars řady s orientací Y. Pouze pro čtení [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars se směrem Y jsou k dispozici pro řady typu area, bar, line, scatter a bubble. Pro jiné typy diagramů tato vlastnost vrací null (včetně 3D diagramů). Při použití vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Vrací:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Určuje, zda je tato řada vykreslena na druhé hodnotové ose. Číst/Zapisovat boolean.

**Vrací:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Určuje, zda je tato řada vykreslena na druhé hodnotové ose. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Vrací nebo nastavuje formát čísel pro hodnoty řady. Číst/Zapisovat String.

**Vrací:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Vrací nebo nastavuje formát čísel pro hodnoty řady. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Vrací nebo nastavuje formát čísel pro x-hodnoty řady. Číst/Zapisovat String.

**Vrací:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Vrací nebo nastavuje formát čísel pro x-hodnoty řady. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Vrací nebo nastavuje formát čísel pro y-hodnoty řady. Číst/Zapisovat String.

**Vrací:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Vrací nebo nastavuje formát čísel pro y-hodnoty řady. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Vrací nebo nastavuje formát čísel pro velikosti bublin řady. Číst/Zapisovat String.

**Vrací:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Vrací nebo nastavuje formát čísel pro velikosti bublin řady. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Určuje, že sloupcová, sloupcová nebo bublinová řada má invertovat barvy, pokud je hodnota záporná. Číst/Zapisovat boolean.

**Vrací:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Určuje, že sloupcová, sloupcová nebo bublinová řada má invertovat barvy, pokud je hodnota záporná. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Určuje invertování plné barvy řady. Pro použití nastavení barvy nastavte FillType řady na FillType.Solid. Číst/Zapisovat [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Reprezentuje legendární položku související s touto řadou Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Vrací automatickou barvu řady na základě indexu řady a stylu diagramu. Tato barva je použita jako výchozí, pokud FillType je NotDefined.

**Vrací:**
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Reprezentuje vnitřní body. True pokud jsou vnitřní body zobrazeny v BoxAndWhisker diagramu. Používá se pouze u BoxAndWhisker diagramů. Číst/Zapisovat boolean.

**Vrací:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Reprezentuje vnitřní body. True pokud jsou vnitřní body zobrazeny v BoxAndWhisker diagramu. Používá se pouze u BoxAndWhisker diagramů. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Reprezentuje odlehlé body. True pokud jsou odlehlé body zobrazeny v BoxAndWhisker diagramu. Používá se pouze u BoxAndWhisker diagramů. Číst/Zapisovat boolean.

**Vrací:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Reprezentuje odlehlé body. True pokud jsou odlehlé body zobrazeny v BoxAndWhisker diagramu. Používá se pouze u BoxAndWhisker diagramů. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Reprezentuje průměrné značky. True pokud jsou průměrné značky zobrazeny v BoxAndWhisker diagramu. Používá se pouze u BoxAndWhisker diagramů. Číst/Zapisovat boolean.

**Vrací:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Reprezentuje průměrné značky. True pokud jsou průměrné značky zobrazeny v BoxAndWhisker diagramu. Používá se pouze u BoxAndWhisker diagramů. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Reprezentuje průměrné značky. True pokud je průměrná čára zobrazena v BoxAndWhisker diagramu. Používá se pouze u BoxAndWhisker diagramů. Číst/Zapisovat boolean.

**Vrací:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Reprezentuje průměrné značky. True pokud je průměrná čára zobrazena v BoxAndWhisker diagramu. Používá se pouze u BoxAndWhisker diagramů. Číst/Zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Reprezentuje metodu kvartilu. Používá se pouze u BoxAndWhisker diagramů.

**Vrací:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Reprezentuje metodu kvartilu. Používá se pouze u BoxAndWhisker diagramů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Reprezentuje spojovací čáry. Používá se pouze u Waterfall diagramů.

**Vrací:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Reprezentuje spojovací čáry. Používá se pouze u Waterfall diagramů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Reprezentuje rozložení nadřazených popisků kategorií. Používá se pouze u Treemap diagramů.

**Vrací:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Reprezentuje rozložení nadřazených popisků kategorií. Používá se pouze u Treemap diagramů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Určuje škálovací faktor pro bublinový diagram (může být mezi 0 a 300 % výchozí velikosti). Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.BubbleSizeScale pro změnu hodnoty.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.BubbleSizeScale.

**Vrací:**
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Určuje, zda má Line- nebo Stock-diagram svislé/nahoru-dolů pruhy. Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.UpDownBars.HasUpDownBars pro změnu hodnoty. Použijte ParentSeriesGroup.UpDownBars pro formát svislých/nahoru-dolů pruhů. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Vrací:**
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Určuje prostor mezi shluky sloupců nebo sloupců jako procento šířky sloupce. Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.GapWidth pro změnu hodnoty. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.GapWidth.

**Vrací:**
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Vrací nebo nastavuje vzdálenost, jako procento šířky značky, mezi datovými řadami ve 3D diagramu. Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.GapDepth pro změnu hodnoty. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.GapDepth.

**Vrací:**
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Určuje, že každý datový marker v řadě má jinou barvu. Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.IsColorVaried pro změnu hodnoty. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.IsColorVaried.

**Vrací:**
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Určuje, zda existují řádkové čáry pro tuto řadu a související řady. Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.HasSeriesLines pro změnu hodnoty. Použijte ParentSeriesGroup.SeriesLinesFormat pro formát řádkových čar. Pouze pro čtení boolean.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.HasSeriesLines.

**Vrací:**
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Určuje, jak moc se sloupce a sloupce překrývají v 2-D diagramech, jako procento (od −100 % do 100 %). Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad. Jedná se o projekci odpovídající skupinové vlastnosti, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte ParentSeriesGroup.Overlap. Pouze pro čtení byte.

--------------------

Overlap určuje míru překrytí nebo mezery mezi sloupci a sloupci jako procento jejich šířky:
- -100 %: Maximální mezera (sloupce jsou zcela odděleny).
- 0 %: Sloupce jsou vedle sebe bez překrytí či mezery.
- 100 %: Maximální překrytí (sloupce se zcela překrývají).
Jedná se o projekci vlastnosti ParentSeriesGroup.Overlap.

**Vrací:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Určuje velikost druhého výseku nebo sloupce v diagramu pie-of-pie nebo bar-of-pie jako procento velikosti prvního výseku (může být mezi 5 a 200 %). Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.SecondPieSize pro změnu hodnoty. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.SecondPieSize.

**Vrací:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém výseku nebo sloupci v diagramu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.PieSplitPosition pro změnu hodnoty. Pouze pro čtení double.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitPosition.

**Vrací:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v diagramu pie-of-pie nebo bar-of-pie. Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.PieSplitBy pro změnu hodnoty. Pouze pro čtení [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitBy. 2) Pokud je hodnota vlastnosti PieSplitType.Custom, můžete definovat vlastní informace o rozdělení pomocí vlastnosti ParentSeriesGroup.PieSplitCustomPoints.

**Vrací:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Určuje velikost díry v donut diagramu (může být mezi 10 a 90 % velikosti vykreslovací oblasti). Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.DoughnutHoleSize pro změnu hodnoty. Pouze pro čtení byte.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.DoughnutHoleSize.

**Vrací:**
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract   



```

Určuje úhel prvního výseku v koláčovém nebo donut diagramu ve stupních (od 0 do 360 °, po směru hodinových ručiček od horní pozice). Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.FirstSliceAngle pro změnu hodnoty. Pouze pro čtení int.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.FirstSliceAngle.

**Vrací:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Vlastní informace o rozdělení pro diagram pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém výseku nebo sloupci v diagramu pie-of-pie nebo bar-of-pie. Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti Pouze pro čtení [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.PieSplitCustomPoints.

**Vrací:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém diagramu. Toto není jen vlastnost této řady, ale všech řad ve skupině nadřazených řad – jde o projekci odpovídající skupinové vlastnosti. Proto je tato vlastnost pouze pro čtení. Použijte ParentSeriesGroup pro přístup ke skupině nadřazených řad. Použijte ParentSeriesGroup.BubbleSizeRepresentation pro změnu hodnoty.

--------------------

Jedná se o projekci vlastnosti ParentSeriesGroup.BubbleSizeRepresentation.

**Vrací:**
int