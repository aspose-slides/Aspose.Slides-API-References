---
title: IDataLabelCollection
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta le etichette di una serie.
type: docs
url: /it/com.aspose.slides/idatalabelcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Rappresenta le etichette di una serie.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'etichetta dati per il punto dati con l'indice specificato. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Restituisce il formato predefinito di tutte le etichette dati nella collezione. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Rappresenta il formato delle linee guida delle etichette dati. |
| [isVisible()](#isVisible--) | False indica che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i flag Show*- (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false). |
| [hide()](#hide--) | Rende l'etichetta dati nascosta per impostazione predefinita impostando tutti i flag Show*- (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Ottiene il numero di etichette dati visibili nella collezione. |
| [getCount()](#getCount--) | Ottiene il numero di tutte le etichette dati nella collezione. |
| [getParentSeries()](#getParentSeries--) | Restituisce la serie di grafico padre. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Restituisce l'indice della DataLabel specificata nella collezione. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Ottiene l'etichetta dati per il punto dati con l'indice specificato.

--------------------

Un modo alternativo per accedere all'etichetta dati è: - getSeries().getDataPoints().get_Item(i).getLabel() - gestire le proprietà dell'etichetta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Restituisce il formato predefinito di tutte le etichette dati nella collezione. Sola lettura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Restituisce:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Rappresenta il formato delle linee guida delle etichette dati. Sola lettura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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


**Restituisce:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False indica che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i flag Show*- (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false). Sola lettura  boolean .

--------------------

Se l'etichetta dati è visibile per impostazione predefinita, è possibile renderla nascosta per impostazione predefinita con il metodo Hide(). Ma se l'etichetta dati non è visibile per impostazione predefinita (IsVisible è false) è possibile rendere l'etichetta dati "visibile per impostazione predefinita" impostando i flag Show*- (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato true.

**Restituisce:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Rende l'etichetta dati nascosta per impostazione predefinita impostando tutti i flag Show*- (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato false. IsVisible sarà false dopo questa operazione.

--------------------

Se l'etichetta dati non è visibile per impostazione predefinita (IsVisible è false) è possibile rendere l'etichetta dati "visibile per impostazione predefinita" impostando i flag Show*- (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Ottiene il numero di etichette dati visibili nella collezione. Sola lettura  int .

**Restituisce:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Ottiene il numero di tutte le etichette dati nella collezione. Sola lettura  int .

**Restituisce:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Restituisce la serie di grafico padre. Sola lettura [IChartSeries](../../com.aspose.slides/ichartseries).

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Restituisce l'indice della DataLabel specificata nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel da trovare. |

**Restituisce:**
int - Indice di una DataLabel o -1 se la DataLabel non proviene da questa collezione.