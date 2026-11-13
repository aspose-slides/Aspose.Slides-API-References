---
title: DataLabelCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le etichette di una serie.
type: docs
url: /it/com.aspose.slides/datalabelcollection/
---
**Eredità:**
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
| [getChart()](#getChart--) | Restituisce il grafico genitore. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [isVisible()](#isVisible--) | False indica che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i flag Show\*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false). |
| [hide()](#hide--) | Nascondi l'etichetta dati per impostazione predefinita impostando tutti i flag Show\*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat nello stato false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Ottiene il numero di etichette dati visibili nella collezione. |
| [getCount()](#getCount--) | Ottiene il numero di tutte le etichette dati nella collezione. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Ottiene il formato predefinito dell'etichetta dati. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Rappresenta il formato delle linee guida delle etichette dati. |
| [getParentSeries()](#getParentSeries--) | Ottiene la serie genitore. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Restituisce l'indice del DataLabel specificato nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'etichetta dati per il punto dati con l'indice specificato. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Ottiene o imposta il tipo di forma predefinito per le etichette dati. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Ottiene o imposta il tipo di forma predefinito per le etichette dati. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva genitore di un FillFormat. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione genitore di un FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Restituisce il grafico genitore. Sola lettura [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel} - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel} - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False indica che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i flag Show\*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false). Sola lettura boolean.

--------------------

Se l'etichetta dati è visibile per impostazione predefinita è possibile nasconderla con il metodo Hide(). Ma se l'etichetta dati non è visibile per impostazione predefinita (IsVisible è false) è possibile renderla "visibile per impostazione predefinita" impostando i flag Show\*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat nello stato true.

**Restituisce:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Nascondi l'etichetta dati per impostazione predefinita impostando tutti i flag Show\*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat nello stato false. IsVisible sarà false dopo questa operazione.

--------------------

Se l'etichetta dati non è visibile per impostazione predefinita (IsVisible è false) è possibile renderla "visibile per impostazione predefinita" impostando i flag Show\*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat nello stato true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Ottiene il numero di etichette dati visibili nella collezione. Sola lettura int.

**Restituisce:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Ottiene il numero di tutte le etichette dati nella collezione. Sola lettura int.

**Restituisce:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Ottiene il formato predefinito dell'etichetta dati. Sola lettura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Restituisce:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
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


Ottiene la serie genitore. Sola lettura [IChartSeries](../../com.aspose.slides/ichartseries).

**Restituisce:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


Restituisce l'indice del DataLabel specificato nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel da trovare. |

**Restituisce:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Ottiene l'etichetta dati per il punto dati con l'indice specificato.

--------------------

Un modo alternativo per accedere all'etichetta dati è: - series.getDataPoints().get_Item(i).getLabel() - gestire le proprietà dell'etichetta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```


Ottiene o imposta il tipo di forma predefinito per le etichette dati. Restituisce [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se non è definita alcuna forma.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Imposta il tipo di forma di tutte le etichette dati nella prima serie su Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Impostare questa proprietà imposta anche la proprietà IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) per tutte le etichette dati nella collezione allo stesso valore.

**Restituisce:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```


Ottiene o imposta il tipo di forma predefinito per le etichette dati. Restituisce [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se non è definita alcuna forma.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Imposta il tipo di forma di tutte le etichette dati nella prima serie su Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Impostare questa proprietà imposta anche la proprietà IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) per tutte le etichette dati nella collezione allo stesso valore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Restituisce la diapositiva genitore di un FillFormat. Sola lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Restituisce la presentazione genitore di un FillFormat. Sola lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)