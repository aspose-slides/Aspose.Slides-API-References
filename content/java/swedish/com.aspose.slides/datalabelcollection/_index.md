---
title: DataLabelCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar serietiketter.
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

Representerar en serieetikett.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChart()](#getChart--) | Returnerar det överordnade diagrammet. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [isVisible()](#isVisible--) | Falskt betyder att datamärket inte är synligt som standard (och därför är alla Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat falska). |
| [hide()](#hide--) | Gör datamärket dolt som standard genom att sätta alla Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till falskt läge. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Hämtar antalet synliga datamärken i samlingen. |
| [getCount()](#getCount--) | Hämtar antalet alla datamärken i samlingen. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Hämtar standardformatet för datamärket. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representerar formatet för ledlinjer för datamärken. |
| [getParentSeries()](#getParentSeries--) | Hämtar den överordnade serien. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returnerar ett index för den angivna DataLabel i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar datamärket för datapunkten med angivet index. |
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Falskt betyder att datamärket inte är synligt som standard (och därför är alla Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat falska). Skrivskyddad boolesk.

--------------------

Om datamärket är synligt som standard kan du göra det dolt som standard med Hide()-metoden. Men om datamärket inte är synligt som standard (IsVisible är falskt) kan du göra datamärket “synligt som standard” genom att sätta Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till sant läge.

**Returnerar:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Gör datamärket dolt som standard genom att sätta alla Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till falskt läge. IsVisible blir falskt efter detta.

--------------------

Om datamärket inte är synligt som standard (IsVisible är falskt) kan du göra datamärket “synligt som standard” genom att sätta Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till sant läge.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Hämtar antalet synliga datamärken i samlingen. Skrivskyddad int.

**Returnerar:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Hämtar antalet alla datamärken i samlingen. Skrivskyddad int.

**Returnerar:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Hämtar standardformatet för datamärket. Skrivskyddad [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Representerar formatet för ledlinjer för datamärken. Skrivskyddad [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
int - Index för en DataLabel eller -1 om DataLabel inte kommer från den här samlingen.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Hämtar datamärket för datapunkten med angivet index.

--------------------

Alternativt sätt att komma åt datamärket är: - series.getDataPoints().get_Item(i).getLabel() - hantera etikettens egenskaper.

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