---
title: ChartSeriesGroup
second_title: Aspose.Slides voor Android via Java API-referentie
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

1) Zie samenvatting en opmerkingen voor de klasse ChartSeriesGroupCollection en de enum CombinableSeriesTypesGroup. 2) Groep van series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("series group properties"). "Series group properties" in de klasse ChartSeriesGroup is lezen/schrijven. Elke "series group properties" kan een alleen-lezen projectie hebben in de klasse ChartSeries.

## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert een type van deze serieengroep. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of series van deze groep worden weergegeven op een secundaire as. |
| [getSeries()](#getSeries--) | Retourneert een collectie van series. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getUpDownBars()](#getUpDownBars--) | Biedt toegang tot op/af-balken van een lijngrafiek of een aandelengrafiek. |
| [getGapWidth()](#getGapWidth--) | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de breedte van de balk of kolom. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de breedte van de balk of kolom. |
| [getGapDepth()](#getGapDepth--) | Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensseries in een 3D-grafiek. |
| [setGapDepth(int value)](#setGapDepth-int-) | Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensseries in een 3D-grafiek. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Haalt op of stelt de hoek in van het eerste part- of donutgrafieksegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Haalt op of stelt de hoek in van het eerste part- of donutgrafieksegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificeert de grootte van het gat in een donutgrafiek (kan tussen 0 en 90 procent van de grootte van het plotgebied liggen). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specificeert de grootte van het gat in een donutgrafiek (kan tussen 0 en 90 procent van de grootte van het plotgebied liggen). |
| [getOverlap()](#getOverlap--) | Specificeert hoeveel balken en kolommen moeten overlappen in 2D-grafieken, als een percentage (van -100% tot 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specificeert hoeveel balken en kolommen moeten overlappen in 2D-grafieken, als een percentage (van -100% tot 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificeert de grootte van de tweede part of balk van een part-in-part grafiek of een balk-in-part grafiek, als een percentage van de grootte van de eerste part (kan tussen 5 en 200 procent liggen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specificeert de grootte van de tweede part of balk van een part-in-part grafiek of een balk-in-part grafiek, als een percentage van de grootte van de eerste part (kan tussen 5 en 200 procent liggen). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificeert hoe de bubbelgroottwaarden worden weergegeven op de bubbelgrafiek. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specificeert hoe de bubbelgroottwaarden worden weergegeven op de bubbelgrafiek. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten zich in de tweede part of balk bevinden in een part-in-part of balk-in-part grafiek. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten zich in de tweede part of balk bevinden in een part-in-part of balk-in-part grafiek. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede part of balk bevinden in een part-in-part of balk-in-part grafiek. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede part of balk bevinden in een part-in-part of balk-in-part grafiek. |
| [isColorVaried()](#isColorVaried--) | Specificeert dat elke gegevensmarkering in de serie een andere kleur heeft. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specificeert dat elke gegevensmarkering in de serie een andere kleur heeft. |
| [hasSeriesLines()](#hasSeriesLines--) | Waar als de grafiek serieslijnen heeft. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Waar als de grafiek serieslijnen heeft. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specificeert HiLowLines-indeling. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste splitsingsinformatie voor een part-in-part of balk-in-part grafiek met een aangepaste splitsing. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retourneert de bovenliggende grafiek. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Retourneert een type van deze serieengroep. Alleen-lezen [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Retourneert:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Geeft aan of series van deze groep worden weergegeven op een secundaire as. Alleen-lezen boolean.

**Retourneert:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Retourneert een collectie van series. Alleen-lezen [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Retourneert:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Biedt toegang tot op/af-balken van een lijngrafiek of een aandelengrafiek. Alleen-lezen [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retourneert:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de breedte van de balk of kolom. Lezen/Schrijven int.

**Retourneert:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de breedte van de balk of kolom. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensseries in een 3D-grafiek. Lezen/Schrijven int.

**Retourneert:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensseries in een 3D-grafiek. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Haalt op of stelt de hoek in van het eerste part- of donutgrafieksegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/Schrijven int.

**Retourneert:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Haalt op of stelt de hoek in van het eerste part- of donutgrafieksegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Specificeert de grootte van het gat in een donutgrafiek (kan tussen 0 en 90 procent van de grootte van het plotgebied liggen). Lezen/Schrijven byte.

**Retourneert:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Specificeert de grootte van het gat in een donutgrafiek (kan tussen 0 en 90 procent van de grootte van het plotgebied liggen). Lezen/Schrijven byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Specificeert hoeveel balken en kolommen moeten overlappen in 2D-grafieken, als een percentage (van -100% tot 100%). - -100%: Maximale spatiëring (balken zijn volledig gescheiden). - 0%: Balken staan naast elkaar zonder overlap of spatiëring. - 100%: Maximale overlap (balken overlappen volledig). Deze eigenschap is Lezen/Schrijven byte.

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

Specificeert hoeveel balken en kolommen moeten overlappen in 2D-grafieken, als een percentage (van -100% tot 100%). - -100%: Maximale spatiëring (balken zijn volledig gescheiden). - 0%: Balken staan naast elkaar zonder overlap of spatiëring. - 100%: Maximale overlap (balken overlappen volledig). Deze eigenschap is Lezen/Schrijven byte.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Specificeert de grootte van de tweede part of balk van een part-in-part grafiek of een balk-in-part grafiek, als een percentage van de grootte van de eerste part (kan tussen 5 en 200 procent liggen). Lezen/Schrijven int.

**Retourneert:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Specificeert de grootte van de tweede part of balk van een part-in-part grafiek of een balk-in-part grafiek, als een percentage van de grootte van de eerste part (kan tussen 5 en 200 procent liggen). Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Specificeert hoe de bubbelgroottwaarden worden weergegeven op de bubbelgrafiek. Lezen/Schrijven [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retourneert:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Specificeert hoe de bubbelgroottwaarden worden weergegeven op de bubbelgrafiek. Lezen/Schrijven [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten zich in de tweede part of balk bevinden in een part-in-part of balk-in-part grafiek. Wordt samen met de eigenschap PieSplitBy gebruikt. Lezen/Schrijven double.

**Retourneert:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten zich in de tweede part of balk bevinden in een part-in-part of balk-in-part grafiek. Wordt samen met de eigenschap PieSplitBy gebruikt. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Specificeert hoe te bepalen welke gegevenspunten zich in de tweede part of balk bevinden in een part-in-part of balk-in-part grafiek. Lezen/Schrijven [PieSplitType](../../com.aspose.slides/piesplittype).

**Retourneert:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Specificeert hoe te bepalen welke gegevenspunten zich in de tweede part of balk bevinden in een part-in-part of balk-in-part grafiek. Lezen/Schrijven [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Specificeert dat elke gegevensmarkering in de serie een andere kleur heeft. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Specificeert dat elke gegevensmarkering in de serie een andere kleur heeft. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Waar als de grafiek serieslijnen heeft. Toegepast op gestapelde balk- en OfPie-grafieken. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Waar als de grafiek serieslijnen heeft. Toegepast op gestapelde balk- en OfPie-grafieken. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Specificeert HiLowLines-indeling. HiLowLines toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose grafiektype.

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lezen/Schrijven int.

**Retourneert:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

De aangepaste splitsingsinformatie voor een part-in-part of balk-in-part grafiek met een aangepaste splitsing. Bevat gegevenspunten die getekend moeten worden in de tweede part of balk in een part-in-part of balk-in-part grafiek. Alleen-lezen [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Retourneert:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

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