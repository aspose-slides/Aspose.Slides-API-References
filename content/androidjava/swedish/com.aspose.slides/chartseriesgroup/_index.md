---
title: ChartSeriesGroup
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en grupp av serier.
type: docs
url: /sv/com.aspose.slides/chartseriesgroup/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Representerar en grupp av serier.

--------------------

1) Se sammanfattning och anmärkningar för klassen ChartSeriesGroupCollection och enumen CombinableSeriesTypesGroup. 2) En grupp av serier innehåller vissa seriegenskaper som är gemensamma för varje serie i gruppen ("series group properties"). "Series group properties" i klassen ChartSeriesGroup är läs/skriv. Varje "series group properties" kan ha en skrivskyddad projektion i klassen ChartSeries.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Returnerar en typ av den här seriegruppen. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Anger om serier i den här gruppen plottas på sekundär axel. |
| [getSeries()](#getSeries--) | Returnerar en samling av serier. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på angivet index. |
| [getUpDownBars()](#getUpDownBars--) | Tillhandahåller åtkomst till upp/ner staplar för linje- eller aktie-diagram. |
| [getGapWidth()](#getGapWidth--) | Anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. |
| [setGapWidth(int value)](#setGapWidth-int-) | Anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. |
| [getGapDepth()](#getGapDepth--) | Returnerar eller anger avståndet, som en procentandel av markörbredden, mellan dataserierna i ett 3D-diagram. |
| [setGapDepth(int value)](#setGapDepth-int-) | Returnerar eller anger avståndet, som en procentandel av markörbredden, mellan dataserierna i ett 3D-diagram. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Hämtar eller anger vinkeln för den första tårt- eller donutdiagramdelen, i grader (medurs från uppåt, 0 till 360 grader). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Hämtar eller anger vinkeln för den första tårt- eller donutdiagramdelen, i grader (medurs från uppåt, 0 till 360 grader). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Anger storleken på hålet i ett donutdiagram (kan vara mellan 0 och 90 % av diagrammets plotområde). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Anger storleken på hålet i ett donutdiagram (kan vara mellan 0 och 90 % av diagrammets plotområde). |
| [getOverlap()](#getOverlap--) | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100 % till 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100 % till 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Anger storleken på den andra tårtan eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procentandel av storleken på den första tårtan (kan vara mellan 5 och 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Anger storleken på den andra tårtan eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procentandel av storleken på den första tårtan (kan vara mellan 5 och 200 %). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Anger hur bubbelstorleksvärdena representeras i bubbel-diagrammet. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Anger hur bubbelstorleksvärdena representeras i bubbel-diagrammet. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Anger hur man bestämmer vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Anger hur man bestämmer vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [isColorVaried()](#isColorVaried--) | Anger att varje datamarkör i serien har en annan färg. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Anger att varje datamarkör i serien har en annan färg. |
| [hasSeriesLines()](#hasSeriesLines--) | Sant om diagrammet har serielinjer. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Sant om diagrammet har serielinjer. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Anger HiLowLines-format. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Anger skalningsfaktorn för bubbel-diagrammet (kan vara mellan 0 och 300 % av standardstorleken). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Anger skalningsfaktorn för bubbel-diagrammet (kan vara mellan 0 och 300 % av standardstorleken). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Den anpassade delningsinformationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad delning. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returnerar det överordnade diagrammet. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Returnerar en typ av den här seriegruppen. Skrivskyddad [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Returnerar:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Anger om serier i den här gruppen plottas på sekundär axel. Skrivskyddad boolean.

**Returnerar:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Returnerar en samling av serier. Skrivskyddad [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Returnerar:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Hämtar elementet på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Tillhandahåller åtkomst till upp/ner staplar för linje- eller aktie-diagram. Skrivskyddad [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Returnerar:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. Läs/skriv int.

**Returnerar:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Returnerar eller anger avståndet, som en procentandel av markörbredden, mellan dataserierna i ett 3D-diagram. Läs/skriv int.

**Returnerar:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Returnerar eller anger avståndet, som en procentandel av markörbredden, mellan dataserierna i ett 3D-diagram. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Hämtar eller anger vinkeln för den första tårt- eller donutdiagramdelen, i grader (medurs från uppåt, 0 till 360 grader). Läs/skriv int.

**Returnerar:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Hämtar eller anger vinkeln för den första tårt- eller donutdiagramdelen, i grader (medurs från uppåt, 0 till 360 grader). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Anger storleken på hålet i ett donutdiagram (kan vara mellan 0 och 90 % av diagrammets plotområde). Läs/skriv byte.

**Returnerar:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Anger storleken på hålet i ett donutdiagram (kan vara mellan 0 och 90 % av diagrammets plotområde). Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100 % till 100 %). - -100 %: Maximal avstånd (staplarna är helt separerade). - 0 %: Staplar placeras sida vid sida utan överlappning eller avstånd. - 100 %: Maximal överlappning (staplarna överlappar helt varandra). Läs/skriv byte.

**Returnerar:**
byte

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


**Returnerar:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100 % till 100 %). - -100 %: Maximal avstånd (staplarna är helt separerade). - 0 %: Staplar placeras sida vid sida utan överlappning eller avstånd. - 100 %: Maximal överlappning (staplarna överlappar helt varandra). Läs/skriv byte.

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
public final int getSecondPieSize()
```

Anger storleken på den andra tårtan eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procentandel av storleken på den första tårtan (kan vara mellan 5 och 200 %). Läs/skriv int.

**Returnerar:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Anger storleken på den andra tårtan eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procentandel av storleken på den första tårtan (kan vara mellan 5 och 200 %). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Anger hur bubbelstorleksvärdena representeras i bubbel-diagrammet. Läs/skriv [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Returnerar:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Anger hur bubbelstorleksvärdena representeras i bubbel-diagrammet. Läs/skriv [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med egenskapen PieSplitBy. Läs/skriv double.

**Returnerar:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med egenskapen PieSplitBy. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Anger hur man bestämmer vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Läs/skriv [PieSplitType](../../com.aspose.slides/piesplittype).

**Returnerar:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Anger hur man bestämmer vilka datapunkter som finns i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Läs/skriv [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Anger att varje datamarkör i serien har en annan färg. Läs/skriv boolean.

**Returnerar:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Anger att varje datamarkör i serien har en annan färg. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Sant om diagrammet har serielinjer. Tillämpligt på staplade stapeldiagram och OfPie-diagram. Läs/skriv boolean.

**Returnerar:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Sant om diagrammet har serielinjer. Tillämpligt på staplade stapeldiagram och OfPie-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Anger HiLowLines-format. HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose diagramtyper.

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Anger skalningsfaktorn för bubbel-diagrammet (kan vara mellan 0 och 300 % av standardstorleken). Läs/skriv int.

**Returnerar:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Anger skalningsfaktorn för bubbel-diagrammet (kan vara mellan 0 och 300 % av standardstorleken). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Den anpassade delningsinformationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad delning. Innehåller datapunkter som ska ritas i den andra tårtan eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Skrivskyddad [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Returnerar:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar det överordnade diagrammet. Skrivskyddad [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för ett FillFormat. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för ett FillFormat. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)