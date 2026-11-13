---
title: IChartSeriesGroup
second_title: Aspose.Slides for Java API Referenciája
description: A sorozatok csoportját képviseli.
type: docs
url: /hu/com.aspose.slides/ichartseriesgroup/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

A sorozatok csoportját képviseli.

--------------------

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaadja ennek a sorozatcsoportnak a típusát. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Megmutatja, hogy a csoport sorozata másodlagos tengelyen van-e ábrázolva. |
| [getSeries()](#getSeries--) | Visszaad egy csak olvasható gyűjteményt a diagram sorozatokról. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [getUpDownBars()](#getUpDownBars--) | Hozzáférést biztosít a fel/le sávokhoz vonal- vagy részvény-diagramon. |
| [getGapWidth()](#getGapWidth--) | A sáv vagy oszlop csoportok közötti térközt adja meg vagy állítja be, a sáv vagy oszlop szélességének százalékában. |
| [setGapWidth(int value)](#setGapWidth-int-) | A sáv vagy oszlop csoportok közötti térközt adja meg vagy állítja be, a sáv vagy oszlop szélességének százalékában. |
| [getGapDepth()](#getGapDepth--) | A 3D diagram adat sorozatai közötti távolságot adja meg vagy állítja be, a jelölő szélességének százalékában. |
| [setGapDepth(int value)](#setGapDepth-int-) | A 3D diagram adat sorozatai közötti távolságot adja meg vagy állítja be, a jelölő szélességének százalékában. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Az első kördiagram vagy fánk diagram szeletének szögét adja meg vagy állítja be fokban (óra járásával megegyező irányban felfelé nézve, 0-tól 360 fokig). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Az első kördiagram vagy fánk diagram szeletének szögét adja meg vagy állítja be fokban (óra járásával megegyező irányban felfelé nézve, 0-tól 360 fokig). |
| [isColorVaried()](#isColorVaried--) | Megadja, hogy a sorozat minden adatjelölője különböző színű legyen. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Megadja, hogy a sorozat minden adatjelölője különböző színű legyen. |
| [hasSeriesLines()](#hasSeriesLines--) | Igaz, ha a diagramnak sorozatsorai vannak. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Igaz, ha a diagramnak sorozatsorai vannak. |
| [getOverlap()](#getOverlap--) | Megadja, hogy a sávok és oszlopok mennyire fedjék egymást 2-D diagramokon, százalékban (-100 % és 100 % között). |
| [setOverlap(byte value)](#setOverlap-byte-) | Megadja, hogy a sávok és oszlopok mennyire fedjék egymást 2-D diagramokon, százalékban (-100 % és 100 % között). |
| [getSecondPieSize()](#getSecondPieSize--) | Megadja a második kör vagy sáv méretét a kör-kör vagy sáv-kör diagramon, az első kör méretének százalékában (5-tól 200-ig százalék). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Megadja a második kör vagy sáv méretét a kör-kör vagy sáv-kör diagramon, az első kör méretének százalékában (5-tól 200-ig százalék). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak a kör-kör vagy sáv-kör diagramon. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak a kör-kör vagy sáv-kör diagramon. |
| [getPieSplitBy()](#getPieSplitBy--) | Megadja, hogyan határozzák meg, mely adatpontok tartoznak a második kör vagy sáv alá a kör-kör vagy sáv-kör diagramon. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Megadja, hogyan határozzák meg, mely adatpontok tartoznak a második kör vagy sáv alá a kör-kör vagy sáv-kör diagramon. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Az egyéni felosztási információ egy egyedi felosztású kör-kör vagy sáv-kör diagramhoz. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Megadja a fánk diagram lyukjának méretét (10-tól 90-ig százalék a rajzterület méretéhez viszonyítva). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Megadja a fánk diagram lyukjának méretét (10-tól 90-ig százalék a rajzterület méretéhez viszonyítva). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Megadja a buborék diagram méretezési tényezőjét (0-tól 300-ig százalék az alapértelmezett mérettől). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Megadja a buborék diagram méretezési tényezőjét (0-tól 300-ig százalék az alapértelmezett mérettől). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Megadja a HiLowLines formátumot. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Megadja, hogyan jelennek meg a buborékméret értékek a buborék diagramon. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Megadja, hogyan jelennek meg a buborékméret értékek a buborék diagramon. |

### getType() {#getType--}
```
public abstract int getType()
```

Visszaadja ennek a sorozatcsoportnak a típusát. Csak olvasható [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Visszatérési érték:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Megmutatja, hogy a csoport sorozata másodlagos tengelyen van-e ábrázolva. Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Visszaad egy csak olvasható gyűjteményt a diagram sorozatokról. Csak olvasható [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Visszatérési érték:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Visszaadja a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Hozzáférést biztosít a fel/le sávokhoz vonal- vagy részvény-diagramon. Csak olvasható [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Visszatérési érték:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

A sáv vagy oszlop csoportok közötti térközt adja meg vagy állítja be, a sáv vagy oszlop szélességének százalékában. Az értéknek 0-tól 500-ig kell lennie. Olvasás/írás int.

--------------------

Ez a tulajdonság a következő típusú sorozatokra vonatkozik: minden sáv és oszlop altípus, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Visszatérési érték:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

A sáv vagy oszlop csoportok közötti térközt adja meg vagy állítja be, a sáv vagy oszlop szélességének százalékában. Az értéknek 0-tól 500-ig kell lennie. Olvasás/írás int.

--------------------

Ez a tulajdonság a következő típusú sorozatokra vonatkozik: minden sáv és oszlop altípus, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

A 3D diagram adat sorozatai közötti távolságot adja meg vagy állítja be, a jelölő szélességének százalékában. Az értéknek 0-tól 500-ig kell lennie. Olvasás/írás int.

--------------------

Ez a tulajdonság a következő típusú sorozatokra vonatkozik: 3D sáv és oszlop altípusok, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Visszatérési érték:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

A 3D diagram adat sorozatai közötti távolságot adja meg vagy állítja be, a jelölő szélességének százalékában. Az értéknek 0-tól 500-ig kell lennie. Olvasás/írás int.

--------------------

Ez a tulajdonság a következő típusú sorozatokra vonatkozik: 3D sáv és oszlop altípusok, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Az első kördiagram vagy fánk diagram szeletének szögét adja meg vagy állítja be fokban (óra járásával megegyező irányban felfelé nézve, 0-tól 360 fokig). Olvasás/írás int.

**Visszatérési érték:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Az első kördiagram vagy fánk diagram szeletének szögét adja meg vagy állítja be fokban (óra járásával megegyező irányban felfelé nézve, 0-tól 360 fokig). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Megadja, hogy a sorozat minden adatjelölője különböző színű legyen. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Megadja, hogy a sorozat minden adatjelölője különböző színű legyen. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Igaz, ha a diagramnak sorozatsorai vannak. Alkalmazható halmozott sáv és OfPie diagramokra. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Igaz, ha a diagramnak sorozatsorai vannak. Alkalmazható halmozott sáv és OfPie diagramokra. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Megadja, hogy a sávok és oszlopok mennyire fedjék egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). -100 %: maximális távolság (a sávok teljesen elkülönülnek). 0 %: a sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. 100 %: maximális átfedés (a sávok teljesen egymásra fednek). Ez a tulajdonság olvasás/írás byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Állítsa be az átfedést 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Megadja, hogy a sávok és oszlopok mennyire fedjék egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). -100 %: maximális távolság (a sávok teljesen elkülönülnek). 0 %: a sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. 100 %: maximális átfedés (a sávok teljesen egymásra fednek). Ez a tulajdonság olvasás/írás byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Állítsa be az átfedést 55%-ra
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Megadja a második kör vagy sáv méretét a kör-kör vagy sáv-kör diagramon, az első kör méretének százalékában (5-tól 200-ig százalék). Olvasás/írás int.

**Visszatérési érték:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Megadja a második kör vagy sáv méretét a kör-kör vagy sáv-kör diagramon, az első kör méretének százalékában (5-tól 200-ig százalék). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak a kör-kör vagy sáv-kör diagramon. A PieSplitBy tulajdonsággal együtt használható. Olvasás/írás double.

**Visszatérési érték:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak a kör-kör vagy sáv-kör diagramon. A PieSplitBy tulajdonsággal együtt használható. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Megadja, hogyan határozzák meg, mely adatpontok tartoznak a második kör vagy sáv alá a kör-kör vagy sáv-kör diagramon. Olvasás/írás [PieSplitType](../../com.aspose.slides/piesplittype).

**Visszatérési érték:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Megadja, hogyan határozzák meg, mely adatpontok tartoznak a második kör vagy sáv alá a kör-kör vagy sáv-kör diagramon. Olvasás/írás [PieSplitType](../../com.aspose.slides/piesplittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Az egyéni felosztási információ egy egyedi felosztású kör-kör vagy sáv-kör diagramhoz. A második kör vagy sávban megjelenítendő adatpontokat tartalmazza. Csak olvasható [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Visszatérési érték:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Megadja a fánk diagram lyukjának méretét (10-tól 90-ig százalék a rajzterület méretéhez viszonyítva). Olvasás/írás byte.

**Visszatérési érték:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Megadja a fánk diagram lyukjának méretét (10-tól 90-ig százalék a rajzterület méretéhez viszonyítva). Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Megadja a buborék diagram méretezési tényezőjét (0-tól 300-ig százalék az alapértelmezett mérettől). Olvasás/írás int.

**Visszatérési érték:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Megadja a buborék diagram méretezési tényezőjét (0-tól 300-ig százalék az alapértelmezett mérettől). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Megadja a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt használható.

**Visszatérési érték:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Megadja, hogyan jelennek meg a buborékméret értékek a buborék diagramon. Olvasás/írás [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Visszatérési érték:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Megadja, hogyan jelennek meg a buborékméret értékek a buborék diagramon. Olvasás/írás [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |