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

1) Zie samenvatting en opmerkingen voor de klasse ChartSeriesGroupCollection en de enum CombinableSeriesTypesGroup. 2) Een groep series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("series group properties"). "Series group properties" in de klasse ChartSeriesGroup is lezen/schrijven. Elke "series group properties" kan een alleen-lezen projectie hebben in de klasse ChartSeries.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Retourneert een type van deze seriesgroep. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of de series van deze groep op een secundaire as worden weergegeven. |
| [getSeries()](#getSeries--) | Retourneert een verzameling van series. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getUpDownBars()](#getUpDownBars--) | Biedt toegang tot up/down-balken van een lijn- of voorraadgrafiek. |
| [getGapWidth()](#getGapWidth--) | Specificeert de ruimte tussen balk- of kolom-clusters, als een percentage van de balk- of kolom-breedte. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specificeert de ruimte tussen balk- of kolom-clusters, als een percentage van de balk- of kolom-breedte. |
| [getGapDepth()](#getGapDepth--) | Retourneert of stelt de afstand in, als een percentage van de marker-breedte, tussen de dataseries in een 3D-grafiek. |
| [setGapDepth(int value)](#setGapDepth-int-) | Retourneert of stelt de afstand in, als een percentage van de marker-breedte, tussen de dataseries in een 3D-grafiek. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Haalt de hoek op of stelt de hoek in van het eerste taart- of donut-segment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Haalt de hoek op of stelt de hoek in van het eerste taart- of donut-segment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificeert de grootte van het gat in een donut-grafiek (kan tussen 0 en 90 procent van de plot-gebiedgrootte liggen). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specificeert de grootte van het gat in een donut-grafiek (kan tussen 0 en 90 procent van de plot-gebiedgrootte liggen). |
| [getOverlap()](#getOverlap--) | Specificeert hoeveel balken en kolommen moeten overlappen in 2-D-grafieken, als een percentage (van -100 % tot 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specificeert hoeveel balken en kolommen moeten overlappen in 2-D-grafieken, als een percentage (van -100 % tot 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificeert de grootte van de tweede taart of balk van een taart-in-taart-grafiek of een balk-in-taart-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specificeert de grootte van de tweede taart of balk van een taart-in-taart-grafiek of een balk-in-taart-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificeert hoe de bubbelaardewaarden worden weergegeven in de bubbelgrafiek. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specificeert hoe de bubbelaardewaarden worden weergegeven in de bubbelgrafiek. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificeert een waarde die wordt gebruikt om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-grafiek. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specificeert een waarde die wordt gebruikt om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-grafiek. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificeert hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-grafiek. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specificeert hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-grafiek. |
| [isColorVaried()](#isColorVaried--) | Specificeert dat elke datamarker in de serie een andere kleur heeft. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specificeert dat elke datamarker in de serie een andere kleur heeft. |
| [hasSeriesLines()](#hasSeriesLines--) | Waar als de grafiek serieslijnen heeft. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Waar als de grafiek serieslijnen heeft. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specificeert HiLowLines-opmaak. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste split-informatie voor een taart-in-taart- of balk-in-taart-grafiek met een aangepaste split. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retourneert de bovenliggende grafiek. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |
### getType() {#getType--}
```
public final int getType()
```

Retourneert een type van deze seriesgroep. Alleen-lezen [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Retourneert:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Geeft aan of de series van deze groep op een secundaire as worden weergegeven. Alleen-lezen boolean.

**Retourneert:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Retourneert een verzameling van series. Alleen-lezen [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

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

Biedt toegang tot up/down-balken van een lijn- of voorraadgrafiek. Alleen-lezen [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retourneert:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Specificeert de ruimte tussen balk- of kolom-clusters, als een percentage van de balk- of kolom-breedte. Lezen/schrijven int.

**Retourneert:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Specificeert de ruimte tussen balk- of kolom-clusters, als een percentage van de balk- of kolom-breedte. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Retourneert of stelt de afstand in, als een percentage van de marker-breedte, tussen de dataseries in een 3D-grafiek. Lezen/schrijven int.

**Retourneert:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Retourneert of stelt de afstand in, als een percentage van de marker-breedte, tussen de dataseries in een 3D-grafiek. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Haalt de hoek op of stelt de hoek in van het eerste taart- of donut-segment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/schrijven int.

**Retourneert:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Haalt de hoek op of stelt de hoek in van het eerste taart- of donut-segment, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Specificeert de grootte van het gat in een donut-grafiek (kan tussen 0 en 90 procent van de plot-gebiedgrootte liggen). Lezen/schrijven byte.

**Retourneert:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Specificeert de grootte van het gat in een donut-grafiek (kan tussen 0 en 90 procent van de plot-gebiedgrootte liggen). Lezen/schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Specificeert hoeveel balken en kolommen moeten overlappen in 2-D-grafieken, als een percentage (van -100 % tot 100 %). - -100 %: maximale spatiëring (balken zijn volledig gescheiden). - 0 %: balken staan naast elkaar zonder overlap of spatiëring. - 100 %: maximale overlap (balken overlappen volledig). Deze eigenschap is lezen/schrijven byte.

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

Specificeert hoeveel balken en kolommen moeten overlappen in 2-D-grafieken, als een percentage (van -100 % tot 100 %). - -100 %: maximale spatiëring (balken zijn volledig gescheiden). - 0 %: balken staan naast elkaar zonder overlap of spatiëring. - 100 %: maximale overlap (balken overlappen volledig). Deze eigenschap is lezen/schrijven byte.

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

Specificeert de grootte van de tweede taart of balk van een taart-in-taart-grafiek of een balk-in-taart-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lezen/schrijven int.

**Retourneert:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Specificeert de grootte van de tweede taart of balk van een taart-in-taart-grafiek of een balk-in-taart-grafiek, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Specificeert hoe de bubbelaardewaarden worden weergegeven in de bubbelgrafiek. Lezen/schrijven [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retourneert:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Specificeert hoe de bubbelaardewaarden worden weergegeven in de bubbelgrafiek. Lezen/schrijven [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Specificeert een waarde die wordt gebruikt om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-grafiek. Wordt samen met de eigenschap PieSplitBy gebruikt. Lezen/schrijven double.

**Retourneert:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Specificeert een waarde die wordt gebruikt om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-grafiek. Wordt samen met de eigenschap PieSplitBy gebruikt. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Specificeert hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-grafiek. Lezen/schrijven [PieSplitType](../../com.aspose.slides/piesplittype).

**Retourneert:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Specificeert hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-grafiek. Lezen/schrijven [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Specificeert dat elke datamarker in de serie een andere kleur heeft. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Specificeert dat elke datamarker in de serie een andere kleur heeft. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Waar als de grafiek serieslijnen heeft. Toegepast op gestapelde balk- en OfPie-grafieken. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Waar als de grafiek serieslijnen heeft. Toegepast op gestapelde balk- en OfPie-grafieken. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Specificeert HiLowLines-opmaak. HiLowLines wordt toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose grafiektypen.

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lezen/schrijven int.

**Retourneert:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Specificeert de schaalfactor voor de bubbelgrafiek (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

De aangepaste split-informatie voor een taart-in-taart- of balk-in-taart-grafiek met een aangepaste split. Bevat datapunten die in de tweede taart of balk moeten worden getekend. Alleen-lezen [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

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