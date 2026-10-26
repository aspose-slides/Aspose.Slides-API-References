---
title: ChartSeriesGroup
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje skupinu sérií.
type: docs
url: /cs/com.aspose.slides/chartseriesgroup/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Reprezentuje skupinu sérií.

--------------------

1) Viz souhrn a poznámky ke třídě ChartSeriesGroupCollection a výčtu CombinableSeriesTypesGroup enum. 2) Skupina sérií obsahuje některé vlastnosti sérií, které jsou společné pro každou sérii ve skupině ("series group properties"). "Series group properties" ve třídě ChartSeriesGroup jsou čtení/zápis. Každá z "series group properties" může mít v třídě ChartSeries pouze pro čtení projekci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Vrací typ této skupiny sérií. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Určuje, zda jsou série této skupiny vykresleny na sekundární ose. |
| [getSeries()](#getSeries--) | Vrací kolekci sérií. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getUpDownBars()](#getUpDownBars--) | Poskytuje přístup k up/down pruhům grafu typu Line nebo Stock. |
| [getGapWidth()](#getGapWidth--) | Určuje mezery mezi shluky pruhů nebo sloupců jako procento šířky pruhu nebo sloupce. |
| [setGapWidth(int value)](#setGapWidth-int-) | Určuje mezery mezi shluky pruhů nebo sloupců jako procento šířky pruhu nebo sloupce. |
| [getGapDepth()](#getGapDepth--) | Vrací nebo nastavuje vzdálenost jako procento šířky značky mezi datovými sériemi ve 3D grafu. |
| [setGapDepth(int value)](#setGapDepth-int-) | Vrací nebo nastavuje vzdálenost jako procento šířky značky mezi datovými sériemi ve 3D grafu. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Získává nebo nastavuje úhel první výseče koláčového nebo donutového grafu ve stupních (ve směru hodinových ručiček od vrchu, od 0 do 360 stupňů). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Získává nebo nastavuje úhel první výseče koláčového nebo donutového grafu ve stupních (ve směru hodinových ručiček od vrchu, od 0 do 360 stupňů). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Určuje velikost díry v donutovém grafu (může být mezi 0 a 90 procenty velikosti vykreslovací plochy). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Určuje velikost díry v donutovém grafu (může být mezi 0 a 90 procenty velikosti vykreslovací plochy). |
| [getOverlap()](#getOverlap--) | Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Určuje velikost druhé výseče nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti první výseče (může být mezi 5 a 200 procenty). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Určuje velikost druhé výseče nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti první výseče (může být mezi 5 a 200 procenty). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Určuje hodnotu, která má být použita k určení, které datové body jsou ve druhém výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Určuje hodnotu, která má být použita k určení, které datové body jsou ve druhém výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Určuje, jak určit, které datové body jsou ve druhém výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Určuje, jak určit, které datové body jsou ve druhém výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | Určuje, že každý datový marker v sérii má jinou barvu. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Určuje, že každý datový marker v sérii má jinou barvu. |
| [hasSeriesLines()](#hasSeriesLines--) | True, pokud graf obsahuje řádové čáry. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True, pokud graf obsahuje řádové čáry. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Určuje formát HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Určuje škálovací faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Určuje škálovací faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Vrací typ této skupiny sérií. Pouze pro čtení [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Vrací:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Určuje, zda jsou série této skupiny vykresleny na sekundární ose. Pouze pro čtení boolean.

**Vrací:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Vrací kolekci sérií. Pouze pro čtení [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Vrací:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Získá prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Poskytuje přístup k up/down pruhům grafu typu Line nebo Stock. Pouze pro čtení [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Vrací:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Určuje mezery mezi shluky pruhů nebo sloupců jako procento šířky pruhu nebo sloupce. Čtení/zápis int.

**Vrací:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Určuje mezery mezi shluky pruhů nebo sloupců jako procento šířky pruhu nebo sloupce. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Vrací nebo nastavuje vzdálenost jako procento šířky značky mezi datovými sériemi ve 3D grafu. Čtení/zápis int.

**Vrací:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Vrací nebo nastavuje vzdálenost jako procento šířky značky mezi datovými sériemi ve 3D grafu. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Získává nebo nastavuje úhel první výseče koláčového nebo donutového grafu ve stupních (ve směru hodinových ručiček od vrchu, od 0 do 360 stupňů). Čtení/zápis int.

**Vrací:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Získává nebo nastavuje úhel první výseče koláčového nebo donutového grafu ve stupních (ve směru hodinových ručiček od vrchu, od 0 do 360 stupňů). Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Určuje velikost díry v donutovém grafu (může být mezi 0 a 90 procenty velikosti vykreslovací plochy). Čtení/zápis byte.

**Vrací:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Určuje velikost díry v donutovém grafu (může být mezi 0 a 90 procenty velikosti vykreslovací plochy). Čtení/zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %). -100 %: maximální rozestup (pruhy jsou zcela odděleny). 0 %: pruhy jsou vedle sebe bez překrytí nebo mezery. 100 %: maximální překrytí (pruhy se zcela překrývají). Tato vlastnost je čtení/zápis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %). -100 %: maximální rozestup (pruhy jsou zcela odděleny). 0 %: pruhy jsou vedle sebe bez překrytí nebo mezery. 100 %: maximální překrytí (pruhy se zcela překrývají). Tato vlastnost je čtení/zápis byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Nastavit překrytí na 55%
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

Určuje velikost druhé výseče nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti první výseče (může být mezi 5 a 200 procenty). Čtení/zápis int.

**Vrací:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Určuje velikost druhé výseče nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti první výseče (může být mezi 5 a 200 procenty). Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. Čtení/zápis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Vrací:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. Čtení/zápis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Určuje hodnotu, která má být použita k určení, které datové body jsou ve druhém výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Čtení/zápis double.

**Vrací:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Určuje hodnotu, která má být použita k určení, které datové body jsou ve druhém výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Určuje, jak určit, které datové body jsou ve druhém výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Čtení/zápis [PieSplitType](../../com.aspose.slides/piesplittype).

**Vrací:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Určuje, jak určit, které datové body jsou ve druhém výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Čtení/zápis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Určuje, že každý datový marker v sérii má jinou barvu. Čtení/zápis boolean.

**Vrací:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Určuje, že každý datový marker v sérii má jinou barvu. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

True, pokud graf obsahuje řádové čáry. Používá se u sloupcových a OfPie grafů. Čtení/zápis boolean.

**Vrací:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

True, pokud graf obsahuje řádové čáry. Používá se u sloupcových a OfPie grafů. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Určuje formát HiLowLines. HiLowLines se používá s typy grafu HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose.

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Určuje škálovací faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Čtení/zápis int.

**Vrací:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Určuje škálovací faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém výseči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Pouze pro čtení [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Vrací:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

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