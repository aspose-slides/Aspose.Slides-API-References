---
title: IDataLabelCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een reekslabels voor.
type: docs
url: /nl/com.aspose.slides/idatalabelcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Stelt een reekslabels voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het gegevenslabel op voor het gegevenspunt met de opgegeven index. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Retourneert het standaardformaat van alle gegevenslabels in de collectie. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Stelt het opmaakformaat van de leidende lijnen van gegevenslabels voor. |
| [isVisible()](#isVisible--) | False betekent dat het gegevenslabel standaard niet zichtbaar is (en dus zijn alle Show*-vlaggen (ShowValue, ...) van de eigenschap DefaultDataLabelFormat false). |
| [hide()](#hide--) | Verberg het gegevenslabel standaard door alle Show*-vlaggen (ShowValue, ...) van de eigenschap DefaultDataLabelFormat op false te zetten. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Haalt het aantal zichtbare gegevenslabels in de collectie op. |
| [getCount()](#getCount--) | Haalt het aantal alle gegevenslabels in de collectie op. |
| [getParentSeries()](#getParentSeries--) | Retourneert de bovenliggende diagramreeks. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Retourneert een index van het opgegeven DataLabel in de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Haalt het gegevenslabel op voor het gegevenspunt met de opgegeven index.

--------------------

Alternatieve manier om toegang te krijgen tot het gegevenslabel is: - getSeries().getDataPoints().get_Item(i).getLabel() - label-eigenschappen beheren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Retourneert het standaardformaat van alle gegevenslabels in de collectie. Alleen-lezen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retourneert:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Stelt het opmaakformaat van de leidende lijnen van gegevenslabels voor. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

**Retourneert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False betekent dat het gegevenslabel standaard niet zichtbaar is (en dus zijn alle Show*-vlaggen (ShowValue, ...) van de eigenschap DefaultDataLabelFormat false). Alleen-lezen boolean.

--------------------

Als het gegevenslabel standaard zichtbaar is, kun je het standaard verborgen maken met de Hide()-methode. Maar als het gegevenslabel standaard niet zichtbaar is (IsVisible is false), kun je het gegevenslabel "standaard zichtbaar" maken door de Show*-vlaggen (ShowValue, ...) van de eigenschap DefaultDataLabelFormat op true te zetten.

**Retourneert:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Verberg het gegevenslabel standaard door alle Show*-vlaggen (ShowValue, ...) van de eigenschap DefaultDataLabelFormat op false te zetten. IsVisible zal daarna false zijn.

--------------------

Als het gegevenslabel standaard niet zichtbaar is (IsVisible is false), kun je het gegevenslabel "standaard zichtbaar" maken door de Show*-vlaggen (ShowValue, ...) van de eigenschap DefaultDataLabelFormat op true te zetten.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Haalt het aantal zichtbare gegevenslabels in de collectie op. Alleen-lezen int.

**Retourneert:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het aantal alle gegevenslabels in de collectie op. Alleen-lezen int.

**Retourneert:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Retourneert de bovenliggende diagramreeks. Alleen-lezen [IChartSeries](../../com.aspose.slides/ichartseries).

**Retourneert:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Retourneert een index van het opgegeven DataLabel in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel om te vinden. |

**Retourneert:**
int - Index van een DataLabel of -1 als DataLabel niet uit deze collectie komt.