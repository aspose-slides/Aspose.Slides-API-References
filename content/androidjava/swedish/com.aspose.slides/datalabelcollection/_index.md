---
title: DataLabelCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en serie etiketter.
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

Representerar en serie etiketter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChart()](#getChart--) | Returnerar det överordnade diagrammet. |
| [iterator()](#iterator--) | Returnerar en uppräknare som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [isVisible()](#isVisible--) | False betyder att dataetiketten inte är synlig som standard (och därför är alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat falska). |
| [hide()](#hide--) | Gör dataetiketten dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till falskt. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Hämtar antalet synliga dataetiketter i samlingen. |
| [getCount()](#getCount--) | Hämtar antalet alla dataetiketter i samlingen. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Hämtar standardformatet för dataetiketter. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representerar formatet för ledlinjer för dataetiketter. |
| [getParentSeries()](#getParentSeries--) | Hämtar den överordnade serien. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returnerar ett index för den angivna DataLabel i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar dataetiketten för datapoängen med angivet index. |
| [getSlide()](#getSlide--) | Returnerar den överordnade bilden för ett FillFormat. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för ett FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Returnerar det överordnade diagrammet. Läs-endast [IChart](../../com.aspose.slides/ichart).

**Returnerar:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


Returnerar en uppräknare som itererar genom samlingen.

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


False betyder att dataetiketten inte är synlig som standard (och därför är alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat falska). Läs-endast boolean.

--------------------

Om dataetiketten är synlig som standard kan du göra den dold som standard med metoden Hide(). Men om dataetiketten inte är synlig som standard (IsVisible är false) kan du göra dataetiketten “synlig som standard” genom att sätta Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till sant läge.

**Returnerar:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Gör dataetiketten dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till falskt läge. IsVisible blir false efter detta.

--------------------

Om dataetiketten inte är synlig som standard (IsVisible är false) kan du göra dataetiketten “synlig som standard” genom att sätta Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till sant läge.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Hämtar antalet synliga dataetiketter i samlingen. Läs-endast int.

**Returnerar:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Hämtar antalet alla dataetiketter i samlingen. Läs-endast int.

**Returnerar:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Hämtar standardformatet för dataetiketten. Läs-endast [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```


Representerar formatet för ledlinjer för dataetiketter. Läs-endast [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

**Returnerar:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```


Hämtar den överordnade serien. Läs-endast [IChartSeries](../../com.aspose.slides/ichartseries).

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
int - Index för en DataLabel eller -1 om DataLabel inte kommer från denna samling.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Hämtar dataetiketten för datapoängen med angivet index.

--------------------

Alternativt sätt att komma åt dataetikett är: - series.getDataPoints().get_Item(i).getLabel() - hantera etikettre egenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returnerar den överordnade bilden för ett FillFormat. Läs-endast [BaseSlide](../../com.aspose.slides/baseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returnerar den överordnade presentationen för ett FillFormat. Läs-endast [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)