---
title: DataLabelCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt labels van een serie voor.
type: docs
url: /nl/com.aspose.slides/datalabelcollection/
---
**Overerving:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Stelt labels voor een serie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChart()](#getChart--) | Retourneert de bovenliggende chart. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [isVisible()](#isVisible--) | False betekent dat het datalabel standaard niet zichtbaar is (en dus alle Show\*-flags (ShowValue, …) van de DefaultDataLabelFormat-eigenschap false zijn). |
| [hide()](#hide--) | Maakt het datalabel standaard verborgen door alle Show\*-flags (ShowValue, …) van de DefaultDataLabelFormat-eigenschap op false te zetten. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Haalt het aantal zichtbare datalabels in de collectie op. |
| [getCount()](#getCount--) | Haalt het totale aantal datalabels in de collectie op. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Haalt het standaard datalabel-formaat op. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Vertegenwoordigt het opmaakformaat van de leider-lijnen van datalabels. |
| [getParentSeries()](#getParentSeries--) | Haalt de bovenliggende serie op. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Retourneert een index van het opgegeven DataLabel in de collectie. |
| [get_Item(int index)](#get-Item-int-) | Haalt het datalabel op voor het datapunt met de opgegeven index. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende slide van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de bovenliggende chart. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retourneert:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Een java.util.Iterator voor de volledige collectie.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False betekent dat het datalabel standaard niet zichtbaar is (en dus alle Show\*-flags (ShowValue, …) van de DefaultDataLabelFormat-eigenschap false zijn). Alleen-lezen boolean.

--------------------

Als het datalabel standaard zichtbaar is, kun je het standaard verborgen maken met de Hide()-methode. Maar als het datalabel standaard niet zichtbaar is (IsVisible is false), kun je het datalabel “standaard zichtbaar” maken door de Show\*-flags (ShowValue, …) van de DefaultDataLabelFormat-eigenschap op true te zetten.

**Retourneert:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Maakt het datalabel standaard verborgen door alle Show\*-flags (ShowValue, …) van de DefaultDataLabelFormat-eigenschap op false te zetten. IsVisible zal daarna false zijn.

--------------------

Als het datalabel standaard niet zichtbaar is (IsVisible is false), kun je het datalabel “standaard zichtbaar” maken door de Show\*-flags (ShowValue, …) van de DefaultDataLabelFormat-eigenschap op true te zetten.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Haalt het aantal zichtbare datalabels in de collectie op. Alleen-lezen int.

**Retourneert:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Haalt het totale aantal datalabels in de collectie op. Alleen-lezen int.

**Retourneert:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Haalt het standaard datalabel-formaat op. Alleen-lezen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retourneert:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Vertegenwoordigt het opmaakformaat van de leider-lijnen van datalabels. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Haalt de bovenliggende serie op. Alleen-lezen [IChartSeries](../../com.aspose.slides/ichartseries).

**Retourneert:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Retourneert een index van het opgegeven DataLabel in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel om te vinden. |

**Retourneert:**
int - Index van een DataLabel of -1 als DataLabel niet uit deze collectie komt.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Haalt het datalabel op voor het datapunt met de opgegeven index.

--------------------

Alternatieve manier om een datalabel te benaderen is: - series.getDataPoints().get\_Item(i).getLabel() - beheer label-eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende slide van een FillFormat. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een FillFormat. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)