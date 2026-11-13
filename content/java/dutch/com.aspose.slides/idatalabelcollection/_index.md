---
title: IDataLabelCollection
second_title: Aspose.Slides voor Java API-referentie
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
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Stelt het opmaak van de begeleidende lijnen van gegevenslabels voor. |
| [isVisible()](#isVisible--) | False betekent dat het gegevenslabel standaard niet zichtbaar is (en dus zijn alle Show*-flags (ShowValue, ...) van de eigenschap DefaultDataLabelFormat onwaar). |
| [hide()](#hide--) | Maak het gegevenslabel standaard verborgen door alle Show*-flags (ShowValue, ...) van de eigenschap DefaultDataLabelFormat op onwaar te zetten. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Haalt het aantal zichtbare gegevenslabels op in de collectie. |
| [getCount()](#getCount--) | Haalt het totale aantal gegevenslabels op in de collectie. |
| [getParentSeries()](#getParentSeries--) | Retourneert de bovenliggende serie van de grafiek. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Retourneert een index van het opgegeven DataLabel in de collectie. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Haalt het standaardvormtype op of stelt het in voor gegevenslabels. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Haalt het standaardvormtype op of stelt het in voor gegevenslabels. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Haalt het gegevenslabel op voor het gegevenspunt met de opgegeven index.

--------------------

Een alternatieve manier om toegang te krijgen tot het gegevenslabel is:
- getSeries().getDataPoints().get_Item(i).getLabel()
- beheren van labeleigenschappen.

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

Stelt het opmaak van de begeleidende lijnen van gegevenslabels voor. Alleen-lezen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False betekent dat het gegevenslabel standaard niet zichtbaar is (en dus zijn alle Show*-flags (ShowValue, ...) van de eigenschap DefaultDataLabelFormat onwaar). Alleen-lezen  boolean .

--------------------

Als het gegevenslabel standaard zichtbaar is, kun je het standaard verbergen met de Hide()-methode. Maar als het gegevenslabel standaard niet zichtbaar is (IsVisible is false), kun je het gegevenslabel “standaard zichtbaar” maken door de Show*-flags (ShowValue, ...) van de eigenschap DefaultDataLabelFormat op waar te zetten.

**Retourneert:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Maak het gegevenslabel standaard verborgen door alle Show*-flags (ShowValue, ...) van de eigenschap DefaultDataLabelFormat op onwaar te zetten. IsVisible zal daarna onwaar zijn.

--------------------

Als het gegevenslabel standaard niet zichtbaar is (IsVisible is false), kun je het gegevenslabel “standaard zichtbaar” maken door de Show*-flags (ShowValue, ...) van de eigenschap DefaultDataLabelFormat op waar te zetten.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Haalt het aantal zichtbare gegevenslabels op in de collectie. Alleen-lezen  int .

**Retourneert:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het totale aantal gegevenslabels op in de collectie. Alleen-lezen  int .

**Retourneert:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Retourneert de bovenliggende serie van de grafiek. Alleen-lezen [IChartSeries](../../com.aspose.slides/ichartseries).

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
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | Te vinden DataLabel. |

**Retourneert:**
int - Index van een DataLabel of -1 als DataLabel niet uit deze collectie komt.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

Haalt het standaardvormtype op of stelt het in voor gegevenslabels. Retourneert [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) als er geen vorm is gedefinieerd.

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

Het instellen van deze eigenschap stelt ook de eigenschap IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) in voor alle gegevenslabels in de collectie op dezelfde waarde.

**Retourneert:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

Haalt het standaardvormtype op of stelt het in voor gegevenslabels. Retourneert [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) als er geen vorm is gedefinieerd.

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

Het instellen van deze eigenschap stelt ook de eigenschap IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) in voor alle gegevenslabels in de collectie op dezelfde waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |