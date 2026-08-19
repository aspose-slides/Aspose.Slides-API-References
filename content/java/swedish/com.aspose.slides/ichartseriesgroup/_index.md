---
title: IChartSeriesGroup
second_title: Aspose.Slides för Java API-referens
description: Representerar en grupp av serier.
type: docs
url: /sv/com.aspose.slides/ichartseriesgroup/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Representerar en grupp av serier.

--------------------

1) Se sammanfattning och anmärkningar för ChartSeriesGroupCollection klass och CombinableSeriesTypesGroup enum. 2) Grupp av serier innehåller vissa seriegenskaper som är gemensamma för varje serie i gruppen ("series group properties"). "Series group properties" i ChartSeriesGroup klass är läs/skriv. Varje av "series group properties" kan ha en skrivskyddad projektion i ChartSeries klass.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Returnerar en typ av den här serieggruppen. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Anger om serier i den här gruppen plottras på sekundär axel. |
| [getSeries()](#getSeries--) | Returnerar en skrivskyddad samling av diagramserier. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [getUpDownBars()](#getUpDownBars--) | Tillhandahåller åtkomst till upp/ner staplar av linje- eller aktiediagram. |
| [getGapWidth()](#getGapWidth--) | Anger avståndet mellan stapel- eller kolumnkluster, som en procent av stapel- eller kolumnbredden. |
| [setGapWidth(int value)](#setGapWidth-int-) | Anger avståndet mellan stapel- eller kolumnkluster, som en procent av stapel- eller kolumnbredden. |
| [getGapDepth()](#getGapDepth--) | Returnerar eller sätter avståndet, som en procent av markörbredden, mellan dataserierna i ett 3D-diagram. |
| [setGapDepth(int value)](#setGapDepth-int-) | Returnerar eller sätter avståndet, som en procent av markörbredden, mellan dataserierna i ett 3D-diagram. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Hämtar eller sätter vinkeln på den första paj- eller donut-diagramdelen, i grader (medurs från upp, från 0 till 360 grader). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Hämtar eller sätter vinkeln på den första paj- eller donut-diagramdelen, i grader (medurs från upp, från 0 till 360 grader). |
| [isColorVaried()](#isColorVaried--) | Anger att varje datamarkör i serien har en annan färg. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Anger att varje datamarkör i serien har en annan färg. |
| [hasSeriesLines()](#hasSeriesLines--) | Sant om diagrammet har serielinjer. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Sant om diagrammet har serielinjer. |
| [getOverlap()](#getOverlap--) | Anger hur mycket staplar och kolumner ska överlappa på 2-D diagram, som en procent (från -100% till 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Anger hur mycket staplar och kolumner ska överlappa på 2-D diagram, som en procent (från -100% till 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som en procent av storleken på den första pajen (kan vara mellan 5 och 200 procent). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som en procent av storleken på den första pajen (kan vara mellan 5 och 200 procent). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Anger ett värde som ska användas för att bestämma vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Anger ett värde som ska användas för att bestämma vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Anger hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Anger hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Den anpassade split-informationen för ett pie-of-pie- eller bar-of-pie-diagram med anpassad split. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Anger storleken på hålet i ett donut-diagram (kan vara mellan 10 och 90 procent av storleken på plot-området). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Anger storleken på hålet i ett donut-diagram (kan vara mellan 10 och 90 procent av storleken på plot-området). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Anger skalningsfaktorn för bubbel-diagrammet (kan vara mellan 0 och 300 procent av standardstorleken). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Anger skalningsfaktorn för bubbel-diagrammet (kan vara mellan 0 och 300 procent av standardstorleken). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Anger HiLowLines-format. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Anger hur bubbel-storleksvärden representeras i bubbel-diagrammet. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Anger hur bubbel-storleksvärden representeras i bubbel-diagrammet. |

### getType() {#getType--}
```
public abstract int getType()
```

Returnerar en typ av den här serieggruppen. Skrivskyddad [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Returnerar:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Anger om serier i den här gruppen plottras på sekundär axel. Skrivskyddad boolean.

**Returnerar:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Returnerar en skrivskyddad samling av diagramserier. Skrivskyddad [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Returnerar:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Tillhandahåller åtkomst till upp/ner staplar av linje- eller aktiediagram. Skrivskyddad [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Returnerar:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Anger avståndet mellan stapel- eller kolumnkluster, som en procent av stapel- eller kolumnbredden. Läs/skriv int.

**Returnerar:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Anger avståndet mellan stapel- eller kolumnkluster, som en procent av stapel- eller kolumnbredden. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Returnerar eller sätter avståndet, som en procent av markörbredden, mellan dataserierna i ett 3D-diagram. Läs/skriv int.

**Returnerar:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Returnerar eller sätter avståndet, som en procent av markörbredden, mellan dataserierna i ett 3D-diagram. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Hämtar eller sätter vinkeln på den första paj- eller donut-diagramdelen, i grader (medurs från upp, från 0 till 360 grader). Läs/skriv int.

**Returnerar:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Hämtar eller sätter vinkeln på den första paj- eller donut-diagramdelen, i grader (medurs från upp, från 0 till 360 grader). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Anger att varje datamarkör i serien har en annan färg. Läs/skriv boolean.

**Returnerar:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Anger att varje datamarkör i serien har en annan färg. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Sant om diagrammet har serielinjer. Tillämplig på staplade stapeldiagram och OfPie diagram. Läs/skriv boolean.

**Returnerar:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Sant om diagrammet har serielinjer. Tillämplig på staplade stapeldiagram och OfPie diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Anger hur mycket staplar och kolumner ska överlappa på 2-D diagram, som en procent (från -100% till 100%). - -100%: Maximal avstånd (staplarna är helt separerade). - 0%: Staplarna placeras sida vid sida utan överlappning eller avstånd. - 100%: Maximal överlappning (staplarna överlappar varandra helt). Denna egenskap är läs/skriv byte.

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
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Anger hur mycket staplar och kolumner ska överlappa på 2-D diagram, som en procent (från -100% till 100%). - -100%: Maximal avstånd (staplarna är helt separerade). - 0%: Staplarna placeras sida vid sida utan överlappning eller avstånd. - 100%: Maximal överlappning (staplarna överlappar varandra helt). Denna egenskap är läs/skriv byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ställ in överlappning till 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Anger storleken på den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som en procent av storleken på den första pajen (kan vara mellan 5 och 200 procent). Läs/skriv int.

**Returnerar:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Anger storleken på den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som en procent av storleken på den första pajen (kan vara mellan 5 och 200 procent). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med PieSplitBy-egenskapen. Läs/skriv double.

**Returnerar:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med PieSplitBy-egenskapen. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Anger hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Läs/skriv [PieSplitType](../../com.aspose.slides/piesplittype).

**Returnerar:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Anger hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Läs/skriv [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Den anpassade split-informationen för ett pie-of-pie- eller bar-of-pie-diagram med anpassad split. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Skrivskyddad [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Returnerar:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Anger storleken på hålet i ett donut-diagram (kan vara mellan 10 och 90 procent av storleken på plot-området). Läs/skriv byte.

**Returnerar:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Anger storleken på hålet i ett donut-diagram (kan vara mellan 10 och 90 procent av storleken på plot-området). Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Anger skalningsfaktorn för bubbel-diagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Läs/skriv int.

**Returnerar:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Anger skalningsfaktorn för bubbel-diagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Anger HiLowLines-format. HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose diagramtyper.

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Anger hur bubbel-storleksvärden representeras i bubbel-diagrammet. Läs/skriv [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Returnerar:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Anger hur bubbel-storleksvärden representeras i bubbel-diagrammet. Läs/skriv [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |