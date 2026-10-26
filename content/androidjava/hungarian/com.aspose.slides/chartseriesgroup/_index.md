---
title: ChartSeriesGroup
second_title: Aspose.Slides Androidhoz Java API referencia
description: A sorozatok csoportját reprezentálja.
type: docs
url: /hu/com.aspose.slides/chartseriesgroup/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

A sorozatok csoportját reprezentálja.

--------------------

1) Lásd a ChartSeriesGroupCollection osztály összefoglalóját és megjegyzéseit, valamint a CombinableSeriesTypesGroup enum-et. 2) A sorozatok csoportja tartalmaz néhány sorozati tulajdonságot, amely közös minden sorozatra a csoportban ("Series group properties"). "Series group properties" a ChartSeriesGroup osztályban olvasás/írás. Minden "Series group properties" rendelkezhet egy csak olvasható vetülettel a ChartSeries osztályban.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaadja a sorozatcsoport típusát. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Megadja, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. |
| [getSeries()](#getSeries--) | Visszaad egy sorozatgyűjteményt. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [getUpDownBars()](#getUpDownBars--) | Elérést biztosít a vonal- vagy részvény-diagram fel/leszálló sávjaihoz. |
| [getGapWidth()](#getGapWidth--) | Megadja a sáv vagy oszlop csoportok közötti távolságot, a sáv vagy oszlop szélességének százalékában. |
| [setGapWidth(int value)](#setGapWidth-int-) | Megadja a sáv vagy oszlop csoportok közötti távolságot, a sáv vagy oszlop szélességének százalékában. |
| [getGapDepth()](#getGapDepth--) | Visszaadja vagy beállítja a távolságot, a jelölő szélesség százalékában, az adat sorozatok között egy 3D diagramon. |
| [setGapDepth(int value)](#setGapDepth-int-) | Visszaadja vagy beállítja a távolságot, a jelölő szélesség százalékában, az adat sorozatok között egy 3D diagramon. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Lekéri vagy beállítja az első kördiagram vagy fánkdiagram szeletének szögét fokban (az órával megegyező irányban fentről, 0-tól 360 fokig). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Lekéri vagy beállítja az első kördiagram vagy fánkdiagram szeletének szögét fokban (az órával megegyező irányban fentről, 0-tól 360 fokig). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Megadja a fánkdiagram lyukjának méretét (0-tól 90 %-ig a diagramterület méretének arányában). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Megadja a fánkdiagram lyukjának méretét (0-tól 90 %-ig a diagramterület méretének arányában). |
| [getOverlap()](#getOverlap--) | Megadja, hogy a sávok és oszlopok mennyire fedhetnek egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). |
| [setOverlap(byte value)](#setOverlap-byte-) | Megadja, hogy a sávok és oszlopok mennyire fedhetnek egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). |
| [getSecondPieSize()](#getSecondPieSize--) | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagram esetén, az első kör méretének százalékában (5-200 % között). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagram esetén, az első kör méretének százalékában (5-200 % között). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Megadja, hogy a buborékméret értékek hogyan jelennek meg a buborékdiagramon. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Megadja, hogy a buborékméret értékek hogyan jelennek meg a buborékdiagramon. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. |
| [getPieSplitBy()](#getPieSplitBy--) | Megadja, hogyan határozzák meg, mely adatpontok tartoznak a második kör vagy sávba egy pie-of-pie vagy bar-of-pie diagramon. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Megadja, hogyan határozzák meg, mely adatpontok tartoznak a második kör vagy sávba egy pie-of-pie vagy bar-of-pie diagramon. |
| [isColorVaried()](#isColorVaried--) | Megadja, hogy a sorozat minden adatjelölője más színű legyen. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Megadja, hogy a sorozat minden adatjelölője más színű legyen. |
| [hasSeriesLines()](#hasSeriesLines--) | Igaz, ha a diagram rendelkezik sorozatsorokkal. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Igaz, ha a diagram rendelkezik sorozatsorokkal. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Megadja a HiLowLines formátumot. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Megadja a méretezési tényezőt a buborékdiagramhoz (0-tól 300 %-ig az alapmérettől). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Megadja a méretezési tényezőt a buborékdiagramhoz (0-tól 300 %-ig az alapmérettől). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Az egyedi felosztási információ egy egyéni felosztással rendelkező pie-of-pie vagy bar-of-pie diagram számára. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő diáját. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő prezentációját. |

### getType() {#getType--}
```
public final int getType()
```

Visszaadja a sorozatcsoport típusát. Csak olvasható [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Visszatér:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Megadja, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. Csak olvasható boolean.

**Visszatér:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Visszaad egy sorozatgyűjteményt. Csak olvasható [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Visszatér:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Lekéri a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Elérést biztosít a vonal- vagy részvény-diagram fel/leszálló sávjaihoz. Csak olvasható [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Visszatér:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Megadja a sáv vagy oszlop csoportok közötti távolságot, a sáv vagy oszlop szélességének százalékában. Olvasás/írás int.

**Visszatér:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Megadja a sáv vagy oszlop csoportok közötti távolságot, a sáv vagy oszlop szélességének százalékában. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Visszaadja vagy beállítja a távolságot, a jelölő szélesség százalékában, az adat sorozatok között egy 3D diagramon. Olvasás/írás int.

**Visszatér:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Visszaadja vagy beállítja a távolságot, a jelölő szélesség százalékában, az adat sorozatok között egy 3D diagramon. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Lekéri vagy beállítja az első kördiagram vagy fánkdiagram szeletének szögét fokban (az órával megegyező irányban fentről, 0-tól 360 fokig). Olvasás/írás int.

**Visszatér:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Lekéri vagy beállítja az első kördiagram vagy fánkdiagram szeletének szögét fokban (az órával megegyező irányban fentről, 0-tól 360 fokig). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Megadja a fánkdiagram lyukjának méretét (0-tól 90 %-ig a diagramterület méretének arányában). Olvasás/írás byte.

**Visszatér:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Megadja a fánkdiagram lyukjának méretét (0-tól 90 %-ig a diagramterület méretének arányában). Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Megadja, hogy a sávok és oszlopok mennyire fedhetnek egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). --100%: Maximális távolság (a sávok teljesen elválasztva). - 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. - 100%: Maximális átfedés (a sávok teljesen átfedik egymást). Ez a tulajdonság olvasás/írás byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Állítsa be a átfedést 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Megadja, hogy a sávok és oszlopok mennyire fedhetnek egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). --100%: Maximális távolság (a sávok teljesen elválasztva). - 0%: A sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. - 100%: Maximális átfedés (a sávok teljesen átfedik egymást). Ez a tulajdonság olvasás/írás byte.

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
public final int getSecondPieSize()
```

Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagram esetén, az első kör méretének százalékában (5-200 % között). Olvasás/írás int.

**Visszatér:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagram esetén, az első kör méretének százalékában (5-200 % között). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Megadja, hogyan jelennek meg a buborékméret értékek a buborékdiagramon. Olvasás/írás [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Visszatér:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Megadja, hogyan jelennek meg a buborékméret értékek a buborékdiagramon. Olvasás/írás [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás double.

**Visszatér:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Megadja, hogyan határozzák meg, mely adatpontok tartoznak a második kör vagy sávba egy pie-of-pie vagy bar-of-pie diagramon. Olvasás/írás [PieSplitType](../../com.aspose.slides/piesplittype).

**Visszatér:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Megadja, hogyan határozzák meg, mely adatpontok tartoznak a második kör vagy sávba egy pie-of-pie vagy bar-of-pie diagramon. Olvasás/írás [PieSplitType](../../com.aspose.slides/piesplittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Megadja, hogy a sorozat minden adatjelölője más színű legyen. Olvasás/írás boolean.

**Visszatér:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Megadja, hogy a sorozat minden adatjelölője más színű legyen. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Igaz, ha a diagram sorozatsorokkal rendelkezik. Alkalmazható halmozott sáv és OfPie diagramokra. Olvasás/írás boolean.

**Visszatér:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Igaz, ha a diagram sorozatsorokkal rendelkezik. Alkalmazható halmozott sáv és OfPie diagramokra. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Megadja a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt használható.

**Visszatér:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Megadja a méretezési tényezőt a buborékdiagramhoz (0-tól 300 %-ig az alapmérettől). Olvasás/írás int.

**Visszatér:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Megadja a méretezési tényezőt a buborékdiagramhoz (0-tól 300 %-ig az alapmérettől). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Az egyedi felosztással rendelkező pie-of-pie vagy bar-of-pie diagram egyedi felosztási információja. Azokat az adatpontokat tartalmazza, amelyek a második kör vagy sávban jelennek meg egy pie-of-pie vagy bar-of-pie diagramon. Csak olvasható [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Visszatér:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

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

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülő diáját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)