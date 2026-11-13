---
title: IChartSeriesGroup
second_title: Aspose.Slides för Java API-referens
description: Representerar en grupp av serier.
type: docs
url: /sv/com.aspose.slides/ichartseriesgroup/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Representerar grupp av serier.

--------------------

1) Se sammanfattning och kommentarer för ChartSeriesGroupCollection class och CombinableSeriesTypesGroup enum. 2) En grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen (“series group properties”). “Series group properties” i ChartSeriesGroup class är läs/skriv. Varje av “series group properties” kan ha en skrivskyddad projektion i ChartSeries class.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getType()](#getType--) | Returnerar en typ av den här seriegrouppen. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Anger om serier i den här gruppen plottas på sekundär axel. |
| [getSeries()](#getSeries--) | Returnerar en skrivskyddad samling av diagramserier. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på angivet index. |
| [getUpDownBars()](#getUpDownBars--) | Tillhandahåller åtkomst till upp/ner-staplar i Line- eller Stock-diagram. |
| [getGapWidth()](#getGapWidth--) | Hämtar eller anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. |
| [setGapWidth(int value)](#setGapWidth-int-) | Hämtar eller anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. |
| [getGapDepth()](#getGapDepth--) | Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procentandel av markörens bredd. |
| [setGapDepth(int value)](#setGapDepth-int-) | Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procentandel av markörens bredd. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Hämtar eller anger vinkeln på den första paj- eller munkdiagram-snutten, i grader (medurs från upp, från 0 till 360 grader). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Hämtar eller anger vinkeln på den första paj- eller munkdiagram-snutten, i grader (medurs från upp, från 0 till 360 grader). |
| [isColorVaried()](#isColorVaried--) | Anger att varje datamarkör i serien har en annan färg. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Anger att varje datamarkör i serien har en annan färg. |
| [hasSeriesLines()](#hasSeriesLines--) | Sant om diagrammet har serielinjer. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Sant om diagrammet har serielinjer. |
| [getOverlap()](#getOverlap--) | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100 % till 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100 % till 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procentandel av storleken på den första pajen (kan vara mellan 5 % och 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procentandel av storleken på den första pajen (kan vara mellan 5 % och 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Anger ett värde som ska användas för att bestämma vilka datapunkter som hamnar i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Anger ett värde som ska användas för att bestämma vilka datapunkter som hamnar i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Anger hur man bestämmer vilka datapunkter som hamnar i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Anger hur man bestämmer vilka datapunkter som hamnar i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Den anpassade delningsinformationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad split. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Anger storleken på hålet i ett munkdiagram (kan vara mellan 10 % och 90 % av storleken på plotområdet). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Anger storleken på hålet i ett munkdiagram (kan vara mellan 10 % och 90 % av storleken på plotområdet). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 % och 300 % av standardstorleken). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 % och 300 % av standardstorleken). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Anger HiLowLines-format. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Anger hur bubbelstorleksvärdena representeras i bubbeldiagrammet. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Anger hur bubbelstorleksvärdena representeras i bubbeldiagrammet. |
### getType() {#getType--}
```
public abstract int getType()
```

Returnerar en typ av den här seriegrouppen. Skrivskyddad [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Returnerar:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Anger om serier i den här gruppen plottas på sekundär axel. Skrivskyddad boolean.

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

Hämtar elementet på angivet index.

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

Tillhandahåller åtkomst till upp/ner-staplar i Line- eller Stock-diagram. Skrivskyddad [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Returnerar:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Hämtar eller anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. Värdet måste vara mellan 0 och 500. Läs/skriv int.

--------------------

Denna egenskap gäller för serier av följande typer: Alla stapel- och kolumnsubtyper, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Returnerar:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Hämtar eller anger avståndet mellan stapel- eller kolumnkluster, som en procentandel av stapel- eller kolumnbredden. Värdet måste vara mellan 0 och 500. Läs/skriv int.

--------------------

Denna egenskap gäller för serier av följande typer: Alla stapel- och kolumnsubtyper, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procentandel av markörens bredd. Värdet måste vara mellan 0 och 500. Läs/skriv int.

--------------------

Denna egenskap gäller för serier av följande typer: 3D stapel- och kolumnsubtyper, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Returnerar:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procentandel av markörens bredd. Värdet måste vara mellan 0 och 500. Läs/skriv int.

--------------------

Denna egenskap gäller för serier av följande typer: 3D stapel- och kolumnsubtyper, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Hämtar eller anger vinkeln på den första paj- eller munkdiagram-snutten, i grader (medurs från upp, från 0 till 360 grader). Läs/skriv int.

**Returnerar:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Hämtar eller anger vinkeln på den första paj- eller munkdiagram-snutten, i grader (medurs från upp, från 0 till 360 grader). Läs/skriv int.

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

Sant om diagrammet har serielinjer. Tillämplig för staplade stapeldiagram och OfPie-diagram. Läs/skriv boolean.

**Returnerar:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Sant om diagrammet har serielinjer. Tillämplig för staplade stapeldiagram och OfPie-diagram. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100 % till 100 %). - -100 %: Maximalt avstånd (staplar är helt separerade). - 0 %: Staplar placeras sida vid sida utan överlappning eller avstånd. - 100 %: Maximal överlappning (staplar överlappar helt varandra). Denna egenskap är Läs/skriv byte.

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

Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentandel (från -100 % till 100 %). - -100 %: Maximalt avstånd (staplar är helt separerade). - 0 %: Staplar placeras sida vid sida utan överlappning eller avstånd. - 100 %: Maximal överlappning (staplar överlappar helt varandra). Denna egenskap är Läs/skriv byte.

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

Anger storleken på den andra pajen eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procentandel av storleken på den första pajen (kan vara mellan 5 % och 200 %). Läs/skriv int.

**Returnerar:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Anger storleken på den andra pajen eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procentandel av storleken på den första pajen (kan vara mellan 5 % och 200 %). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som hamnar i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med PieSplitBy-egenskapen. Läs/skriv double.

**Returnerar:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Anger ett värde som ska användas för att bestämma vilka datapunkter som hamnar i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med PieSplitBy-egenskapen. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Anger hur man bestämmer vilka datapunkter som hamnar i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Läs/skriv [PieSplitType](../../com.aspose.slides/piesplittype).

**Returnerar:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Anger hur man bestämmer vilka datapunkter som hamnar i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Läs/skriv [PieSplitType](../../com.aspose.slides/piesplittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Den anpassade delningsinformationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad split. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Skrivskyddad [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Returnerar:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Anger storleken på hålet i ett munkdiagram (kan vara mellan 10 % och 90 % av storleken på plotområdet). Läs/skriv byte.

**Returnerar:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Anger storleken på hålet i ett munkdiagram (kan vara mellan 10 % och 90 % av storleken på plotområdet). Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 % och 300 % av standardstorleken). Läs/skriv int.

**Returnerar:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 % och 300 % av standardstorleken). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Anger HiLowLines-format. HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose-diagramtyper.

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Anger hur bubbelstorleksvärdena representeras i bubbeldiagrammet. Läs/skriv [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Returnerar:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Anger hur bubbelstorleksvärdena representeras i bubbeldiagrammet. Läs/skriv [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |