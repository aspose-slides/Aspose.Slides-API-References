---
title: DataLabelCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een reekslabels voor.
type: docs
url: /nl/com.aspose.slides/datalabelcollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Stelt een reekslabels voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChart()](#getChart--) | Geeft het bovenliggende diagram terug. |
| [iterator()](#iterator--) | Geeft een enumerator die door de collectie iterereert terug. |
| [iteratorJava()](#iteratorJava--) | Geeft een java-iterator voor de volledige collectie terug. |
| [isVisible()](#isVisible--) | False betekent dat gegevenslabel standaard niet zichtbaar is (en dus zijn alle Show*-flags (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap false). |
| [hide()](#hide--) | Maak het gegevenslabel standaard verborgen door alle Show*-flags (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap op false te zetten. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Haalt het aantal zichtbare gegevenslabels in de collectie op. |
| [getCount()](#getCount--) | Haalt het totale aantal gegevenslabels in de collectie op. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Haalt het standaard gegevenslabelopmaak op. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Stelt het opmaak van leidende lijnen van gegevenslabels voor. |
| [getParentSeries()](#getParentSeries--) | Haalt de bovenliggende serie op. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Geeft de index van het opgegeven DataLabel in de collectie terug. |
| [get_Item(int index)](#get-Item-int-) | Haalt het gegevenslabel op voor het gegevenspunt met de opgegeven index. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Haalt het standaard vormtype op voor gegevenslabels of stelt het in. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Haalt het standaard vormtype op voor gegevenslabels of stelt het in. |
| [getSlide()](#getSlide--) | Geeft de bovenliggende dia van een FillFormat terug. |
| [getPresentation()](#getPresentation--) | Geeft de bovenliggende presentatie van een FillFormat terug. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Geeft het bovenliggende diagram terug. Alleen-lezen [IChart](../../com.aspose.slides/ichart).

**Retourneert:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Geeft een enumerator die door de collectie iterereert terug.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel} - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Geeft een java-iterator voor de volledige collectie terug.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel} - Een java.util.Iterator voor de volledige collectie.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False betekent dat gegevenslabel standaard niet zichtbaar is (en dus zijn alle Show*-flags (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap false). Alleen-lezen boolean.

--------------------

Als het gegevenslabel standaard zichtbaar is, kun je het standaard verborgen maken met de Hide()-methode. Maar als het gegevenslabel standaard niet zichtbaar is (IsVisible is false), kun je het gegevenslabel "standaard zichtbaar" maken door de Show*-flags (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap op true te zetten.

**Retourneert:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Maak het gegevenslabel standaard verborgen door alle Show*-flags (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap op false te zetten. IsVisible zal daarna false zijn.

--------------------

Als het gegevenslabel standaard niet zichtbaar is (IsVisible is false), kun je het gegevenslabel "standaard zichtbaar" maken door de Show*-flags (ShowValue, ...) van de DefaultDataLabelFormat-eigenschap op true te zetten.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Haalt het aantal zichtbare gegevenslabels in de collectie op. Alleen-lezen int.

**Retourneert:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Haalt het totale aantal gegevenslabels in de collectie op. Alleen-lezen int.

**Retourneert:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Haalt het standaard gegevenslabelopmaak op. Alleen-lezen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retourneert:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Stelt het opmaak van leidende lijnen van gegevenslabels voor. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

Geeft de index van het opgegeven DataLabel in de collectie terug.

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

Haalt het gegevenslabel op voor het gegevenspunt met de opgegeven index.

--------------------

Alternatieve manier om toegang te krijgen tot het gegevenslabel is:
- series.getDataPoints().get_Item(i).getLabel()
- label-eigenschappen beheren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

Haalt het standaard vormtype op voor gegevenslabels of stelt het in. Retourneert [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) als er geen vorm is gedefinieerd.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Stel het vormtype van alle gegevenslabels in de eerste serie in op Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Het instellen van deze eigenschap stelt ook de  IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) eigenschap voor alle gegevenslabels in de collectie in op dezelfde waarde.

**Retourneert:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

Haalt het standaard vormtype op voor gegevenslabels of stelt het in. Retourneert [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) als er geen vorm is gedefinieerd.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Stel het vormtype van alle gegevenslabels in de eerste serie in op Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Het instellen van deze eigenschap stelt ook de  IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) eigenschap voor alle gegevenslabels in de collectie in op dezelfde waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Geeft de bovenliggende dia van een FillFormat terug. Alleen-lezen [BaseSlide](../../com.aspose.slides/baseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Geeft de bovenliggende presentatie van een FillFormat terug. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)