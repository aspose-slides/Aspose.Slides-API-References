---
title: IChartSeriesGroup
second_title: Aspose.Slides Androidhoz Java API referencia
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

1) Lásd a summary és remarks részt a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enum számára. 2) A sorozatok csoport olyan sorozat-tulajdonságokat tartalmaz, amelyek közösek minden sorozatra a csoportban („series group properties”). A „Series group properties” a ChartSeriesGroup osztályban olvasás/írás. Minden „series group properties” rendelkezhet csak olvasható leképezéssel a ChartSeries osztályban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getType()](#getType--) | Returns a type of this series group. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indicates if series of this group is plotted on secondary axis. |
| [getSeries()](#getSeries--) | Returns a readonly collection of chart series. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getUpDownBars()](#getUpDownBars--) | Provede access to up/down bars of Line- or Stock-chart. |
| [getGapWidth()](#getGapWidth--) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. |
| [getGapDepth()](#getGapDepth--) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. |
| [setGapDepth(int value)](#setGapDepth-int-) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [isColorVaried()](#isColorVaried--) | Specifies that each data marker in the series has a different color. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specifies that each data marker in the series has a different color. |
| [hasSeriesLines()](#hasSeriesLines--) | True if chart has series lines. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True if chart has series lines. |
| [getOverlap()](#getOverlap--) | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specifies HiLowLines format. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifies how the bubble size values are represented on the bubble chart. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specifies how the bubble size values are represented on the bubble chart. |
### getType() {#getType--}
```
public abstract int getType()
```

Visszaadja ennek a sorozatcsoportnak a típusát. **Csak olvasható** [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Visszatérési érték:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Megmutatja, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. **Csak olvasható** boolean.

**Visszatérési érték:**
boolean
### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Visszaad egy csak olvasható gyűjteményt a diagram sorozatokról. **Csak olvasható** [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Visszatérési érték:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Lekéri az elemet a megadott indexnél.

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

Provede access to up/down bars of Line- or Stock-chart. **Csak olvasható** [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Visszatérési érték:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Specifies the space between bar or column clusters, as a percentage of the bar or column width. **Olvasás/írás** int.

**Visszatérési érték:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Specifies the space between bar or column clusters, as a percentage of the bar or column width. **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Visszaadja vagy beállítja a távolságot, százalékban a marker szélességére vonatkozóan, a 3D diagram sorozatai között. **Olvasás/írás** int.

**Visszatérési érték:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Visszaadja vagy beállítja a távolságot, százalékban a marker szélességére vonatkozóan, a 3D diagram sorozatai között. **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Lekéri vagy beállítja az első kör vagy fánk diagram szeletének szögét fokban (az óramutató járásával megegyező irányban fentről, 0-tól 360 fokig). **Olvasás/írás** int.

**Visszatérési érték:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Lekéri vagy beállítja az első kör vagy fánk diagram szeletének szögét fokban (az óramutató járásával megegyező irányban fentről, 0-tól 360 fokig). **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Megadja, hogy a sorozat egyes adatjelzői különböző színűek-e. **Olvasás/írás** boolean.

**Visszatérési érték:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Megadja, hogy a sorozat egyes adatjelzői különböző színűek-e. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Igaz, ha a diagramnak sorozatsora van. Alkalmazott halmozott oszlop és OfPie diagramok esetén. **Olvasás/írás** boolean.

**Visszatérési érték:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Igaz, ha a diagramnak sorozatsora van. Alkalmazott halmozott oszlop és OfPie diagramok esetén. **Olvasás/írás** boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Megadja, hogy a 2-D diagramokon a sávok és oszlopok mekkora mértékben fedik egymást, százalékban (-100%-tól 100%-ig). - -100%: maximális távolság (a sávok teljesen szét vannak). - 0%: a sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. - 100%: maximális átfedés (a sávok teljesen átfedik egymást). Ez a tulajdonság **Olvasás/írás** byte.

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

Megadja, hogy a 2-D diagramokon a sávok és oszlopok mekkora mértékben fedik egymást, százalékban (-100%-tól 100%-ig). - -100%: maximális távolság (a sávok teljesen szét vannak). - 0%: a sávok egymás mellett helyezkednek el átfedés vagy távolság nélkül. - 100%: maximális átfedés (a sávok teljesen átfedik egymást). Ez a tulajdonság **Olvasás/írás** byte.

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

Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, a első kör méretének százalékában (5-tól 200 %-ig). **Olvasás/írás** int.

**Visszatérési érték:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, a első kör méretének százalékában (5-tól 200 %-ig). **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Megad egy értéket, amely a pie-of-pie vagy bar-of-pie diagramon a második kör vagy sávba tartozó adatpontok meghatározásához használható. A PieSplitBy tulajdonsággal együtt alkalmazható. **Olvasás/írás** double.

**Visszatérési érték:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Megad egy értéket, amely a pie-of-pie vagy bar-of-pie diagramon a második kör vagy sávba tartozó adatpontok meghatározásához használható. A PieSplitBy tulajdonsággal együtt alkalmazható. **Olvasás/írás** double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Megadja, hogyan kell meghatározni, mely adatpontok tartoznak a második kör vagy sávba egy pie-of-pie vagy bar-of-pie diagramon. **Olvasás/írás** [PieSplitType](../../com.aspose.slides/piesplittype).

**Visszatérési érték:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Megadja, hogyan kell meghatározni, mely adatpontok tartoznak a második kör vagy sávba egy pie-of-pie vagy bar-of-pie diagramon. **Olvasás/írás** [PieSplitType](../../com.aspose.slides/piesplittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

A saját felosztási információ egy pie-of-pie vagy bar-of-pie diagramhoz, amely saját felosztással rendelkezik. Tartalmazza azokat az adatpontokat, amelyek a második kör vagy sávban jelennek meg. **Csak olvasható** [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Visszatérési érték:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Megadja a fánk diagram lyukának méretét (10-tól 90 %-ig a plot terület méretéhez viszonyítva). **Olvasás/írás** byte.

**Visszatérési érték:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Megadja a fánk diagram lyukának méretét (10-tól 90 %-ig a plot terület méretéhez viszonyítva). **Olvasás/írás** byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Megadja a buborék diagram skálázási tényezőjét (0-tól 300 %-ig az alapértelmezett mérethez képest). **Olvasás/írás** int.

**Visszatérési érték:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Megadja a buborék diagram skálázási tényezőjét (0-tól 300 %-ig az alapértelmezett mérethez képest). **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Meghatározza a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusoknál alkalmazható.

**Visszatérési érték:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Megadja, hogyan jelennek meg a buborékméret értékek a buborékdiagramon. **Olvasás/írás** [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Visszatérési érték:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Megadja, hogyan jelennek meg a buborékméret értékek a buborékdiagramon. **Olvasás/írás** [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |