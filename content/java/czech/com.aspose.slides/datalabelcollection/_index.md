---
title: DataLabelCollection
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje popisky řady.
type: docs
url: /cs/com.aspose.slides/datalabelcollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Reprezentuje popisky řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [isVisible()](#isVisible--) | False znamená, že popisek dat není ve výchozím stavu viditelný (a tedy všechny Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat jsou false). |
| [hide()](#hide--) | Skryjte popisek dat ve výchozím stavu nastavením všech Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Získá počet viditelných popisků dat v kolekci. |
| [getCount()](#getCount--) | Získá počet všech popisků dat v kolekci. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Získá výchozí formát popisku dat. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Reprezentuje formát vodicích čar popisků dat. |
| [getParentSeries()](#getParentSeries--) | Získá nadřazenou řadu. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Vrací index zadaného DataLabel v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá popisek dat pro datový bod se zadaným indexem. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Získá nebo nastaví výchozí typ tvaru pro popisky dat. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Získá nebo nastaví výchozí typ tvaru pro popisky dat. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací nadřazený graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - java.util.Iterator pro celou kolekci.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False znamená, že popisek dat není ve výchozím stavu viditelný (a tedy všechny Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat jsou false). Pouze pro čtení boolean.

--------------------

Pokud je popisek dat ve výchozím stavu viditelný, můžete jej ve výchozím stavu skrýt pomocí metody Hide(). Pokud popisek dat není ve výchozím stavu viditelný (IsVisible je false), můžete jej "ve výchozím stavu viditelný" učinit nastavením příznaků Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na true.

**Vrací:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Skryjte popisek dat ve výchozím stavu nastavením všech Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na false. IsVisible bude po tomto nastavení false.

--------------------

Pokud popisek dat není ve výchozím stavu viditelný (IsVisible je false), můžete jej "ve výchozím stavu viditelný" učinit nastavením příznaků Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Získá počet viditelných popisků dat v kolekci. Pouze pro čtení int.

**Vrací:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Získá počet všech popisků dat v kolekci. Pouze pro čtení int.

**Vrací:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Získá výchozí formát popisku dat. Pouze pro čtení [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Vrací:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Reprezentuje formát vodicích čar popisků dat. Pouze pro čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Získá nadřazenou řadu. Pouze pro čtení [IChartSeries](../../com.aspose.slides/ichartseries).

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Vrací index zadaného DataLabel v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel k nalezení. |

**Vrací:**
int - Index DataLabel nebo -1, pokud DataLabel není z této kolekce.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Získá popisek dat pro datový bod se zadaným indexem.

--------------------

Alternativní způsob přístupu k popisku dat je: - series.getDataPoints().get_Item(i).getLabel() - spravovat vlastnosti popisku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

Získá nebo nastaví výchozí typ tvaru pro popisky dat. Vrací [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), pokud není definován žádný tvar.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Nastavte typ tvaru všech popisků dat v první řadě na Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nastavením této vlastnosti se také nastaví vlastnost IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) pro všechny popisky dat v kolekci na stejnou hodnotu.

**Vrací:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

Získá nebo nastaví výchozí typ tvaru pro popisky dat. Vrací [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), pokud není definován žádný tvar.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Nastavte typ tvaru všech popisků dat v první řadě na Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nastavením této vlastnosti se také nastaví vlastnost IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) pro všechny popisky dat v kolekci na stejnou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek objektu FillFormat. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci objektu FillFormat. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)