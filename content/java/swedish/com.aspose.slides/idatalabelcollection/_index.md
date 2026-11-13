---
title: IDataLabelCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en serie etiketter.
type: docs
url: /sv/com.aspose.slides/idatalabelcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Representerar en serie etiketter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar dataetiketten för datapunkten med det angivna indexet. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Returnerar standardformatet för alla dataetiketter i samlingen. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representerar dataetiketternas ledarlinjeformat. |
| [isVisible()](#isVisible--) | False betyder att dataetiketten inte är synlig som standard (och så är alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat falska). |
| [hide()](#hide--) | Gör dataetiketten dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till falskt. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Hämtar antalet synliga dataetiketter i samlingen. |
| [getCount()](#getCount--) | Hämtar antalet alla dataetiketter i samlingen. |
| [getParentSeries()](#getParentSeries--) | Returnerar föräldrakartserien. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returnerar ett index för den angivna DataLabel i samlingen. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Hämtar eller anger standardformen för dataetiketter. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Hämtar eller anger standardformen för dataetiketter. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Hämtar dataetiketten för datapunkten med det angivna indexet.

--------------------

Alternativt sätt att komma åt dataetikett är: - getSeries().getDataPoints().get_Item(i).getLabel() - hantera etikettregenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Returnerar standardformatet för alla dataetiketter i samlingen. Endast läsbar [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Representerar dataetiketternas ledarlinjeformat. Endast läsbar [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False betyder att dataetiketten inte är synlig som standard (och så är alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat falska). Endast läsbar  boolean .

--------------------

Om dataetiketten är synlig som standard kan du göra den dold som standard med Hide()-metoden. Men om dataetiketten inte är synlig som standard (IsVisible är false) kan du göra dataetiketten "synlig som standard" genom att sätta Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till sant.

**Returnerar:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Gör dataetiketten dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till falskt. IsVisible kommer att vara false efter detta.

--------------------

Om dataetiketten inte är synlig som standard (IsVisible är false) kan du göra dataetiketten "synlig som standard" genom att sätta Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till sant.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Hämtar antalet synliga dataetiketter i samlingen. Endast läsbar  int .

**Returnerar:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Hämtar antalet alla dataetiketter i samlingen. Endast läsbar  int .

**Returnerar:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Returnerar föräldrakartserien. Endast läsbar [IChartSeries](../../com.aspose.slides/ichartseries).

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Returnerar ett index för den angivna DataLabel i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel att hitta. |

**Returnerar:**
int - Index för en DataLabel eller -1 om DataLabel inte kommer från denna samling.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

Hämtar eller anger standardformen för dataetiketter. Returnerar [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) om ingen form är definierad.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Sätt formtypen för alla dataetiketter i den första serien till Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Att sätta denna egenskap sätter också egenskapen IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) för alla dataetiketter i samlingen till samma värde.

**Returnerar:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

Hämtar eller anger standardformen för dataetiketter. Returnerar [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) om ingen form är definierad.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Sätt formtypen för alla dataetiketter i den första serien till Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Att sätta denna egenskap sätter också egenskapen IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) för alla dataetiketter i samlingen till samma värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |