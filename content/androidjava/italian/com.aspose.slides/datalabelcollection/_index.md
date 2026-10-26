---
title: DataLabelCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta le etichette di una serie.
type: docs
url: /it/com.aspose.slides/datalabelcollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Rappresenta le etichette di una serie.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChart()](#getChart--) | Restituisce il grafico padre. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [isVisible()](#isVisible--) | False indica che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false). |
| [hide()](#hide--) | Rende l'etichetta dati nascosta per impostazione predefinita impostando tutti i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Ottiene il numero di etichette dati visibili nella collezione. |
| [getCount()](#getCount--) | Ottiene il numero di tutte le etichette dati nella collezione. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Ottiene il formato predefinito dell'etichetta dati. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Rappresenta il formato delle linee guida delle etichette dati. |
| [getParentSeries()](#getParentSeries--) | Ottiene la serie padre. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Restituisce l'indice della DataLabel specificata nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'etichetta dati per il punto dati con l'indice specificato. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva padre di un FillFormat. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione padre di un FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Restituisce il grafico padre. Solo lettura [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Un java.util.Iterator per l'intera collezione.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False indica che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false). Booleano solo lettura.

--------------------

Se l'etichetta dati è visibile per impostazione predefinita, è possibile renderla nascosta per impostazione predefinita con il metodo Hide(). Ma se l'etichetta dati non è visibile per impostazione predefinita (IsVisible è false) è possibile rendere l'etichetta dati "visibile per impostazione predefinita" impostando i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato true.

**Restituisce:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Rende l'etichetta dati nascosta per impostazione predefinita impostando tutti i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato false. IsVisible sarà false dopo questa operazione.

--------------------

Se l'etichetta dati non è visibile per impostazione predefinita (IsVisible è false) è possibile rendere l'etichetta dati "visibile per impostazione predefinita" impostando i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat allo stato true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Ottiene il numero di etichette dati visibili nella collezione. Solo lettura int.

**Restituisce:**
int

### getCount() {#getCount--}
```
public final int getCount()
```

Ottiene il numero di tutte le etichette dati nella collezione. Solo lettura int.

**Restituisce:**
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Ottiene il formato predefinito dell'etichetta dati. Solo lettura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Restituisce:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Rappresenta il formato delle linee guida delle etichette dati. Solo lettura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Ottiene la serie padre. Solo lettura [IChartSeries](../../com.aspose.slides/ichartseries).

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Restituisce l'indice della DataLabel specificata nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel da trovare. |

**Restituisce:**
int - Indice di una DataLabel o -1 se la DataLabel non appartiene a questa collezione.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Ottiene l'etichetta dati per il punto dati con l'indice specificato.

--------------------

Un modo alternativo per accedere all'etichetta dati è:
- series.getDataPoints().get_Item(i).getLabel()
- gestire le proprietà dell'etichetta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva padre di un FillFormat. Solo lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione padre di un FillFormat. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)