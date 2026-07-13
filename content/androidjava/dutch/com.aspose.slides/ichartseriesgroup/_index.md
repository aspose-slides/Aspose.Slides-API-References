---
title: IChartSeriesGroup
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een groep series voor.
type: docs
url: /nl/com.aspose.slides/ichartseriesgroup/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Stelt een groep series voor.

--------------------

1) Zie samenvatting en opmerkingen voor de klasse ChartSeriesGroupCollection en de enum CombinableSeriesTypesGroup. 2) Een groep series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep (“series group properties”). “Series group properties” in de klasse ChartSeriesGroup is lees-schrijf. Elk van de “series group properties” kan een alleen-lezen projectie hebben in de klasse ChartSeries.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert een type van deze series-groep. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of series van deze groep worden weergegeven op een secundaire as. |
| [getSeries()](#getSeries--) | Retourneert een alleen-lezen verzameling van grafiek-series. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getUpDownBars()](#getUpDownBars--) | Biedt toegang tot up/down-balken van een Line- of Stock-diagram. |
| [getGapWidth()](#getGapWidth--) | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de balk- of kolombreedte. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de balk- of kolombreedte. |
| [getGapDepth()](#getGapDepth--) | Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de dataseries in een 3D-diagram. |
| [setGapDepth(int value)](#setGapDepth-int-) | Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de dataseries in een 3D-diagram. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Haalt op of stelt de hoek in van het eerste taart- of donut-diagramsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Haalt op of stelt de hoek in van het eerste taart- of donut-diagramsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [isColorVaried()](#isColorVaried--) | Specificeert dat elke datamarker in de serie een andere kleur heeft. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specificeert dat elke datamarker in de serie een andere kleur heeft. |
| [hasSeriesLines()](#hasSeriesLines--) | True als diagram series-lijnen heeft. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True als diagram series-lijnen heeft. |
| [getOverlap()](#getOverlap--) | Specificeert hoeveel balken en kolommen overlappen op 2-D-diagrammen, als percentage (van -100% tot 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specificeert hoeveel balken en kolommen overlappen op 2-D-diagrammen, als percentage (van -100% tot 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificeert de grootte van de tweede taart of balk van een pie-of-pie-diagram of een bar-of-pie-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specificeert de grootte van de tweede taart of balk van een pie-of-pie-diagram of een bar-of-pie-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-diagram. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-diagram. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-diagram. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste splitsingsinformatie voor een pie-of-pie- of bar-of-pie-diagram met een aangepaste splitsing. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specificeert het HiLowLines-formaat. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificeert hoe de bubbelgrootte-waarden worden weergegeven op het bubbel-diagram. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specificeert hoe de bubbelgrootte-waarden worden weergegeven op het bubbel-diagram. |

### getType() {#getType--}
```
public abstract int getType()
```

Retourneert een type van deze series-groep. Alleen-lezen [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Retourneert:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Geeft aan of series van deze groep worden weergegeven op een secundaire as. Alleen-lezen boolean.

**Retourneert:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Retourneert een alleen-lezen verzameling van grafiek-series. Alleen-lezen [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Retourneert:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
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
public abstract IUpDownBarsManager getUpDownBars()
```

Biedt toegang tot up/down-balken van een Line- of Stock-diagram. Alleen-lezen [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retourneert:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de balk- of kolombreedte. Lees-schrijf int.

**Retourneert:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de balk- of kolombreedte. Lees-schrijf int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de dataseries in een 3D-diagram. Lees-schrijf int.

**Retourneert:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de dataseries in een 3D-diagram. Lees-schrijf int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Haalt op of stelt de hoek in van het eerste taart- of donut-diagramsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lees-schrijf int.

**Retourneert:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Haalt op of stelt de hoek in van het eerste taart- of donut-diagramsegment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lees-schrijf int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Specificeert dat elke datamarker in de serie een andere kleur heeft. Lees-schrijf boolean.

**Retourneert:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Specificeert dat elke datamarker in de serie een andere kleur heeft. Lees-schrijf boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

True als diagram series-lijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Lees-schrijf boolean.

**Retourneert:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

True als diagram series-lijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Lees-schrijf boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Specificeert hoeveel balken en kolommen overlappen op 2-D-diagrammen, als percentage (van -100% tot 100%). - -100%: maximale afstand (balken zijn volledig gescheiden). - 0%: balken worden naast elkaar geplaatst zonder overlap of afstand. - 100%: maximale overlap (balken overlappen volledig). Deze eigenschap is lees-schrijf byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Stel overlapping in op 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Specificeert hoeveel balken en kolommen overlappen op 2-D-diagrammen, als percentage (van -100% tot 100%). - -100%: maximale afstand (balken zijn volledig gescheiden). - 0%: balken worden naast elkaar geplaatst zonder overlap of afstand. - 100%: maximale overlap (balken overlappen volledig). Deze eigenschap is lees-schrijf byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Stel overlapping in op 55%
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
public abstract int getSecondPieSize()
```

Specificeert de grootte van de tweede taart of balk van een pie-of-pie-diagram of een bar-of-pie-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lees-schrijf int.

**Retourneert:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Specificeert de grootte van de tweede taart of balk van een pie-of-pie-diagram of een bar-of-pie-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lees-schrijf int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-diagram. Wordt gebruikt samen met de eigenschap PieSplitBy. Lees-schrijf double.

**Retourneert:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-diagram. Wordt gebruikt samen met de eigenschap PieSplitBy. Lees-schrijf double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-diagram. Lees-schrijf [PieSplitType](../../com.aspose.slides/piesplittype).

**Retourneert:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of balk bevinden in een pie-of-pie- of bar-of-pie-diagram. Lees-schrijf [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

De aangepaste splitsingsinformatie voor een pie-of-pie- of bar-of-pie-diagram met een aangepaste splitsing. Bevat gegevenspunten die in de tweede taart of balk moeten worden getekend. Alleen-lezen [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Retourneert:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). Lees-schrijf byte.

**Retourneert:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). Lees-schrijf byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lees-schrijf int.

**Retourneert:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lees-schrijf int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Specificeert het HiLowLines-formaat. HiLowLines wordt toegepast met de diagramtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose.

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Specificeert hoe de bubbelgrootte-waarden worden weergegeven op het bubbel-diagram. Lees-schrijf [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retourneert:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Specificeert hoe de bubbelgrootte-waarden worden weergegeven op het bubbel-diagram. Lees-schrijf [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |