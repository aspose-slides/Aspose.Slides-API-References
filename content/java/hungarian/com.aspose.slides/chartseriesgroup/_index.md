---
title: ChartSeriesGroup
second_title: Aspose.Slides Java API referencia
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

1) Tekintse meg a ChartSeriesGroupCollection osztály összefoglalóját és megjegyzéseit, valamint a CombinableSeriesTypesGroup enumerációt. 2) A sorozatok csoportja néhány sorozat-tulajdonságot tartalmaz, amely közös minden sorozatnál a csoportban („series group properties”). A „series group properties” a ChartSeriesGroup osztályban olvasás/írás. Minden „series group properties” rendelkezhet egy csak-olvasható vetülettel a ChartSeries osztályban.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaadja ennek a sorozatcsoportnak a típusát. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Megadja, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. |
| [getSeries()](#getSeries--) | Visszaad egy sorozatgyűjteményt. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [getUpDownBars()](#getUpDownBars--) | Hozzáférést biztosít a Line- vagy Stock-diagram fel- és le-oszlopaihoz. |
| [getGapWidth()](#getGapWidth--) | Lekéri vagy beállítja az oszlop vagy sáv klaszterek közti távolságot, a sáv vagy oszlop szélességének százalékában. |
| [setGapWidth(int value)](#setGapWidth-int-) | Lekéri vagy beállítja az oszlop vagy sáv klaszterek közti távolságot, a sáv vagy oszlop szélességének százalékában. |
| [getGapDepth()](#getGapDepth--) | Lekéri vagy beállítja a 3D diagram adat-sorozatai közti távolságot, a marker szélességének százalékában. |
| [setGapDepth(int value)](#setGapDepth-int-) | Lekéri vagy beállítja a 3D diagram adat-sorozatai közti távolságot, a marker szélességének százalékában. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Lekéri vagy beállítja az első kör vagy fánk diagram szeletének szögét fokban (az óramutató járásával megegyezően felülről, 0-tól 360-ig). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Lekéri vagy beállítja az első kör vagy fánk diagram szeletének szögét fokban (az óramutató járásával megegyezően felülről, 0-tól 360-ig). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Megadja a fánk diagram lyukjának méretét (0-tól a rajzterület méretének 90 %-áig). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Megadja a fánk diagram lyukjának méretét (0-tól a rajzterület méretének 90 %-áig). |
| [getOverlap()](#getOverlap--) | Megadja, hogy a sávok és oszlopok mennyire fedjék egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). |
| [setOverlap(byte value)](#setOverlap-byte-) | Megadja, hogy a sávok és oszlopok mennyire fedjék egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). |
| [getSecondPieSize()](#getSecondPieSize--) | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-tól 200-ig). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-tól 200-ig). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Megadja, hogyan legyenek a buborékméret-értékek megjelenítve a buborékdiagramon. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Megadja, hogyan legyenek a buborékméret-értékek megjelenítve a buborékdiagramon. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Megad egy értéket, amely meghatározza, mely adatpontok kerülnek a második kör vagy sávba egy pie-of-pie vagy bar-of-pie diagramon. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Megad egy értéket, amely meghatározza, mely adatpontok kerülnek a második kör vagy sávba egy pie-of-pie vagy bar-of-pie diagramon. |
| [getPieSplitBy()](#getPieSplitBy--) | Megadja, hogyan kell meghatározni, mely adatpontok vannak a második körben vagy sávban egy pie-of-pie vagy bar-of-pie diagramon. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Megadja, hogyan kell meghatározni, mely adatpontok vannak a második körben vagy sávban egy pie-of-pie vagy bar-of-pie diagramon. |
| [isColorVaried()](#isColorVaried--) | Megadja, hogy a sorozat minden adat-jelölője különböző színű legyen. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Megadja, hogy a sorozat minden adat-jelölője különböző színű legyen. |
| [hasSeriesLines()](#hasSeriesLines--) | Igaz, ha a diagramon sorozatsorok vannak. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Igaz, ha a diagramon sorozatsorok vannak. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Megadja a HiLowLines formátumát. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Megadja a buborékdiagram skálafaktorát (0-tól az alapméret 300 %-áig). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Megadja a buborékdiagram skálafaktorát (0-tól az alapméret 300 %-áig). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Az egyedi szétválasztási információ egy pie-of-pie vagy bar-of-pie diagramhoz egyedi szétválasztással. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő diát. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő prezentációt. |

### getType() {#getType--}
```
public final int getType()
```

Visszatér egy típusával ennek a sorozatcsoportnak. Csak-olvasható [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Visszatér:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Megadja, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. Csak-olvasható boolean.

**Visszatér:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Visszaad egy sorozatgyűjteményt. Csak-olvasható [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

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

Hozzáférést biztosít a Line- vagy Stock-diagram fel- és le-oszlopaihoz. Csak-olvasható [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Visszatér:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Lekéri vagy beállítja az oszlop vagy sáv klaszterek közti távolságot, a sáv vagy oszlop szélességének százalékában. Az érték 0-tól 500-ig terjedhet. Olvasás/írás int.

--------------------

Ez a tulajdonság a következő típusú sorozatokra vonatkozik: Bar alosztályok (lásd még [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metódus), Column alosztályok (lásd még [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) metódus), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Visszatér:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Lekéri vagy beállítja az oszlop vagy sáv klaszterek közti távolságot, a sáv vagy oszlop szélességének százalékában. Az érték 0-tól 500-ig terjedhet. Olvasás/írás int.

--------------------

Ez a tulajdonság a következő típusú sorozatokra vonatkozik: Bar alosztályok (lásd még [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) metódus), Column alosztályok (lásd még [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) metódus), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Lekéri vagy beállítja a 3D diagram adat-sorozatai közti távolságot, a marker szélességének százalékában. Az érték 0-tól 500-ig terjedhet. Olvasás/írás int.

--------------------

Ez a tulajdonság a következő típusú sorozatokra vonatkozik: 3D bar és column alosztályok (lásd még [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) metódus), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Visszatér:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Lekéri vagy beállítja a 3D diagram adat-sorozatai közti távolságot, a marker szélességének százalékában. Az érték 0-tól 500-ig terjedhet. Olvasás/írás int.

--------------------

Ez a tulajdonság a következő típusú sorozatokra vonatkozik: 3D bar és column alosztályok (lásd még [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) metódus), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Lekéri vagy beállítja az első kör vagy fánk diagram szeletének szögét fokban (az óramutató járásával megegyezően felülről, 0-tól 360-ig). Olvasás/írás int.

**Visszatér:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Lekéri vagy beállítja az első kör vagy fánk diagram szeletének szögét fokban (az óramutató járásával megegyezően felülről, 0-tól 360-ig). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Megadja a fánk diagram lyukjának méretét (0-tól a rajzterület méretének 90 %-áig). Olvasás/írás byte.

**Visszatér:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Megadja a fánk diagram lyukjának méretét (0-tól a rajzterület méretének 90 %-áig). Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Megadja, hogy a sávok és oszlopok mennyire fedjék egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). -100 %: maximális távolság (a sávok teljesen különállóak). -0 %: a sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. 100 %: maximális átfedés (a sávok teljesen egymásra fednek). Ez a tulajdonság olvasás/írás byte.

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

Megadja, hogy a sávok és oszlopok mennyire fedjék egymást 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). -100 %: maximális távolság (a sávok teljesen különállóak). -0 %: a sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. 100 %: maximális átfedés (a sávok teljesen egymásra fednek). Ez a tulajdonság olvasás/írás byte.

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

Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-tól 200-ig). Olvasás/írás int.

**Visszatér:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-tól 200-ig). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Megadja, hogyan legyenek a buborékméret-értékek megjelenítve a buborékdiagramon. Olvasás/írás [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Visszatér:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Megadja, hogyan legyenek a buborékméret-értékek megjelenítve a buborékdiagramon. Olvasás/írás [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Megad egy értéket, amelyet a második kör vagy sáv meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás double.

**Visszatér:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Megad egy értéket, amelyet a második kör vagy sáv meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Megadja, hogyan kell meghatározni, mely adatpontok vannak a második körben vagy sávban egy pie-of-pie vagy bar-of-pie diagramon. Olvasás/írás [PieSplitType](../../com.aspose.slides/piesplittype).

**Visszatér:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Megadja, hogyan kell meghatározni, mely adatpontok vannak a második körben vagy sávban egy pie-of-pie vagy bar-of-pie diagramon. Olvasás/írás [PieSplitType](../../com.aspose.slides/piesplittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Megadja, hogy a sorozat minden adat-jelölője különböző színű legyen. Olvasás/írás boolean.

**Visszatér:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Megadja, hogy a sorozat minden adat-jelölője különböző színű legyen. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Igaz, ha a diagramon sorozatsorok vannak. Alkalmazott stacked bar és OfPie diagramokra. Olvasás/írás boolean.

**Visszatér:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Igaz, ha a diagramon sorozatsorok vannak. Alkalmazott stacked bar és OfPie diagramokra. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Megadja a HiLowLines formátumát. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt használható.

**Visszatér:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Megadja a buborékdiagram skálafaktorát (0-tól az alapméret 300 %-áig). Olvasás/írás int.

**Visszatér:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Megadja a buborékdiagram skálafaktorát (0-tól az alapméret 300 %-áig). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Az egyedi szétválasztási információ egy pie-of-pie vagy bar-of-pie diagramhoz egyedi szétválasztással. Tartalmazza azokat az adatpontokat, amelyeket a második kör vagy sávban kell megjeleníteni. Csak-olvasható [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Visszatér:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak-olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a szülő diagramot. Csak-olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatér:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülő diát. Csak-olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülő prezentációt. Csak-olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)