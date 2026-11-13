---
title: ChartSeriesGroup
second_title: Aspose.Slides för Java API-referens
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

1) Se sammanfattning och kommentarer för ChartSeriesGroupCollection-klass och CombinableSeriesTypesGroup-enum. 2) Grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("seriegruppsegenskaper"). "Seriegruppsegenskaper" i ChartSeriesGroup-klass är läs/skriv. Varje av "seriegruppsegenskaper" kan ha en endast läsning-projektion i ChartSeries-klass.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Returnerar en typ av denna seriegrupp. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indikerar om serier i denna grupp plottas på sekundär axel. |
| [getSeries()](#getSeries--) | Returnerar en samling av serier. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [getUpDownBars()](#getUpDownBars--) | Tillhandahåller åtkomst till upp/ner staplar för linje- eller aktiediagram. |
| [getGapWidth()](#getGapWidth--) | Hämtar eller anger avståndet mellan stapel- eller kolumnkluster, som en procentsats av stapel- eller kolumnbredden. |
| [setGapWidth(int value)](#setGapWidth-int-) | Hämtar eller anger avståndet mellan stapel- eller kolumnkluster, som en procentsats av stapel- eller kolumnbredden. |
| [getGapDepth()](#getGapDepth--) | Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procentsats av markörens bredd. |
| [setGapDepth(int value)](#setGapDepth-int-) | Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procentsats av markörens bredd. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Hämtar eller anger vinkeln för den första paj- eller munkdiagramskivan, i grader (medurs från upp, från 0 till 360 grader). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Hämtar eller anger vinkeln för den första paj- eller munkdiagramskivan, i grader (medurs från upp, från 0 till 360 grader). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Anger storleken på hålet i ett munkdiagram (kan vara mellan 0 och 90 procent av storleken på plotområdet). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Anger storleken på hålet i ett munkdiagram (kan vara mellan 0 och 90 procent av storleken på plotområdet). |
| [getOverlap()](#getOverlap--) | Anger hur mycket staplar och kolumner ska överlappa i 2D-diagram, som en procentsats (från -100% till 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Anger hur mycket staplar och kolumner ska överlappa i 2D-diagram, som en procentsats (från -100% till 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Anger storleken på den andra pajen eller stapeln i ett paj-av-paj-diagram eller stapel-av-paj-diagram, som en procentsats av storleken på den första pajen (kan vara mellan 5 och 200 procent). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Anger storleken på den andra pajen eller stapeln i ett paj-av-paj-diagram eller stapel-av-paj-diagram, som en procentsats av storleken på den första pajen (kan vara mellan 5 och 200 procent). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Anger hur bubblestorleksvärden representeras i bubbeldiagrammet. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Anger hur bubblestorleksvärden representeras i bubbeldiagrammet. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. |
| [isColorVaried()](#isColorVaried--) | Anger att varje datamarkör i serien har en annan färg. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Anger att varje datamarkör i serien har en annan färg. |
| [hasSeriesLines()](#hasSeriesLines--) | Sant om diagrammet har serielinjer. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Sant om diagrammet har serielinjer. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Anger HiLowLines-format. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Den anpassade split-informationen för ett paj-av-paj- eller stapel-av-paj-diagram med anpassad split. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returnerar det överordnade diagrammet. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Returnerar en typ av denna seriegrupp. Endast läsning [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Returnerar:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indikerar om serier i denna grupp plottas på sekundär axel. Endast läsning boolean.

**Returnerar:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Returnerar en samling av serier. Endast läsning [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Returnerar:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
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
public final IUpDownBarsManager getUpDownBars()
```

Tillhandahåller åtkomst till upp/ner staplar för linje- eller aktiediagram. Endast läsning [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Returnerar:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Hämtar eller anger avståndet mellan stapel- eller kolumnkluster, som en procentsats av stapel- eller kolumnbredden. Värdet måste vara mellan 0 och 500. Läs/skriv int.

--------------------

Denna egenskap gäller för serier av följande typer: Bar-undertyper (se även [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)-metod), Kolumn-undertyper (se även [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)-metod), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Returnerar:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Hämtar eller anger avståndet mellan stapel- eller kolumnkluster, som en procentsats av stapel- eller kolumnbredden. Värdet måste vara mellan 0 och 500. Läs/skriv int.

--------------------

Denna egenskap gäller för serier av följande typer: Bar-undertyper (se även [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)-metod), Kolumn-undertyper (se även [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)-metod), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procentsats av markörens bredd. Värdet måste vara mellan 0 och 500. Läs/skriv int.

--------------------

Denna egenskap gäller för serier av följande typer: 3D bar and column undertyper (see also [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) method), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Returnerar:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procentsats av markörens bredd. Värdet måste vara mellan 0 och 500. Läs/skriv int.

--------------------

Denna egenskap gäller för serier av följande typer: 3D bar and column undertyper (see also [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) method), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Hämtar eller anger vinkeln för den första paj- eller munkdiagramskivan, i grader (medurs från upp, från 0 till 360 grader). Läs/skriv int.

**Returnerar:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Hämtar eller anger vinkeln för den första paj- eller munkdiagramskivan, i grader (medurs från upp, från 0 till 360 grader). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Anger storleken på hålet i ett munkdiagram (kan vara mellan 0 och 90 procent av storleken på plotområdet). Läs/skriv byte.

**Returnerar:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Anger storleken på hålet i ett munkdiagram (kan vara mellan 0 och 90 procent av storleken på plotområdet). Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Anger hur mycket staplar och kolumner ska överlappa i 2D-diagram, som en procentsats (från -100% till 100%). - -100%: Maximalt avstånd (staplar är helt separerade). - 0%: Staplar placeras sida vid sida utan överlappning eller avstånd. - 100%: Maximal överlappning (staplar överlappar varandra helt). Denna egenskap är läs/skriv byte.

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


**Returnerar:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Anger hur mycket staplar och kolumner ska överlappa i 2D-diagram, som en procentsats (från -100% till 100%). - -100%: Maximalt avstånd (staplar är helt separerade). - 0%: Staplar placeras sida vid sida utan överlappning eller avstånd. - 100%: Maximal överlappning (staplar överlappar varandra helt). Denna egenskap är läs/skriv byte.

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
public final int getSecondPieSize()
```

Anger storleken på den andra pajen eller stapeln i ett paj-av-paj-diagram eller stapel-av-paj-diagram, som en procentsats av storleken på den första pajen (kan vara mellan 5 och 200 procent). Läs/skriv int.

**Returnerar:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Anger storleken på den andra pajen eller stapeln i ett paj-av-paj-diagram eller stapel-av-paj-diagram, som en procentsats av storleken på den första pajen (kan vara mellan 5 och 200 procent). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Anger hur bubblestorleksvärden representeras i bubbeldiagrammet. Läs/skriv [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Returnerar:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Anger hur bubblestorleksvärden representeras i bubbeldiagrammet. Läs/skriv [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Används tillsammans med PieSplitBy-egenskapen. Läs/skriv double.

**Returnerar:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Används tillsammans med PieSplitBy-egenskapen. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Läs/skriv [PieSplitType](../../com.aspose.slides/piesplittype).

**Returnerar:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Läs/skriv [PieSplitType](../../com.aspose.slides/piesplittype).

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

Sant om diagrammet har serielinjer. Tillämpas på staplade stapeldiagram och OfPie-diagram. Läs/skriv boolean.

**Returnerar:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Sant om diagrammet har serielinjer. Tillämpas på staplade stapeldiagram och OfPie-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Anger HiLowLines-format. HiLowLines används med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose-diagramtyper.

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Läs/skriv int.

**Returnerar:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Den anpassade split-informationen för ett paj-av-paj- eller stapel-av-paj-diagram med anpassad split. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Endast läsning [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Returnerar:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Endast läsning IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Returnerar det överordnade diagrammet. Endast läsning [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den överordnade bilden för ett FillFormat. Endast läsning [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för ett FillFormat. Endas läsning [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)