---
title: IChartSeriesGroup
second_title: Aspose.Slides pro Java – reference API
description: Zastupuje skupinu řad.
type: docs
url: /cs/com.aspose.slides/ichartseriesgroup/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Zastupuje skupinu řad.

--------------------

1) Viz souhrn a poznámky pro třídu ChartSeriesGroupCollection a výčtový typ CombinableSeriesTypesGroup. 2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině („vlastnosti skupiny řad“). „Vlastnosti skupiny řad“ ve třídě ChartSeriesGroup jsou čtení/zápis. Každá z „vlastností skupiny řad“ může mít pouze pro čtení projekci ve třídě ChartSeries.

## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Vrací typ této skupiny řad. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Určuje, zda jsou řady této skupiny vykresleny na sekundární ose. |
| [getSeries()](#getSeries--) | Vrací kolekci řad grafu jen pro čtení. |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [getUpDownBars()](#getUpDownBars--) | Poskytuje přístup k up/down barům u čarového nebo akciového grafu. |
| [getGapWidth()](#getGapWidth--) | Získá nebo nastaví prostor mezi shluky pruhů nebo sloupců jako procento šířky pruhu nebo sloupce. |
| [setGapWidth(int value)](#setGapWidth-int-) | Získá nebo nastaví prostor mezi shluky pruhů nebo sloupců jako procento šířky pruhu nebo sloupce. |
| [getGapDepth()](#getGapDepth--) | Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky markeru. |
| [setGapDepth(int value)](#setGapDepth-int-) | Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky markeru. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Získá nebo nastaví úhel první výseče koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Získá nebo nastaví úhel první výseče koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). |
| [isColorVaried()](#isColorVaried--) | Určuje, že každý datový marker v řadě má jinou barvu. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Určuje, že každý datový marker v řadě má jinou barvu. |
| [hasSeriesLines()](#hasSeriesLines--) | True, pokud graf má řádky řady. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True, pokud graf má řádky řady. |
| [getOverlap()](#getOverlap--) | Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Určuje velikost druhého koláče nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče jako procento velikosti prvního koláče (může být mezi 5 % a 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Určuje velikost druhého koláče nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče jako procento velikosti prvního koláče (může být mezi 5 % a 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče. |
| [getPieSplitBy()](#getPieSplitBy--) | Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Vlastní informace o rozdělení pro graf koláč-z-koláče nebo pruh-z-koláče s vlastním rozdělením. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Určuje velikost díry v prstencovém grafu (může být mezi 10 % a 90 % velikosti oblasti grafu). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Určuje velikost díry v prstencovém grafu (může být mezi 10 % a 90 % velikosti oblasti grafu). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 % a 300 % výchozí velikosti). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 % a 300 % výchozí velikosti). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Určuje formát HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Určuje, jak jsou hodnoty velikosti bubliny zobrazeny v bublinovém grafu. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Určuje, jak jsou hodnoty velikosti bubliny zobrazeny v bublinovém grafu. |

### getType() {#getType--}
```
public abstract int getType()
```

Vrací typ této skupiny řad. Pouze pro čtení [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Vrací:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Určuje, zda jsou řady této skupiny vykresleny na sekundární ose. Pouze pro čtení boolean.

**Vrací:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Vrací kolekci řad grafu jen pro čtení. Pouze pro čtení [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Vrací:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
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
public abstract IUpDownBarsManager getUpDownBars()
```

Poskytuje přístup k up/down barům u čarového nebo akciového grafu. Pouze pro čtení [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Vrací:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Získá nebo nastaví prostor mezi shluky pruhů nebo sloupců jako procento šířky pruhu nebo sloupce. Hodnota musí být mezi 0 a 500. Čtení/Zápis int.

--------------------

Tato vlastnost platí pro řady následujících typů: Všechny podtypy pruhových a sloupcových řad, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Vrací:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Získá nebo nastaví prostor mezi shluky pruhů nebo sloupců jako procento šířky pruhu nebo sloupce. Hodnota musí být mezi 0 a 500. Čtení/Zápis int.

--------------------

Tato vlastnost platí pro řady následujících typů: Všechny podtypy pruhových a sloupcových řad, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky markeru. Hodnota musí být mezi 0 a 500. Čtení/Zápis int.

--------------------

Tato vlastnost platí pro řady následujících typů: Podtypy 3D pruhových a sloupcových řad, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Vrací:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Získá nebo nastaví vzdálenost mezi datovými řadami ve 3D grafu jako procento šířky markeru. Hodnota musí být mezi 0 a 500. Čtení/Zápis int.

--------------------

Tato vlastnost platí pro řady následujících typů: Podtypy 3D pruhových a sloupcových řad, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Získá nebo nastaví úhel první výseče koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Čtení/Zápis int.

**Vrací:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Získá nebo nastaví úhel první výseče koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Určuje, že každý datový marker v řadě má jinou barvu. Čtení/Zápis boolean.

**Vrací:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Určuje, že každý datový marker v řadě má jinou barvu. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

True, pokud graf má řádky řady. Použito u sloupcových grafů se seskupením a grafů OfPie. Čtení/Zápis boolean.

**Vrací:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

True, pokud graf má řádky řady. Použito u sloupcových grafů se seskupením a grafů OfPie. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %). - -100 %: Maximální rozestup (pruhy jsou zcela odděleny). - 0 %: Pruhy jsou umístěny vedle sebe bez překrytí nebo mezery. - 100 %: Maximální překrytí (pruhy se zcela překrývají). Tato vlastnost je čtení/zápis byte.

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
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Určuje, jak moc se mají pruhy a sloupce překrývat v 2-D grafech, jako procento (od -100 % do 100 %). - -100 %: Maximální rozestup (pruhy jsou zcela odděleny). - 0 %: Pruhy jsou umístěny vedle sebe bez překrytí nebo mezery. - 100 %: Maximální překrytí (pruhy se zcela překrývají). Tato vlastnost je čtení/zápis byte.

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
public abstract int getSecondPieSize()
```

Určuje velikost druhého koláče nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče jako procento velikosti prvního koláče (může být mezi 5 % a 200 %). Čtení/Zápis int.

**Vrací:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Určuje velikost druhého koláče nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče jako procento velikosti prvního koláče (může být mezi 5 % a 200 %). Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče. Používá se společně s vlastností PieSplitBy. Čtení/Zápis double.

**Vrací:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče. Používá se společně s vlastností PieSplitBy. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče. Čtení/Zápis [PieSplitType](../../com.aspose.slides/piesplittype).

**Vrací:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče. Čtení/Zápis [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Vlastní informace o rozdělení pro graf koláč-z-koláče nebo pruh-z-koláče s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém koláči nebo pruhu v grafu koláč-z-koláče nebo pruh-z-koláče. Pouze pro čtení [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Vrací:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Určuje velikost díry v prstencovém grafu (může být mezi 10 % a 90 % velikosti oblasti grafu). Čtení/Zápis byte.

**Vrací:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Určuje velikost díry v prstencovém grafu (může být mezi 10 % a 90 % velikosti oblasti grafu). Čtení/Zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Určuje měřítkový faktor pro bublinový graf (může být mezi 0 % a 300 % výchozí velikosti). Čtení/Zápis int.

**Vrací:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Určuje měřítkový faktor pro bublinový graf (může být mezi 0 % a 300 % výchozí velikosti). Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Určuje formát HiLowLines. HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose.

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Určuje, jak jsou hodnoty velikosti bubliny zobrazeny v bublinovém grafu. Čtení/Zápis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Vrací:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Určuje, jak jsou hodnoty velikosti bubliny zobrazeny v bublinovém grafu. Čtení/Zápis [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |