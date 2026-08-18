---
title: IChartSeriesGroup
second_title: Aspose.Slides Java API referencia
description: A sorozatok csoportját képviseli.
type: docs
url: /hu/com.aspose.slides/ichartseriesgroup/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

A sorozatok csoportját képviseli.

--------------------

1) Lásd a ChartSeriesGroupCollection osztály összegzését és megjegyzéseit, valamint a CombinableSeriesTypesGroup enumerációt. 2) A sorozatok csoportja olyan sorozatcsoport-tulajdonságokat tartalmaz, amelyek közösek a csoport minden sorozata számára („series group properties”). A „series group properties” a ChartSeriesGroup osztályban olvasható/írható. Minden „series group properties” rendelkezhet csak-olvasású leképezéssel a ChartSeries osztályban.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaadja ennek a sorozatcsoportnak a típusát. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Jelzi, hogy a csoport sorozatai a másodlagos tengelyen kerülnek-e ábrázolásra. |
| [getSeries()](#getSeries--) | Visszaad egy csak-olvasású gyűjteményt a diagram sorozatokról. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [getUpDownBars()](#getUpDownBars--) | Lehetővé teszi a fel/le sávok elérését Line- vagy Stock-chart diagramon. |
| [getGapWidth()](#getGapWidth--) | Megadja a sáv- vagy oszlop-csoportok közötti távolságot a sáv vagy oszlop szélességének százalékában. |
| [setGapWidth(int value)](#setGapWidth-int-) | Megadja a sáv- vagy oszlop-csoportok közötti távolságot a sáv vagy oszlop szélességének százalékában. |
| [getGapDepth()](#getGapDepth--) | Visszaadja vagy beállítja a távolságot, a marker szélességének százalékában, az adat sorozatok között egy 3D diagramon. |
| [setGapDepth(int value)](#setGapDepth-int-) | Visszaadja vagy beállítja a távolságot, a marker szélességének százalékában, az adat sorozatok között egy 3D diagramon. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Lekéri vagy beállítja az első kör- vagy galambkör-szelet szögét fokban (az órakorra felülről, 0-tól 360 fokig). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Lekéri vagy beállítja az első kör- vagy galambkör-szelet szögét fokban (az órakorra felülről, 0-tól 360 fokig). |
| [isColorVaried()](#isColorVaried--) | Megadja, hogy a sorozat minden adatjelzője különböző színű legyen. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Megadja, hogy a sorozat minden adatjelzője különböző színű legyen. |
| [hasSeriesLines()](#hasSeriesLines--) | Igaz, ha a diagramon sorozatvonalak vannak. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Igaz, ha a diagramon sorozatvonalak vannak. |
| [getOverlap()](#getOverlap--) | Megadja, mennyire fedjék egymást a sávok és oszlopok 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). |
| [setOverlap(byte value)](#setOverlap-byte-) | Megadja, mennyire fedjék egymást a sávok és oszlopok 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). |
| [getSecondPieSize()](#getSecondPieSize--) | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-200 % között). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-200 % között). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. |
| [getPieSplitBy()](#getPieSplitBy--) | Megadja, hogyan határozzák meg, hogy mely adatpontok legyenek a második körben vagy sávban egy pie-of-pie vagy bar-of-pie diagramon. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Megadja, hogyan határozzák meg, hogy mely adatpontok legyenek a második körben vagy sávban egy pie-of-pie vagy bar-of-pie diagramon. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Az egyéni felosztási információ egy egyéni felosztású pie-of-pie vagy bar-of-pie diagramhoz. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Megadja a lyuk méretét egy doughnut diagramon (10-90 % a ábrázolási terület méretétől). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Megadja a lyuk méretét egy doughnut diagramon (10-90 % a ábrázolási terület méretétől). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Megadja a méretezési tényezőt a bubble chart diagramhoz (0-300 % az alapértelmezett mérettől). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Megadja a méretezési tényezőt a bubble chart diagramhoz (0-300 % az alapértelmezett mérettől). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Megadja a HiLowLines formátumot. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Megadja, hogy a bubble size értékek hogyan jelennek meg a bubble chart diagramon. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Megadja, hogy a bubble size értékek hogyan jelennek meg a bubble chart diagramon. |

### getType() {#getType--}
```
public abstract int getType()
```

Visszaadja ennek a sorozatcsoportnak a típusát. Csak-olvasású [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Visszatér:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Jelzi, hogy a csoport sorozatai a másodlagos tengelyen kerülnek-e ábrázolásra. Csak-olvasású boolean.

**Visszatér:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Visszaad egy csak-olvasású gyűjteményt a diagram sorozatokról. Csak-olvasású [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Visszatér:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
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
public abstract IUpDownBarsManager getUpDownBars()
```

Lehetővé teszi a fel/le sávok elérését Line- vagy Stock-chart diagramon. Csak-olvasású [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Visszatér:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Megadja a sáv- vagy oszlop-csoportok közötti távolságot a sáv vagy oszlop szélességének százalékában. Olvasható/írható int.

**Visszatér:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Megadja a sáv- vagy oszlop-csoportok közötti távolságot a sáv vagy oszlop szélességének százalékában. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Visszaadja vagy beállítja a távolságot, a marker szélességének százalékában, az adat sorozatok között egy 3D diagramon. Olvasható/írható int.

**Visszatér:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Visszaadja vagy beállítja a távolságot, a marker szélességének százalékában, az adat sorozatok között egy 3D diagramon. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Lekéri vagy beállítja az első kör- vagy galambkör-szelet szögét fokban (az órakorra felülről, 0-tól 360 fokig). Olvasható/írható int.

**Visszatér:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Lekéri vagy beállítja az első kör- vagy galambkör-szelet szögét fokban (az órakorra felülről, 0-tól 360 fokig). Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Megadja, hogy a sorozat minden adatjelzője különböző színű legyen. Olvasható/írható boolean.

**Visszatér:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Megadja, hogy a sorozat minden adatjelzője különböző színű legyen. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Igaz, ha a diagramon sorozatvonalak vannak. Alkalmazva halmozott sáv- és OfPie diagramokra. Olvasható/írható boolean.

**Visszatér:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Igaz, ha a diagramon sorozatvonalak vannak. Alkalmazva halmozott sáv- és OfPie diagramokra. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Megadja, mennyire fedjék egymást a sávok és oszlopok 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). - -100 %: maximális térköz (a sávok teljesen el vannak választva). - 0 %: a sávok egymás mellett helyezkednek el átfedés vagy térköz nélkül. - 100 %: maximális átfedés (a sávok teljesen egymásra fednek). Ez a tulajdonság olvasható/írható byte.

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


**Visszatér:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Megadja, mennyire fedjék egymást a sávok és oszlopok 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). - -100 %: maximális térköz (a sávok teljesen el vannak választva). - 0 %: a sávok egymás mellett helyezkednek el átfedés vagy térköz nélkül. - 100 %: maximális átfedés (a sávok teljesen egymásra fednek). Ez a tulajdonság olvasható/írható byte.

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

Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-200 % között). Olvasható/írható int.

**Visszatér:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-200 % között). Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasható/írható double.

**Visszatér:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Megad egy értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasható/írható double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Megadja, hogyan határozzák meg, hogy mely adatpontok legyenek a második körben vagy sávban egy pie-of-pie vagy bar-of-pie diagramon. Olvasható/írható [PieSplitType](../../com.aspose.slides/piesplittype).

**Visszatér:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Megadja, hogyan határozzák meg, hogy mely adatpontok legyenek a második körben vagy sávban egy pie-of-pie vagy bar-of-pie diagramon. Olvasható/írható [PieSplitType](../../com.aspose.slides/piesplittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Az egyéni felosztási információ egy egyéni felosztású pie-of-pie vagy bar-of-pie diagramhoz. Azokat az adatpontokat tartalmazza, amelyeket a második körben vagy sávban kell megjeleníteni. Csak-olvasású [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Visszatér:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Megadja a lyuk méretét egy doughnut diagramon (10-90 % a ábrázolási terület méretétől). Olvasható/írható byte.

**Visszatér:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Megadja a lyuk méretét egy doughnut diagramon (10-90 % a ábrázolási terület méretétől). Olvasható/írható byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Megadja a méretezési tényezőt a bubble chart diagramhoz (0-300 % az alapértelmezett mérettől). Olvasható/írható int.

**Visszatér:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Megadja a méretezési tényezőt a bubble chart diagramhoz (0-300 % az alapértelmezett mérettől). Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Megadja a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusoknál alkalmazható.

**Visszatér:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Megadja, hogy a bubble size értékek hogyan jelennek meg a bubble chart diagramon. Olvasható/írható [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Visszatér:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Megadja, hogy a bubble size értékek hogyan jelennek meg a bubble chart diagramon. Olvasható/írható [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |