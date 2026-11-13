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

1) Bekijk de samenvatting en opmerkingen voor de klasse ChartSeriesGroupCollection en de enum CombinableSeriesTypesGroup. 2) Een groep van series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("series group properties"). "Series group properties" in de klasse ChartSeriesGroup is lezen/schrijven. Elke van de "series group properties" kan een alleen-lezen projectie hebben in de klasse ChartSeries.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Geeft een type van deze series-groep terug. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Geeft aan of series van deze groep op een secundaire as worden geplot. |
| [getSeries()](#getSeries--) | Geeft een alleen-lezen collectie van diagramseries terug. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getUpDownBars()](#getUpDownBars--) | Biedt toegang tot op/naar-boven staafjes van een Lijn- of Koers-diagram. |
| [getGapWidth()](#getGapWidth--) | Haalt op of stelt de ruimte tussen staaf- of kolomclusters in, als een percentage van de breedte van de staaf of kolom. |
| [setGapWidth(int value)](#setGapWidth-int-) | Haalt op of stelt de ruimte tussen staaf- of kolomclusters in, als een percentage van de breedte van de staaf of kolom. |
| [getGapDepth()](#getGapDepth--) | Haalt op of stelt de afstand tussen gegevensseries in een 3D-diagram in, als een percentage van de markerbreedte. |
| [setGapDepth(int value)](#setGapDepth-int-) | Haalt op of stelt de afstand tussen gegevensseries in een 3D-diagram in, als een percentage van de markerbreedte. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Haalt op of stelt de hoek van het eerste taart- of donut-diagramsegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Haalt op of stelt de hoek van het eerste taart- of donut-diagramsegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). |
| [isColorVaried()](#isColorVaried--) | Specificeert dat elke gegevensmarker in de serie een andere kleur heeft. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specificeert dat elke gegevensmarker in de serie een andere kleur heeft. |
| [hasSeriesLines()](#hasSeriesLines--) | Waar als het diagram serielijnen heeft. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Waar als het diagram serielijnen heeft. |
| [getOverlap()](#getOverlap--) | Specificeert hoeveel staven en kolommen elkaar overlappen in 2-D-diagrammen, als een percentage (van -100% tot 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specificeert hoeveel staven en kolommen elkaar overlappen in 2-D-diagrammen, als een percentage (van -100% tot 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specificeert de grootte van de tweede taart of staaf van een taart-van-taart-diagram of een staaf-van-taart-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specificeert de grootte van de tweede taart of staaf van een taart-van-taart-diagram of een staaf-van-taart-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-van-taart- of staaf-van-taart-diagram. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-van-taart- of staaf-van-taart-diagram. |
| [getPieSplitBy()](#getPieSplitBy--) | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-van-taart- of staaf-van-taart-diagram. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-van-taart- of staaf-van-taart-diagram. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | De aangepaste splitsingsinformatie voor een taart-van-taart- of staaf-van-taart-diagram met een aangepaste splitsing. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specificeert de grootte van het gat in een donut-diagram (kan liggen tussen 10 en 90 procent van de grootte van het plotgebied). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specificeert de grootte van het gat in een donut-diagram (kan liggen tussen 10 en 90 procent van de grootte van het plotgebied). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specificeert de schaalfactor voor het bubbel-diagram (kan liggen tussen 0 en 300 procent van de standaardgrootte). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specificeert de schaalfactor voor het bubbel-diagram (kan liggen tussen 0 en 300 procent van de standaardgrootte). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specificeert het HiLowLines-formaat. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specificeert hoe de bubbelgrootte-waarden worden weergegeven in het bubbel-diagram. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specificeert hoe de bubbelgrootte-waarden worden weergegeven in het bubbel-diagram. |

### getType() {#getType--}
```
public abstract int getType()
```

Geeft een type van deze series-groep terug. Alleen-lezen [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

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

Geeft een alleen-lezen collectie van diagramseries terug. Alleen-lezen [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

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

Biedt toegang tot op/naar-boven staafjes van een Lijn- of Koers-diagram. Alleen-lezen [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retour:**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Haalt op of stelt de ruimte tussen staaf- of kolomclusters in, als een percentage van de breedte van de staaf of kolom. De waarde moet tussen 0 en 500 liggen. Lezen/schrijven int.

--------------------

Deze eigenschap is van toepassing op series van de volgende typen: alle staaf- en kolomsubtypes, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Retour:**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Haalt op of stelt de ruimte tussen staaf- of kolomclusters in, als een percentage van de breedte van de staaf of kolom. De waarde moet tussen 0 en 500 liggen. Lezen/schrijven int.

--------------------

Deze eigenschap is van toepassing op series van de volgende typen: alle staaf- en kolomsubtypes, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Haalt op of stelt de afstand tussen gegevensseries in een 3D-diagram in, als een percentage van de markerbreedte. De waarde moet tussen 0 en 500 liggen. Lezen/schrijven int.

--------------------

Deze eigenschap is van toepassing op series van de volgende typen: 3D staaf- en kolomsubtypes, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Retour:**  
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Haalt op of stelt de afstand tussen gegevensseries in een 3D-diagram in, als een percentage van de markerbreedte. De waarde moet tussen 0 en 500 liggen. Lezen/schrijven int.

--------------------

Deze eigenschap is van toepassing op series van de volgende typen: 3D staaf- en kolomsubtypes, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Haalt op of stelt de hoek van het eerste taart- of donut-diagramsegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/schrijven int.

**Retour:**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Haalt op of stelt de hoek van het eerste taart- of donut-diagramsegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lezen/schrijven int.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Specificeert dat elke gegevensmarker in de serie een andere kleur heeft. Lezen/schrijven boolean.

**Retour:**  
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Specificeert dat elke gegevensmarker in de serie een andere kleur heeft. Lezen/schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Waar als het diagram serielijnen heeft. Toegepast op gestapelde staaf- en OfPie-diagrammen. Lezen/schrijven boolean.

**Retour:**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Waar als het diagram serielijnen heeft. Toegepast op gestapelde staaf- en OfPie-diagrammen. Lezen/schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Specificeert hoeveel staven en kolommen elkaar overlappen in 2-D-diagrammen, als een percentage (van -100% tot 100%). - -100%: maximale afstand (staven zijn volledig gescheiden). - 0%: staven staan zij aan zij zonder overlap of ruimte. - 100%: maximale overlap (staven overlappen volledig). Deze eigenschap is lezen/schrijven byte.

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

Specificeert hoeveel staven en kolommen elkaar overlappen in 2-D-diagrammen, als een percentage (van -100% tot 100%). - -100%: maximale afstand (staven zijn volledig gescheiden). - 0%: staven staan zij aan zij zonder overlap of ruimte. - 100%: maximale overlap (staven overlappen volledig). Deze eigenschap is lezen/schrijven byte.

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

Specificeert de grootte van de tweede taart of staaf van een taart-van-taart-diagram of een staaf-van-taart-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lezen/schrijven int.

**Retour:**  
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Specificeert de grootte van de tweede taart of staaf van een taart-van-taart-diagram of een staaf-van-taart-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lezen/schrijven int.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-van-taart- of staaf-van-taart-diagram. Wordt samen met de eigenschap PieSplitBy gebruikt. Lezen/schrijven double.

**Retour:**  
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Specificeert een waarde die gebruikt moet worden om te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-van-taart- of staaf-van-taart-diagram. Wordt samen met de eigenschap PieSplitBy gebruikt. Lezen/schrijven double.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-van-taart- of staaf-van-taart-diagram. Lezen/schrijven [PieSplitType](../../com.aspose.slides/piesplittype).

**Retour:**  
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Specificeert hoe te bepalen welke gegevenspunten zich in de tweede taart of staaf bevinden in een taart-van-taart- of staaf-van-taart-diagram. Lezen/schrijven [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

De aangepaste splitsingsinformatie voor een taart-van-taart- of staaf-van-taart-diagram met een aangepaste splitsing. Bevat gegevenspunten die moeten worden getekend in de tweede taart of staaf in een taart-van-taart- of staaf-van-taart-diagram. Alleen-lezen [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Retour:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Specificeert de grootte van het gat in een donut-diagram (kan liggen tussen 10 en 90 procent van de grootte van het plotgebied). Lezen/schrijven byte.

**Retour:**  
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Specificeert de grootte van het gat in een donut-diagram (kan liggen tussen 10 en 90 procent van de grootte van het plotgebied). Lezen/schrijven byte.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Specificeert de schaalfactor voor het bubbel-diagram (kan liggen tussen 0 en 300 procent van de standaardgrootte). Lezen/schrijven int.

**Retour:**  
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Specificeert de schaalfactor voor het bubbel-diagram (kan liggen tussen 0 en 300 procent van de standaardgrootte). Lezen/schrijven int.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Specificeert het HiLowLines-formaat. HiLowLines toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose diagramtypen.

**Retour:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Specificeert hoe de bubbelgrootte-waarden worden weergegeven in het bubbel-diagram. Lezen/schrijven [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retour:**  
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Specificeert hoe de bubbelgrootte-waarden worden weergegeven in het bubbel-diagram. Lezen/schrijven [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |