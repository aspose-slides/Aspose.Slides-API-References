---
title: IDataLabelCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar serietiketter.
type: docs
url: /sv/com.aspose.slides/idatalabelcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Representerar serietiketter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar dataetiketten för datapunkten med angivet index. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Returnerar standardformatet för alla dataetiketter i samlingen. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representerar formatet för ledarlinjer för dataetiketter. |
| [isVisible()](#isVisible--) | Falskt betyder att dataetiketten inte är synlig som standard (och således är alla Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat falska). |
| [hide()](#hide--) | Gör dataetiketten dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till falskt. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Hämtar antalet synliga dataetiketter i samlingen. |
| [getCount()](#getCount--) | Hämtar antalet dataetiketter i samlingen. |
| [getParentSeries()](#getParentSeries--) | Returnerar föräldra diagramserie. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returnerar ett index för den angivna DataLabel i samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Hämtar dataetiketten för datapunkten med angivet index.

--------------------

Alternativt sätt att komma åt dataetikett är: - getSeries().getDataPoints().get_Item(i).getLabel() - hantera etikettens egenskaper.

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


Returnerar standardformatet för alla dataetiketter i samlingen. Skrivskyddad [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Falskt betyder att dataetiketten inte är synlig som standard (och således är alla Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat falska). Skrivskyddad  boolean .

--------------------

Om dataetiketten är synlig som standard kan du göra den dold som standard med Hide()-metoden. Men om dataetiketten inte är synlig som standard (IsVisible är falskt) kan du göra dataetiketten "synlig som standard" genom att sätta Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till sant läge.

**Returnerar:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Gör dataetiketten dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till falskt. IsVisible blir falskt efter detta.

--------------------

Om dataetiketten inte är synlig som standard (IsVisible är falskt) kan du göra dataetiketten "synlig som standard" genom att sätta Show*-flaggor (ShowValue, ...) för egenskapen DefaultDataLabelFormat till sant läge.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Hämtar antalet synliga dataetiketter i samlingen. Skrivskyddad  int .

**Returnerar:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Hämtar antalet dataetiketter i samlingen. Skrivskyddad  int .

**Returnerar:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Returnerar föräldra diagramserie. Skrivskyddad [IChartSeries](../../com.aspose.slides/ichartseries).

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