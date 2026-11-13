---
title: DataLabelCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en serieetiketter.
type: docs
url: /sv/com.aspose.slides/datalabelcollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Representerar en serieetiketter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChart()](#getChart--) | Returnerar det överordnade diagrammet. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [isVisible()](#isVisible--) | Falskt betyder att dataetiketten inte är synlig som standard (och så är alla Show\*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat falska). |
| [hide()](#hide--) | Gör dataetiketten dold som standard genom att sätta alla Show\*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till falskt. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Hämtar antalet synliga dataetiketter i samlingen. |
| [getCount()](#getCount--) | Hämtar antalet dataetiketter i samlingen. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Hämtar standardformatet för dataetiketter. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representerar formatet för ledarlinjer för dataetiketter. |
| [getParentSeries()](#getParentSeries--) | Hämtar den överordnade serien. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returnerar ett index för den angivna DataLabel i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar dataetiketten för datapunkten med det angivna indexet. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Hämtar eller anger standardformtypen för dataetiketter. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Hämtar eller anger standardformtypen för dataetiketter. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returnerar det överordnade diagrammet. Skrivskyddad [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - En java.util.Iterator för hela samlingen.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Falskt betyder att dataetiketten inte är synlig som standard (och så är alla Show\*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat falska). Skrivskyddad boolean.

--------------------

Om dataetiketten är synlig som standard kan du göra den dold som standard med Hide()-metoden. Men om dataetiketten inte är synlig som standard (IsVisible är falskt) kan du göra dataetiketten "synlig som standard" genom att sätta Show\*-flaggorna (ShowValue, ...) för egenskapen DefaultDataLabelFormat till sant.

**Returnerar:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Gör dataetiketten dold som standard genom att sätta alla Show\*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till falskt. IsVisible kommer att vara falskt efter detta.

--------------------

Om dataetiketten inte är synlig som standard (IsVisible är falskt) kan du göra dataetiketten "synlig som standard" genom att sätta Show\*-flaggorna (ShowValue, ...) för egenskapen DefaultDataLabelFormat till sant.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Hämtar antalet synliga dataetiketter i samlingen. Skrivskyddad int.

**Returnerar:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Hämtar antalet dataetiketter i samlingen. Skrivskyddad int.

**Returnerar:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Hämtar standardformatet för dataetiketter. Skrivskyddad [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```


Representerar formatet för ledarlinjer för dataetiketter. Skrivskyddad [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```


Hämtar den överordnade serien. Skrivskyddad [IChartSeries](../../com.aspose.slides/ichartseries).

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


Returnerar ett index för den angivna DataLabel i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel att hitta. |

**Returnerar:**
int - Index för en DataLabel eller -1 om DataLabel inte finns i denna samling.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Hämtar dataetiketten för datapunkten med det angivna indexet.

--------------------

Alternativt sätt att komma åt dataetiketten är: - series.getDataPoints().get_Item(i).getLabel() - hantera etikettens egenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```


Hämtar eller anger standardformtypen för dataetiketter. Returnerar [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) om ingen form är definierad.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ställ in formtypen för alla dataetiketter i den första serien till Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Inställning av den här egenskapen sätter också egenskapen IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) för alla dataetiketter i samlingen till samma värde.

**Returnerar:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```


Hämtar eller anger standardformtypen för dataetiketter. Returnerar [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) om ingen form är definierad.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ställ in formtypen för alla dataetiketter i den första serien till Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Inställning av den här egenskapen sätter också egenskapen IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) för alla dataetiketter i samlingen till samma värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returnerar den överordnade bilden för ett FillFormat. Skrivskyddad [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returnerar den överordnade presentationen för ett FillFormat. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)