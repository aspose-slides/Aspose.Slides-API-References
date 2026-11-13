---
title: ChartSeriesGroup
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een groep van series voor.
type: docs
url: /nl/com.aspose.slides/chartseriesgroup/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Stelt een groep van series voor.

--------------------

1) Zie samenvatting en opmerkingen voor de class ChartSeriesGroupCollection en de enum CombinableSeriesTypesGroup. 2) Een groep van series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep (“series group properties”). “Series group properties” in de class ChartSeriesGroup is lees/schrijf. Elke “series group properties” kan een alleen-lezen projectie hebben in de class ChartSeries.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert een type van deze seriegroep. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of series van deze groep op een secundaire as worden weergegeven. |
| [getSeries()](#getSeries--) | Retourneert een verzameling series. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op de opgegeven index. |
| [getUpDownBars()](#getUpDownBars--) | Biedt toegang tot up/down-balken van een Line- of Stock-grafiek. |
| [getGapWidth()](#getGapWidth--) | Haalt op of stelt de ruimte tussen balk- of kolomclusters in, als een percentage van de breedte van de balk of kolom. |
| [setGapWidth(int value)](#setGapWidth-int-) | Haalt op of stelt de ruimte tussen balk- of kolomclusters in, als een percentage van de breedte van de balk of kolom. |
| [getGapDepth()](#getGapDepth--) | Haalt op of stelt de afstand tussen dataseries in een 3D-grafiek in, als een percentage van de marker-breedte. |
| [setGapDepth(int value)](#setGapDepth-int-) | Haalt op of stelt de afstand tussen dataseries in een 3D-grafiek in, als een percentage van de marker-breedte. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Haalt op of stelt de hoek van het eerste taart- of donut-grafieksegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Haalt op of stelt de hoek van het eerste taart- of donut-grafieksegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Bepaalt de grootte van het gat in een donut-grafiek (kan tussen 0 en 90 procent van de grootte van het plot-gebied liggen). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Bepaalt de grootte van het gat in een donut-grafiek (kan tussen 0 en 90 procent van de grootte van het plot-gebied liggen). |
| [getOverlap()](#getOverlap--) | Bepaalt hoeveel balken en kolommen moeten overlappen op 2-D-grafieken, als een percentage (van -100% tot 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Bepaalt hoeveel balken en kolommen moeten overlappen op 2-D-grafieken, als een percentage (van -100% tot 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Bepaalt de grootte van de tweede taart of balk in een taart-van-taart-grafiek of een balk-van-taart-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Bepaalt de grootte van de tweede taart of balk in een taart-van-taart-grafiek of een balk-van-taart-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Bepaalt hoe de bubbelformaat-waarden worden weergegeven op de bubbeldiagram. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Bepaalt hoe de bubbelformaat-waarden worden weergegeven op de bubbeldiagram. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Bepaalt een waarde die wordt gebruikt om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-grafiek. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Bepaalt een waarde die wordt gebruikt om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-grafiek. |
| [getPieSplitBy()](#getPieSplitBy--) | Bepaalt hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-grafiek. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Bepaalt hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-grafiek. |
| [isColorVaried()](#isColorVaried--) | Geeft aan dat elke datamarker in de serie een andere kleur heeft. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Geeft aan dat elke datamarker in de serie een andere kleur heeft. |
| [hasSeriesLines()](#hasSeriesLines--) | Waar als de grafiek serielijnen heeft. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Waar als de grafiek serielijnen heeft. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Bepaalt HiLowLines-opmaak. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Bepaalt de schaalfactor voor de bubbeldiagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Bepaalt de schaalfactor voor de bubbeldiagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste splitsingsinformatie voor een taart-van-taart of balk-van-taart grafiek met een aangepaste splitsing. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retourneert de bovenliggende grafiek. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Retourneert een type van deze seriegroep. Alleen-lezen [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Retourneert:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Geeft aan of series van deze groep op een secundaire as worden weergegeven. Alleen-lezen boolean.

**Retourneert:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Retourneert een verzameling series. Alleen-lezen [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Retourneert:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Biedt toegang tot up/down-balken van een Line- of Stock-grafiek. Alleen-lezen [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retourneert:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Haalt op of stelt de ruimte tussen balk- of kolomclusters in, als een percentage van de breedte van de balk of kolom. De waarde moet tussen 0 en 500 liggen. Lees/schrijf int.

--------------------

Deze eigenschap geldt voor series van de volgende typen: Bar-subtypes (zie ook methode [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), Column-subtypes (zie ook methode [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Retourneert:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Haalt op of stelt de ruimte tussen balk- of kolomclusters in, als een percentage van de breedte van de balk of kolom. De waarde moet tussen 0 en 500 liggen. Lees/schrijf int.

--------------------

Deze eigenschap geldt voor series van de volgende typen: Bar-subtypes (zie ook methode [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), Column-subtypes (zie ook methode [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Haalt op of stelt de afstand tussen dataseries in een 3D-grafiek in, als een percentage van de marker-breedte. De waarde moet tussen 0 en 500 liggen. Lees/schrijf int.

--------------------

Deze eigenschap geldt voor series van de volgende typen: 3D-bar- en column-subtypes (zie ook methode [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Retourneert:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Haalt op of stelt de afstand tussen dataseries in een 3D-grafiek in, als een percentage van de marker-breedte. De waarde moet tussen 0 en 500 liggen. Lees/schrijf int.

--------------------

Deze eigenschap geldt voor series van de volgende typen: 3D-bar- en column-subtypes (zie ook methode [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Haalt op of stelt de hoek van het eerste taart- of donut-grafieksegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lees/schrijf int.

**Retourneert:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Haalt op of stelt de hoek van het eerste taart- of donut-grafieksegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lees/schrijf int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Bepaalt de grootte van het gat in een donut-grafiek (kan tussen 0 en 90 procent van de grootte van het plot-gebied liggen). Lees/schrijf byte.

**Retourneert:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Bepaalt de grootte van het gat in een donut-grafiek (kan tussen 0 en 90 procent van de grootte van het plot-gebied liggen). Lees/schrijf byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Bepaalt hoeveel balken en kolommen moeten overlappen op 2-D-grafieken, als een percentage (van -100% tot 100%). - -100%: Maximale spatiëring (balken zijn volledig gescheiden). - 0%: Balken staan naast elkaar zonder overlap of spatiëring. - 100%: Maximale overlap (balken overlappen volledig). Deze eigenschap is lees/schrijf byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Stel overlap in op 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Bepaalt hoeveel balken en kolommen moeten overlappen op 2-D-grafieken, als een percentage (van -100% tot 100%). - -100%: Maximale spatiëring (balken zijn volledig gescheiden). - 0%: Balken staan naast elkaar zonder overlap of spatiëring. - 100%: Maximale overlap (balken overlappen volledig). Deze eigenschap is lees/schrijf byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Stel overlap in op 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Bepaalt de grootte van de tweede taart of balk in een taart-van-taart-grafiek of een balk-van-taart-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lees/schrijf int.

**Retourneert:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Bepaalt de grootte van de tweede taart of balk in een taart-van-taart-grafiek of een balk-van-taart-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lees/schrijf int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Bepaalt hoe de bubbelformaat-waarden worden weergegeven op de bubbeldiagram. Lees/schrijf [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retourneert:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Bepaalt hoe de bubbelformaat-waarden worden weergegeven op de bubbeldiagram. Lees/schrijf [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Bepaalt een waarde die wordt gebruikt om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-grafiek. Wordt gebruikt samen met de eigenschap PieSplitBy. Lees/schrijf double.

**Retourneert:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Bepaalt een waarde die wordt gebruikt om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-grafiek. Wordt gebruikt samen met de eigenschap PieSplitBy. Lees/schrijf double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Bepaalt hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-grafiek. Lees/schrijf [PieSplitType](../../com.aspose.slides/piesplittype).

**Retourneert:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Bepaalt hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-grafiek. Lees/schrijf [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Geeft aan dat elke datamarker in de serie een andere kleur heeft. Lees/schrijf boolean.

**Retourneert:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Geeft aan dat elke datamarker in de serie een andere kleur heeft. Lees/schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Waar als de grafiek serielijnen heeft. Toegepast op gestapelde balk- en OfPie-grafieken. Lees/schrijf boolean.

**Retourneert:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Waar als de grafiek serielijnen heeft. Toegepast op gestapelde balk- en OfPie-grafieken. Lees/schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Bepaalt HiLowLines-opmaak. HiLowLines wordt toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose grafiektype.

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Bepaalt de schaalfactor voor de bubbeldiagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lees/schrijf int.

**Retourneert:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Bepaalt de schaalfactor voor de bubbeldiagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lees/schrijf int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

De aangepaste splitsingsinformatie voor een taart-van-taart of balk-van-taart grafiek met een aangepaste splitsing. Bevat datapunten die getekend moeten worden in de tweede taart of balk in een taart-van-taart of balk-van-taart grafiek. Alleen-lezen [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Retourneert:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de bovenliggende grafiek. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retourneert:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een FillFormat. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een FillFormat. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)