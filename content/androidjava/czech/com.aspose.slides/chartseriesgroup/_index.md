---
title: ChartSeriesGroup
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Representuje skupinu řad.
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

Representuje skupinu řad.

--------------------

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.
## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Vrací typ této skupiny řad. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Udává, zda jsou řady této skupiny vykresleny na sekundární ose. |
| [getSeries()](#getSeries--) | Vrací kolekci řad. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getUpDownBars()](#getUpDownBars--) | Provede přístup k up/down barům grafu typu Line nebo Stock. |
| [getGapWidth()](#getGapWidth--) | Určuje mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. |
| [setGapWidth(int value)](#setGapWidth-int-) | Určuje mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. |
| [getGapDepth()](#getGapDepth--) | Vrací nebo nastavuje vzdálenost, jako procento šířky markeru, mezi datovými řadami ve 3D grafu. |
| [setGapDepth(int value)](#setGapDepth-int-) | Vrací nebo nastavuje vzdálenost, jako procento šířky markeru, mezi datovými řadami ve 3D grafu. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Získá nebo nastaví úhel první výsečky koláčového nebo prstencového grafu ve stupních (odshora po směru hodinových ručiček, 0-360). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Získá nebo nastaví úhel první výsečky koláčového nebo prstencového grafu ve stupních (odshora po směru hodinových ručiček, 0-360). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Určuje velikost díry v prstencovém grafu (0-90 % velikosti oblasti vykreslování). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Určuje velikost díry v prstencovém grafu (0-90 % velikosti oblasti vykreslování). |
| [getOverlap()](#getOverlap--) | Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (-100 % až 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (-100 % až 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Určuje velikost druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento první výsečky (5-200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Určuje velikost druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento první výsečky (5-200 %). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bubble chartu. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bubble chartu. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Určuje hodnotu, která se použije k určení, které datové body patří do druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Určuje hodnotu, která se použije k určení, které datové body patří do druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Určuje, jak určit, které datové body patří do druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Určuje, jak určit, které datové body patří do druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | Určuje, že každý datový marker v řadě má jinou barvu. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Určuje, že každý datový marker v řadě má jinou barvu. |
| [hasSeriesLines()](#hasSeriesLines--) | Pravda, pokud má graf řádkové čáry řad. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Pravda, pokud má graf řádkové čáry řad. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Určuje formát HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Určuje měřítko pro bubble chart (0-300 % výchozí velikosti). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Určuje měřítko pro bubble chart (0-300 % výchozí velikosti). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |
### getType() {#getType--}
```
public final int getType()
```


Vrací typ této skupiny řad. Pouze pro čtení [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Vrací:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```


Udává, zda jsou řady této skupiny vykresleny na sekundární ose. Pouze pro čtení boolean.

**Vrací:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```


Vrací kolekci řad. Pouze pro čtení [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Vrací:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


Získá prvek na zadaném indexu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```


Provede přístup k up/down barům grafu typu Line nebo Stock. Pouze pro čtení [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Vrací:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```


Určuje mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. Čtení/Zápis int.

**Vrací:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```


Určuje mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. Čtení/Zápis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```


Vrací nebo nastavuje vzdálenost, jako procento šířky markeru, mezi datovými řadami ve 3D grafu. Čtení/Zápis int.

**Vrací:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```


Vrací nebo nastavuje vzdálenost, jako procento šířky markeru, mezi datovými řadami ve 3D grafu. Čtení/Zápis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```


Získá nebo nastaví úhel první výsečky koláčového nebo prstencového grafu ve stupních (odshora po směru hodinových ručiček, 0-360). Čtení/Zápis int.

**Vrací:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```


Získá nebo nastaví úhel první výsečky koláčového nebo prstencového grafu ve stupních (odshora po směru hodinových ručiček, 0-360). Čtení/Zápis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```


Určuje velikost díry v prstencovém grafu (0-90 % velikosti oblasti vykreslování). Čtení/Zápis byte.

**Vrací:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```


Určuje velikost díry v prstencovém grafu (0-90 % velikosti oblasti vykreslování). Čtení/Zápis byte.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```


Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (-100 % až 100 %). -100 %: maximální rozestup (sloupce jsou zcela oddělené). -0 %: sloupce jsou vedle sebe bez překrytí. 100 %: maximální překrytí (sloupce se úplně překrývají). Tato vlastnost je čtení/Zápis byte.

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


**Vrací:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```


Určuje, jak moc se mají sloupce a pruhy překrývat v 2-D grafech, jako procento (-100 % až 100 %). -100 %: maximální rozestup (sloupce jsou zcela oddělené). -0 %: sloupce jsou vedle sebe bez překrytí. 100 %: maximální překrytí (sloupce se úplně překrývají). Tato vlastnost je čtení/Zápis byte.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```


Určuje velikost druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento první výsečky (5-200 %). Čtení/Zápis int.

**Vrací:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```


Určuje velikost druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento první výsečky (5-200 %). Čtení/Zápis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```


Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bubble chartu. Čtení/Zápis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Vrací:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```


Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bubble chartu. Čtení/Zápis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```


Určuje hodnotu, která se použije k určení, které datové body patří do druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Čtení/Zápis double.

**Vrací:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```


Určuje hodnotu, která se použije k určení, které datové body patří do druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Čtení/Zápis double.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```


Určuje, jak určit, které datové body patří do druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Čtení/Zápis [PieSplitType](../../com.aspose.slides/piesplittype).

**Vrací:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```


Určuje, jak určit, které datové body patří do druhé výsečky nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Čtení/Zápis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```


Určuje, že každý datový marker v řadě má jinou barvu. Čtení/Zápis boolean.

**Vrací:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```


Určuje, že každý datový marker v řadě má jinou barvu. Čtení/Zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```


Pravda, pokud má graf řádkové čáry řad. Použito u sloupcových a OfPie grafů. Čtení/Zápis boolean.

**Vrací:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```


Pravda, pokud má graf řádkové čáry řad. Použito u sloupcových a OfPie grafů. Čtení/Zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```


Určuje formát HiLowLines. HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose.

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```


Určuje měřítko pro bubble chart (0-300 % výchozí velikosti). Čtení/Zápis int.

**Vrací:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```


Určuje měřítko pro bubble chart (0-300 % výchozí velikosti). Čtení/Zápis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhé výsečce nebo pruhu. Pouze pro čtení [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

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