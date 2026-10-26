---
title: IDataLabelCollection
second_title: Aspose.Slides för Android via Java API-referens
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
| [get_Item(int index)](#get-Item-int-) | Hämtar datatetiketten för datapunkten med det angivna indexet. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Returnerar standardformatet för alla datatetiketter i samlingen. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representerar formatet för ledarlinjer för datatetiketter. |
| [isVisible()](#isVisible--) | Falskt betyder att datatetiketten inte är synlig som standard (och att alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat är falska). |
| [hide()](#hide--) | Gör datatetiketten dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till falskt tillstånd. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Hämtar antalet synliga datatetiketter i samlingen. |
| [getCount()](#getCount--) | Hämtar antalet alla datatetiketter i samlingen. |
| [getParentSeries()](#getParentSeries--) | Returnerar den överordnade diagramserien. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returnerar ett index för den specificerade DataLabel i samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Hämtar datatetiketten för datapunkten med det angivna indexet.

--------------------

Alternativt sätt att komma åt datatetiketten är: - getSeries().getDataPoints().get_Item(i).getLabel() - hantera etiketts egenskaper.

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


Returnerar standardformatet för alla datatetiketter i samlingen. Skrivskyddad [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returnerar:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Representerar formatet för ledarlinjer för datatetiketter. Skrivskyddad [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Falskt betyder att datatetiketten inte är synlig som standard (och att alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat är falska). Skrivskyddad  boolean .

--------------------

Om datatetiketten är synlig som standard kan du göra den dold som standard med metoden Hide(). Men om datatetiketten inte är synlig som standard (IsVisible är falskt) kan du göra datatetiketten "synlig som standard" genom att sätta Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till sant tillstånd.

**Returnerar:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Gör datatetiketten dold som standard genom att sätta alla Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till falskt tillstånd. IsVisible kommer att vara falskt efter detta.

--------------------

Om datatetiketten inte är synlig som standard (IsVisible är falskt) kan du göra datatetiketten "synlig som standard" genom att sätta Show*-flaggor (ShowValue, ...) i egenskapen DefaultDataLabelFormat till sant tillstånd.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Hämtar antalet synliga datatetiketter i samlingen. Skrivskyddad  int .

**Returnerar:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Hämtar antalet alla datatetiketter i samlingen. Skrivskyddad  int .

**Returnerar:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Returnerar den överordnade diagramserien. Skrivskyddad [IChartSeries](../../com.aspose.slides/ichartseries).

**Returnerar:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Returnerar ett index för den specificerade DataLabel i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel att hitta. |

**Returnerar:**
int - Index för en DataLabel eller -1 om DataLabel inte kommer från denna samling.