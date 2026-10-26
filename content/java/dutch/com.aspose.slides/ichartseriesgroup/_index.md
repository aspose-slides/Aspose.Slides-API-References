---
title: IChartSeriesGroup
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een groep van series voor.
type: docs
url: /nl/com.aspose.slides/ichartseriesgroup/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Stelt een groep van series voor.

--------------------

1) Zie de samenvatting en opmerkingen voor de class ChartSeriesGroupCollection en de enum CombinableSeriesTypesGroup. 2) Een groep series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep (“seriegroep-eigenschappen”). “Seriegroep-eigenschappen” in de class ChartSeriesGroup zijn lees-/schrijf. Elke “seriegroep-eigenschappen” kan een alleen-lezen projectie hebben in de class ChartSeries.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert een type van deze seriegroep. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of series van deze groep op een secundaire as worden geplot. |
| [getSeries()](#getSeries--) | Retourneert een alleen-lees collectie van diagram-series. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getUpDownBars()](#getUpDownBars--) | Biedt toegang tot op/ neer-balken van een lijndiagram of voorraad-diagram. |
| [getGapWidth()](#getGapWidth--) | Specificeert de ruimte tussen balk- of kolom-clusters, als een percentage van de balk- of kolombreedte. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specificeert de ruimte tussen balk- of kolom-clusters, als een percentage van de balk- of kolombreedte. |
| [getGapDepth()](#getGapDepth--) | Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensseries in een 3D-diagram. |
| [setGapDepth(int value)](#setGapDepth-int-) | Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensseries in een 3D-diagram. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Haalt op of stelt de hoek in van het eerste taart- of donut-segment, in graden (kloksgewijs vanaf boven, van 0 tot 360 graden). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Haalt op of stelt de hoek in van het eerste taart- of donut-segment, in graden (kloksgewijs vanaf boven, van 0 tot 360 graden). |
| [isColorVaried()](#isColorVaried--) | Specificeert dat elke datamarker in de serie een andere kleur heeft. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specificeert dat elke datamarker in de serie een andere kleur heeft. |
| [hasSeriesLines()](#hasSeriesLines--) | Waar als het diagram serielijnen heeft. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Waar als het diagram serielijnen heeft. |
| [getOverlap()](#getOverlap--) | Specificeert hoeveel balken en kolommen overlappen op 2-D diagrammen, als een percentage (van -100% tot 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specificeert hoeveel balken en kolommen overlappen op 2-D diagrammen, als een percentage (van -100% tot 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificeert de grootte van de tweede taart of balk van een taart-in-taart diagram of een balk-in-taart diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specificeert de grootte van de tweede taart of balk van een taart-in-taart diagram of een balk-in-taart diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten in de tweede taart of balk van een taart-in-taart of balk-in-taart diagram staan. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten in de tweede taart of balk van een taart-in-taart of balk-in-taart diagram staan. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificeert hoe bepaald wordt welke gegevenspunten in de tweede taart of balk van een taart-in-taart of balk-in-taart diagram staan. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specificeert hoe bepaald wordt welke gegevenspunten in de tweede taart of balk van een taart-in-taart of balk-in-taart diagram staan. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste splitsingsinformatie voor een taart-in-taart of balk-in-taart diagram met een aangepaste splitsing. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specificeert het HiLowLines-formaat. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificeert hoe de bubbel-groottewaarden worden weergegeven op het bubbel-diagram. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specificeert hoe de bubbel-groottewaarden worden weergegeven op het bubbel-diagram. |

### getType() {#getType--}
```
public abstract int getType()
```

Retourneert een type van deze seriegroep. Alleen-lezen [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Retour:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Geeft aan of series van deze groep op een secundaire as worden geplot. Alleen-lezen boolean.

**Retour:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Retourneert een alleen-lees collectie van diagram-series. Alleen-lezen [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Retour:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Biedt toegang tot op/ neer-balken van een lijn- of voorraad-diagram. Alleen-lezen [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retour:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Specificeert de ruimte tussen balk- of kolom-clusters, als een percentage van de balk- of kolombreedte. Lees-schrijf int.

**Retour:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Specificeert de ruimte tussen balk- of kolom-clusters, als een percentage van de balk- of kolombreedte. Lees-schrijf int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensseries in een 3D-diagram. Lees-schrijf int.

**Retour:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Retourneert of stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensseries in een 3D-diagram. Lees-schrijf int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Haalt op of stelt de hoek in van het eerste taart- of donut-segment, in graden (kloksgewijs vanaf boven, van 0 tot 360 graden). Lees-schrijf int.

**Retour:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Haalt op of stelt de hoek in van het eerste taart- of donut-segment, in graden (kloksgewijs vanaf boven, van 0 tot 360 graden). Lees-schrijf int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Specificeert dat elke datamarker in de serie een andere kleur heeft. Lees-schrijf boolean.

**Retour:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Specificeert dat elke datamarker in de serie een andere kleur heeft. Lees-schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Waar als het diagram serielijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Lees-schrijf boolean.

**Retour:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Waar als het diagram serielijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Lees-schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Specificeert hoeveel balken en kolommen overlappen op 2-D diagrammen, als een percentage (van -100% tot 100%). - -100%: maximale spatiëring (balken zijn volledig gescheiden). - 0%: balken staan naast elkaar zonder overlap of spatiëring. - 100%: maximale overlap (balken overlappen volledig). Deze eigenschap is lees-schrijf byte.

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


**Retour:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Specificeert hoeveel balken en kolommen overlappen op 2-D diagrammen, als een percentage (van -100% tot 100%). - -100%: maximale spatiëring (balken zijn volledig gescheiden). - 0%: balken staan naast elkaar zonder overlap of spatiëring. - 100%: maximale overlap (balken overlappen volledig). Deze eigenschap is lees-schrijf byte.

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
public abstract int getSecondPieSize()
```

Specificeert de grootte van de tweede taart of balk van een taart-in-taart diagram of een balk-in-taart diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lees-schrijf int.

**Retour:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Specificeert de grootte van de tweede taart of balk van een taart-in-taart diagram of een balk-in-taart diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lees-schrijf int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten in de tweede taart of balk van een taart-in-taart of balk-in-taart diagram staan. Wordt samen met de eigenschap PieSplitBy gebruikt. Lees-schrijf double.

**Retour:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Specificeert een waarde die gebruikt wordt om te bepalen welke gegevenspunten in de tweede taart of balk van een taart-in-taart of balk-in-taart diagram staan. Wordt samen met de eigenschap PieSplitBy gebruikt. Lees-schrijf double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specificeert hoe bepaald wordt welke gegevenspunten in de tweede taart of balk van een taart-in-taart of balk-in-taart diagram staan. Lees-schrijf [PieSplitType](../../com.aspose.slides/piesplittype).

**Retour:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Specificeert hoe bepaald wordt welke gegevenspunten in de tweede taart of balk van een taart-in-taart of balk-in-taart diagram staan. Lees-schrijf [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

De aangepaste splitsingsinformatie voor een taart-in-taart of balk-in-taart diagram met een aangepaste splitsing. Bevat gegevenspunten die in de tweede taart of balk van een taart-in-taart of balk-in-taart diagram getekend moeten worden. Alleen-lezen [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Retour:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). Lees-schrijf byte.

**Retour:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). Lees-schrijf byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lees-schrijf int.

**Retour:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lees-schrijf int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Specificeert het HiLowLines-formaat. HiLowLines wordt toegepast bij HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose diagramtypen.

**Retour:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Specificeert hoe de bubbel-groottewaarden worden weergegeven op het bubbel-diagram. Lees-schrijf [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retour:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Specificeert hoe de bubbel-groottewaarden worden weergegeven op het bubbel-diagram. Lees-schrijf [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |