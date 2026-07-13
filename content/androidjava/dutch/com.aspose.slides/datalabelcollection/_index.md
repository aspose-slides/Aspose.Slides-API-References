---
title: DataLabelCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt labels van een serie voor.
type: docs
url: /nl/com.aspose.slides/datalabelcollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle Geïmplementeerde Interfaces:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Stelt labels van een series voor.
## Methoden

| Method | Description |
| --- | --- |
| [getChart()](#getChart--) | Retourneert de bovenliggende chart. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereren. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [isVisible()](#isVisible--) | False betekent dat de data label standaard niet zichtbaar is (en dus alle Show*-vlaggen (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap onwaar zijn). |
| [hide()](#hide--) | Maak de data label standaard verborgen door alle Show*-vlaggen (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap op onwaar te zetten. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Haalt het aantal zichtbare data labels op in de collectie. |
| [getCount()](#getCount--) | Haalt het totale aantal data labels op in de collectie. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Haalt het standaard data label-formaat op. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Stelt het formaat van leader-lines van data labels voor. |
| [getParentSeries()](#getParentSeries--) | Haalt de bovenliggende series op. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Retourneert een index van de opgegeven DataLabel in de collectie. |
| [get_Item(int index)](#get-Item-int-) | Haalt het data label op voor het datapunt met de opgegeven index. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende slide van een FillFormat. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentation van een FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retourneert de bovenliggende chart. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retour:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Retourneert een enumerator die door de collectie itereren.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False betekent dat de data label standaard niet zichtbaar is (en dus alle Show*-vlaggen (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap onwaar zijn). Alleen-lezen boolean.

--------------------

Als de data label standaard zichtbaar is, kun je deze standaard verbergen met de Hide()-methode. Maar als de data label standaard niet zichtbaar is (IsVisible is false), kun je de data label “standaard zichtbaar” maken door de Show*-vlaggen (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap op waar te zetten.

**Retour:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Maak de data label standaard verborgen door alle Show*-vlaggen (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap op onwaar te zetten. IsVisible zal daarna false zijn.

--------------------

Als de data label standaard niet zichtbaar is (IsVisible is false), kun je de data label “standaard zichtbaar” maken door de Show*-vlaggen (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap op waar te zetten.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Haalt het aantal zichtbare data labels op in de collectie. Alleen-lezen int.

**Retour:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Haalt het totale aantal data labels op in de collectie. Alleen-lezen int.

**Retour:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Haalt het standaard data label-formaat op. Alleen-lezen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retour:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Stelt het formaat van leader-lines van data labels voor. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Haalt de bovenliggende series op. Alleen-lezen [IChartSeries](../../com.aspose.slides/ichartseries).

**Retour:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Retourneert een index van de opgegeven DataLabel in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel to find. |

**Retour:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Haalt het data label op voor het datapunt met de opgegeven index.

--------------------

Alternatieve manier om het data label te benaderen is: - series.getDataPoints().get_Item(i).getLabel() - beheer labeleigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende slide van een FillFormat. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retour:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentation van een FillFormat. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)