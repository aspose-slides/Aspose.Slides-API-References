---
title: IDataLabelCollection
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta le etichette di una serie.
type: docs
url: /it/com.aspose.slides/idatalabelcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Rappresenta le etichette della serie.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'etichetta dei dati per il punto dati con l'indice specificato. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Restituisce il formato predefinito di tutte le etichette dei dati nella collezione. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Rappresenta il formato delle linee guida delle etichette dei dati. |
| [isVisible()](#isVisible--) | False indica che l'etichetta dei dati non è visibile per impostazione predefinita (e quindi tutti i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false). |
| [hide()](#hide--) | Rende l'etichetta dei dati nascosta per impostazione predefinita impostando tutti i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat nello stato false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Restituisce il numero di etichette dei dati visibili nella collezione. |
| [getCount()](#getCount--) | Restituisce il numero di tutte le etichette dei dati nella collezione. |
| [getParentSeries()](#getParentSeries--) | Restituisce la serie di grafico padre. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Restituisce l'indice della DataLabel specificata nella collezione. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Restituisce o imposta il tipo di forma predefinito per le etichette dei dati. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Restituisce o imposta il tipo di forma predefinito per le etichette dei dati. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Restituisce l'etichetta dei dati per il punto dati con l'indice specificato.

--------------------

Un modo alternativo per accedere all'etichetta dei dati è:
- getSeries().getDataPoints().get\_Item(i).getLabel()
- manage label properties.

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

Restituisce il formato predefinito di tutte le etichette dei dati nella collezione. Solo lettura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Restituisce:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Rappresenta il formato delle linee guida delle etichette dei dati. Solo lettura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False indica che l'etichetta dei dati non è visibile per impostazione predefinita (e quindi tutti i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false). Solo lettura boolean .

--------------------

Se l'etichetta dei dati è visibile per impostazione predefinita è possibile nasconderla di default con il metodo Hide(). Ma se l'etichetta dei dati non è visibile per impostazione predefinita (IsVisible è false) è possibile renderla "visibile per impostazione predefinita" impostando i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat nello stato true.

**Restituisce:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Rende l'etichetta dei dati nascosta per impostazione predefinita impostando tutti i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat nello stato false. IsVisible sarà false dopo questa operazione.

--------------------

Se l'etichetta dei dati non è visibile per impostazione predefinita (IsVisible è false) è possibile renderla "visibile per impostazione predefinita" impostando i flag Show* (ShowValue, ...) della proprietà DefaultDataLabelFormat nello stato true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Restituisce il numero di etichette dei dati visibili nella collezione. Solo lettura int .

**Restituisce:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Restituisce il numero di tutte le etichette dei dati nella collezione. Solo lettura int .

**Restituisce:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Restituisce la serie di grafico padre. Solo lettura [IChartSeries](../../com.aspose.slides/ichartseries).

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
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

Restituisce o imposta il tipo di forma predefinito per le etichette dei dati. Restituisce [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se non è definita alcuna forma.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Imposta il tipo di forma di tutte le etichette dei dati nella prima serie su Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Impostare questa proprietà imposta anche la proprietà IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) per tutte le etichette dei dati nella collezione allo stesso valore.

**Restituisce:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

Restituisce o imposta il tipo di forma predefinito per le etichette dei dati. Restituisce [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se non è definita alcuna forma.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Imposta il tipo di forma di tutte le etichette dei dati nella prima serie su Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Impostare questa proprietà imposta anche la proprietà IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) per tutte le etichette dei dati nella collezione allo stesso valore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |