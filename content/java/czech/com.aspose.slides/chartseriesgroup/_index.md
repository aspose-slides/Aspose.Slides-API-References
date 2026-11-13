---
title: ChartSeriesGroup
second_title: Aspose.Slides pro Java API Reference
description: Představuje skupinu řad.
type: docs
url: /cs/com.aspose.slides/chartseriesgroup/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Představuje skupinu řad.

--------------------

1) Viz souhrn a poznámky ke třídě ChartSeriesGroupCollection a výčtu CombinableSeriesTypesGroup. 2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině („vlastnosti skupiny řad“). „Vlastnosti skupiny řad“ ve třídě ChartSeriesGroup jsou čtení/zápis. Každá z „vlastností skupiny řad“ může mít projekci pouze pro čtení ve třídě ChartSeries.

## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Vrací typ této skupiny řad. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indikuje, zda jsou řady této skupiny vykresleny na sekundární ose. |
| [getSeries()](#getSeries--) | Vrací kolekci řad. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na určeném indexu. |
| [getUpDownBars()](#getUpDownBars--) | Poskytuje přístup k up/down barům grafu typu Line nebo Stock. |
| [getGapWidth()](#getGapWidth--) | Získá nebo nastaví mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. |
| [setGapWidth(int value)](#setGapWidth-int-) | Získá nebo nastaví mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. |
| [getGapDepth()](#getGapDepth--) | Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky markeru. |
| [setGapDepth(int value)](#setGapDepth-int-) | Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky markeru. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Získá nebo nastaví úhel první výseč koláčového nebo donutového grafu ve stupních (ve směru hodinových ručiček odshora, od 0 do 360 stupňů). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Získá nebo nastaví úhel první výseč koláčového nebo donutového grafu ve stupních (ve směru hodinových ručiček odshora, od 0 do 360 stupňů). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Určuje velikost otvoru v donutovém grafu (může být mezi 0 a 90 procenty velikosti vykreslovací plochy). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Určuje velikost otvoru v donutovém grafu (může být mezi 0 a 90 procenty velikosti vykreslovací plochy). |
| [getOverlap()](#getOverlap--) | Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (od -100 % do 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (od -100 % do 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Určuje velikost druhého koláče nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 procenty). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Určuje velikost druhého koláče nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 procenty). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Určuje, jak jsou hodnoty velikosti bublin zobrazovány v bublinovém grafu. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Určuje, jak jsou hodnoty velikosti bublin zobrazovány v bublinovém grafu. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | Určuje, že každý datový marker v řadě má jinou barvu. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Určuje, že každý datový marker v řadě má jinou barvu. |
| [hasSeriesLines()](#hasSeriesLines--) | True pokud má graf řádkové čáry. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True pokud má graf řádkové čáry. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Určuje formát HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Vlastní informace o rozdělení pro graf typu pie-of-pie nebo bar-of-pie s vlastním rozdělením. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Vrací typ této skupiny řad. Pouze pro čtení [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Návratová hodnota:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indikuje, zda jsou řady této skupiny vykresleny na sekundární ose. Pouze pro čtení boolean.

**Návratová hodnota:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Vrací kolekci řad. Pouze pro čtení [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Návratová hodnota:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Získá prvek na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Poskytuje přístup k up/down barům grafu typu Line nebo Stock. Pouze pro čtení [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Návratová hodnota:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Získá nebo nastaví mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. Hodnota musí být mezi 0 a 500. Čtení/Zápis int.

--------------------

Tato vlastnost se vztahuje na řady následujících typů: podtypy Bar (viz také metoda [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), podtypy Column (viz také metoda [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Návratová hodnota:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Získá nebo nastaví mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. Hodnota musí být mezi 0 a 500. Čtení/Zápis int.

--------------------

Tato vlastnost se vztahuje na řady následujících typů: podtypy Bar (viz také metoda [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), podtypy Column (viz také metoda [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky markeru. Hodnota musí být mezi 0 a 500. Čtení/Zápis int.

--------------------

Tato vlastnost se vztahuje na řady následujících typů: 3D podtypy bar a column (viz také metoda [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Návratová hodnota:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky markeru. Hodnota musí být mezi 0 a 500. Čtení/Zápis int.

--------------------

Tato vlastnost se vztahuje na řady následujících typů: 3D podtypy bar a column (viz také metoda [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Získá nebo nastaví úhel první výseč koláčového nebo donutového grafu ve stupních (ve směru hodinových ručiček odshora, od 0 do 360 stupňů). Čtení/Zápis int.

**Návratová hodnota:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Získá nebo nastaví úhel první výseč koláčového nebo donutového grafu ve stupních (ve směru hodinových ručiček odshora, od 0 do 360 stupňů). Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Určuje velikost otvoru v donutovém grafu (může být mezi 0 a 90 procenty velikosti vykreslovací plochy). Čtení/Zápis byte.

**Návratová hodnota:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Určuje velikost otvoru v donutovém grafu (může být mezi 0 a 90 procenty velikosti vykreslovací plochy). Čtení/Zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (od -100 % do 100 %). - -100 %: maximální mezera (sloupce jsou úplně oddělené). - 0 %: sloupce jsou vedle sebe bez překrytí nebo mezery. - 100 %: maximální překrytí (sloupce se úplně překrývají). Tato vlastnost je čtení/zápis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Nastavte překrytí na 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Návratová hodnota:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (od -100 % do 100 %). - -100 %: maximální mezera (sloupce jsou úplně oddělené). - 0 %: sloupce jsou vedle sebe bez překrytí nebo mezery. - 100 %: maximální překrytí (sloupce se úplně překrývají). Tato vlastnost je čtení/zápis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Nastavte překrytí na 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Určuje velikost druhého koláče nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 procenty). Čtení/Zápis int.

**Návratová hodnota:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Určuje velikost druhého koláče nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 procenty). Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Určuje, jak jsou hodnoty velikosti bublin zobrazovány v bublinovém grafu. Čtení/Zápis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Návratová hodnota:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Určuje, jak jsou hodnoty velikosti bublin zobrazovány v bublinovém grafu. Čtení/Zápis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie. Používá se společně s vlastností PieSplitBy. Čtení/Zápis double.

**Návratová hodnota:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie. Používá se společně s vlastností PieSplitBy. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie. Čtení/Zápis [PieSplitType](../../com.aspose.slides/piesplittype).

**Návratová hodnota:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu typu pie-of-pie nebo bar-of-pie. Čtení/Zápis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Určuje, že každý datový marker v řadě má jinou barvu. Čtení/Zápis boolean.

**Návratová hodnota:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Určuje, že každý datový marker v řadě má jinou barvu. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

True pokud má graf řádkové čáry. Použito u sloupcových a OfPie grafů. Čtení/Zápis boolean.

**Návratová hodnota:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

True pokud má graf řádkové čáry. Použito u sloupcových a OfPie grafů. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Určuje formát HiLowLines. HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose.

**Návratová hodnota:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Čtení/Zápis int.

**Návratová hodnota:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Vlastní informace o rozdělení pro graf typu pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém koláči nebo pruhu. Pouze pro čtení [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Návratová hodnota:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Návratová hodnota:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací nadřazený graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Návratová hodnota:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek objektu FillFormat. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Návratová hodnota:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci objektu FillFormat. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation)