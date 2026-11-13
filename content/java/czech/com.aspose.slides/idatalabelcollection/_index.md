---
title: IDataLabelCollection
second_title: Aspose.Slides pro Java – reference API
description: Představuje popisky řady.
type: docs
url: /cs/com.aspose.slides/idatalabelcollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Představuje popisky řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá popisek dat pro datový bod se zadaným indexem. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Vrací výchozí formát všech popisků dat v kolekci. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Představuje formát vodičových čar popisků dat. |
| [isVisible()](#isVisible--) | False znamená, že popisek dat není ve výchozím nastavení viditelný (a proto jsou všechny příznaky Show*- (ShowValue, ...) vlastnosti DefaultDataLabelFormat nastaveny na false). |
| [hide()](#hide--) | Skryje popisek dat ve výchozím nastavení nastavením všech příznaků Show*- (ShowValue, ...) vlastnosti DefaultDataLabelFormat do stavu false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Získá počet viditelných popisků dat v kolekci. |
| [getCount()](#getCount--) | Získá počet všech popisků dat v kolekci. |
| [getParentSeries()](#getParentSeries--) | Vrací nadřazenou sérii grafu. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Vrací index zadaného DataLabel v kolekci. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Získá nebo nastaví výchozí typ tvaru pro popisky dat. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Získá nebo nastaví výchozí typ tvaru pro popisky dat. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Získá popisek dat pro datový bod se zadaným indexem.

--------------------

Alternativní způsob přístupu k popisku dat je: - getSeries().getDataPoints().get_Item(i).getLabel() - spravovat vlastnosti popisku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Vrací výchozí formát všech popisků dat v kolekci. Pouze pro čtení [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Vrací:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Představuje formát vodičových čar popisků dat. Pouze pro čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False znamená, že popisek dat není ve výchozím nastavení viditelný (a proto jsou všechny příznaky Show*- (ShowValue, ...) vlastnosti DefaultDataLabelFormat nastaveny na false). Pouze pro čtení  boolean .

--------------------

Pokud je popisek dat ve výchozím nastavení viditelný, můžete jej ve výchozím nastavení skrýt pomocí metody Hide(). Ale pokud popisek dat není ve výchozím nastavení viditelný (IsVisible je false), můžete popisek dat „viditelný ve výchozím nastavení“ nastavit nastavením příznaků Show*- (ShowValue, ...) vlastnosti DefaultDataLabelFormat na stav true.

**Vrací:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Skryje popisek dat ve výchozím nastavení nastavením všech příznaků Show*- (ShowValue, ...) vlastnosti DefaultDataLabelFormat do stavu false. IsVisible bude po tomto nastavení false.

--------------------

Pokud popisek dat není ve výchozím nastavení viditelný (IsVisible je false), můžete popisek dat „viditelný ve výchozím nastavení“ nastavit nastavením příznaků Show*- (ShowValue, ...) vlastnosti DefaultDataLabelFormat na stav true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Získá počet viditelných popisků dat v kolekci. Pouze pro čtení  int .

**Vrací:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Získá počet všech popisků dat v kolekci. Pouze pro čtení  int .

**Vrací:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Vrací nadřazenou sérii grafu. Pouze pro čtení [IChartSeries](../../com.aspose.slides/ichartseries).

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Vrací index zadaného DataLabel v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel k nalezení. |

**Vrací:**
int - Index DataLabel nebo -1, pokud DataLabel není z této kolekce.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

Získá nebo nastaví výchozí typ tvaru pro popisky dat. Vrací [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), pokud není definován žádný tvar.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Nastavte typ tvaru všech popisků dat v první sérii na Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nastavení této vlastnosti také nastaví vlastnost IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) pro všechny popisky dat v kolekci na stejnou hodnotu.

**Vrací:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

Získá nebo nastaví výchozí typ tvaru pro popisky dat. Vrací [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined), pokud není definován žádný tvar.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Nastavte typ tvaru všech popisků dat v první sérii na Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nastavení této vlastnosti také nastaví vlastnost IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) pro všechny popisky dat v kolekci na stejnou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |