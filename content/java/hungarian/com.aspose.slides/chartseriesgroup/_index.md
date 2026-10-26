---
title: ChartSeriesGroup
second_title: Aspose.Slides Java API referenciája
description: A sorozatok csoportját képviseli.
type: docs
url: /hu/com.aspose.slides/chartseriesgroup/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

A sorozatok csoportját képviseli.

--------------------

1) Lásd a **ChartSeriesGroupCollection** osztály összefoglalóját és megjegyzéseit, valamint a **CombinableSeriesTypesGroup** felsorolt típusát. 2) A sorozatcsoport néhány, a csoport minden sorozatára közös tulajdonságot tartalmaz („series group properties”). A **ChartSeriesGroup** osztályban a „series group properties” olvasás/írás módú. Minden „series group properties” rendelkezhet csak olvasható leképezéssel a **ChartSeries** osztályban.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaadja ennek a sorozatcsoportnak a típusát. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Azt jelzi, hogy a csoport sorozatai a másodlagos tengelyen vannak-e ábrázolva. |
| [getSeries()](#getSeries--) | Visszaad egy sorozatgyűjteményt. |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexen. |
| [getUpDownBars()](#getUpDownBars--) | Hozzáférést biztosít a Vonalkövető vagy Részvény diagram fel- és le- oszlopaihoz. |
| [getGapWidth()](#getGapWidth--) | Meghatározza a sáv- vagy oszlopklaszterek közti távolságot a sáv vagy oszlop szélességének százalékában. |
| [setGapWidth(int value)](#setGapWidth-int-) | Meghatározza a sáv- vagy oszlopklaszterek közti távolságot a sáv vagy oszlop szélességének százalékában. |
| [getGapDepth()](#getGapDepth--) | Visszaadja vagy állítja be a 3D diagram adatcsoportrészei közti távolságot a marker szélességének százalékában. |
| [setGapDepth(int value)](#setGapDepth-int-) | Visszaadja vagy állítja be a 3D diagram adatcsoportrészei közti távolságot a marker szélességének százalékában. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Lekéri vagy állítja be az első pite- vagy donutdiagram szeletének szögét fokban (az órakortról felfelé, 0-tól 360 fokig). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Lekéri vagy állítja be az első pite- vagy donutdiagram szeletének szögét fokban (az órakortról felfelé, 0-tól 360 fokig). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Meghatározza a donutdiagram lyukjának méretét (0-tól 90 %-ig a rajzlap méretéhez képest). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Meghatározza a donutdiagram lyukjának méretét (0-tól 90 %-ig a rajzlap méretéhez képest). |
| [getOverlap()](#getOverlap--) | Meghatározza, hogy a sávok és oszlopok mennyire fedik egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). |
| [setOverlap(byte value)](#setOverlap-byte-) | Meghatározza, hogy a sávok és oszlopok mennyire fedik egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). |
| [getSecondPieSize()](#getSecondPieSize--) | Meghatározza a második pite vagy piteoszlop méretét a pite-pité vagy oszlop-pite diagramokban, az első pite méretének százalékában (5-tól 200 %-ig). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Meghatározza a második pite vagy piteoszlop méretét a pite-pité vagy oszlop-pite diagramokban, az első pite méretének százalékában (5-tól 200 %-ig). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Megadja, hogyan jelennek meg a buborékméret-értékek a buborékdiagramon. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Megadja, hogyan jelennek meg a buborékméret-értékek a buborékdiagramon. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Egy értéket ad meg, amely a második pite vagy piteoszlop adatpontjainak meghatározásához használatos pite-pité vagy oszlop-pite diagramokban. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Egy értéket ad meg, amely a második pite vagy piteoszlop adatpontjainak meghatározásához használatos pite-pité vagy oszlop-pite diagramokban. |
| [getPieSplitBy()](#getPieSplitBy--) | Megadja, hogyan határozzuk meg, mely adatpontok tartoznak a második pite vagy piteoszlopba pite-pité vagy oszlop-pite diagramokban. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Megadja, hogyan határozzuk meg, mely adatpontok tartoznak a második pite vagy piteoszlopba pite-pité vagy oszlop-pite diagramokban. |
| [isColorVaried()](#isColorVaried--) | Megadja, hogy a sorozat minden adatjelzője más színű legyen. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Megadja, hogy a sorozat minden adatjelzője más színű legyen. |
| [hasSeriesLines()](#hasSeriesLines--) | Igaz, ha a diagramnak sorozatsorai vannak. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Igaz, ha a diagramnak sorozatsorai vannak. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Megadja a HiLowLines formátumát. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Megadja a buborékdiagram méretezési tényezőjét (0-tól 300 %-ig az alapmérettől). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Megadja a buborékdiagram méretezési tényezőjét (0-tól 300 %-ig az alapmérettől). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | A testreszabott felosztási információ egy pite-pité vagy oszlop-pite diagramhoz. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [getSlide()](#getSlide--) | Visszaadja a **FillFormat** szülődiapozitívját. |
| [getPresentation()](#getPresentation--) | Visszaadja a **FillFormat** szülőprezentációját. |

### getType() {#getType--}
```
public final int getType()
```

Visszaadja ennek a sorozatcsoportnak a típusát. Csak olvasható [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Visszatér:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Azt jelzi, hogy a csoport sorozatai a másodlagos tengelyen vannak-e ábrázolva. Csak olvasható boolean.

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

Lekéri az elemet a megadott indexen.

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

Hozzáférést biztosít a Vonalkövető vagy Részvény diagram fel- és le- oszlopaihoz. Csak olvasható [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Visszatér:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Megadja a sáv- vagy oszlopklaszterek közti távolságot a sáv vagy oszlop szélességének százalékában. Olvasás/írás int.

**Visszatér:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Megadja a sáv- vagy oszlopklaszterek közti távolságot a sáv vagy oszlop szélességének százalékában. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Visszaadja vagy állítja be a 3D diagram adatcsoportrészei közti távolságot a marker szélességének százalékában. Olvasás/írás int.

**Visszatér:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Visszaadja vagy állítja be a 3D diagram adatcsoportrészei közti távolságot a marker szélességének százalékában. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Lekéri vagy állítja be az első pite vagy donutdiagram szeletének szögét fokban (az órakortról felfelé, 0-tól 360 fokig). Olvasás/írás int.

**Visszatér:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Lekéri vagy állítja be az első pite vagy donutdiagram szeletének szögét fokban (az órakortról felfelé, 0-tól 360 fokig). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Megadja a donutdiagram lyukjának méretét (0-tól 90 %-ig a rajzlap méretéhez képest). Olvasás/írás byte.

**Visszatér:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Megadja a donutdiagram lyukjának méretét (0-tól 90 %-ig a rajzlap méretéhez képest). Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Megadja, hogy a sávok és oszlopok mennyire fedik egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). -100 %: maximális távolság (a sávok teljesen el vannak választva). 0 %: a sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. 100 %: maximális átfedés (a sávok teljesen egymásra fednek). Ez a tulajdonság olvasás/írás byte.

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


**Visszatér:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Megadja, hogy a sávok és oszlopok mennyire fedik egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). -100 %: maximális távolság (a sávok teljesen el vannak választva). 0 %: a sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. 100 %: maximális átfedés (a sávok teljesen egymásra fednek). Ez a tulajdonság olvasás/írás byte.

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

Megadja a második pite vagy piteoszlop méretét a pite-pité vagy oszlop-pite diagramokban, az első pite méretének százalékában (5-tól 200 %-ig). Olvasás/írás int.

**Visszatér:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Megadja a második pite vagy piteoszlop méretét a pite-pité vagy oszlop-pite diagramokban, az első pite méretének százalékában (5-tól 200 %-ig). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Megadja, hogyan jelennek meg a buborékméret-értékek a buborékdiagramon. Olvasás/írás [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Visszatér:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Megadja, hogyan jelennek meg a buborékméret-értékek a buborékdiagramon. Olvasás/írás [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Megad egy értéket, amely a második pite vagy piteoszlop adatpontjainak meghatározásához használatos pite-pité vagy oszlop-pite diagramokban. A **PieSplitBy** tulajdonsággal együtt használatos. Olvasás/írás double.

**Visszatér:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Megad egy értéket, amely a második pite vagy piteoszlop adatpontjainak meghatározásához használatos pite-pité vagy oszlop-pite diagramokban. A **PieSplitBy** tulajdonsággal együtt használatos. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Megadja, hogyan határozzuk meg, mely adatpontok tartoznak a második pite vagy piteoszlopba pite-pité vagy oszlop-pite diagramokban. Olvasás/írás [PieSplitType](../../com.aspose.slides/piesplittype).

**Visszatér:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Megadja, hogyan határozzuk meg, mely adatpontok tartoznak a második pite vagy piteoszlopba pite-pité vagy oszlop-pite diagramokban. Olvasás/írás [PieSplitType](../../com.aspose.slides/piesplittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Megadja, hogy a sorozat minden adatjelzője más színű legyen. Olvasás/írás boolean.

**Visszatér:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Megadja, hogy a sorozat minden adatjelzője más színű legyen. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Igaz, ha a diagramnak sorozatsorai vannak. Alkalmazható halmozott sáv és OfPie diagramokra. Olvasás/írás boolean.

**Visszatér:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Igaz, ha a diagramnak sorozatsorai vannak. Alkalmazható halmozott sáv és OfPie diagramokra. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Megadja a HiLowLines formátumát. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt alkalmazható.

**Visszatér:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Megadja a buborékdiagram méretezési tényezőjét (0-tól 300 %-ig az alapmérettől). Olvasás/írás int.

**Visszatér:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Megadja a buborékdiagram méretezési tényezőjét (0-tól 300 %-ig az alapmérettől). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

A testreszabott felosztási információ egy pite-pité vagy oszlop-pite diagramhoz, amely egyedi felosztással rendelkezik. Tartalmazza azokat az adatpontokat, amelyek a második pite vagy piteoszlopban lesznek megjelenítve. Csak olvasható [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Visszatér:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a **Parent_Immediate** objektumot. Csak olvasható IDOMObject.

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

Visszaadja a **FillFormat** szülődiapozitívját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a **FillFormat** szülőprezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)