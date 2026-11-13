---
title: IDataLabelCollection
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje etykiety serii.
type: docs
url: /pl/com.aspose.slides/idatalabelcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Reprezentuje etykiety serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera etykietę danych dla punktu danych o podanym indeksie. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Zwraca domyślny format wszystkich etykiet danych w kolekcji. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Reprezentuje format linii prowadzących etykiet danych. |
| [isVisible()](#isVisible--) | Fałsz oznacza, że etykieta danych nie jest widoczna domyślnie (a więc wszystkie flagi Show\*- (ShowValue, ...) właściwości DefaultDataLabelFormat są ustawione na false). |
| [hide()](#hide--) | Ukrywa etykietę danych domyślnie, ustawiając wszystkie flagi Show\*- (ShowValue, ...) właściwości DefaultDataLabelFormat na stan false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Pobiera liczbę widocznych etykiet danych w kolekcji. |
| [getCount()](#getCount--) | Pobiera liczbę wszystkich etykiet danych w kolekcji. |
| [getParentSeries()](#getParentSeries--) | Zwraca powiązaną serię wykresu. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Zwraca indeks określonej DataLabel w kolekcji. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Pobiera lub ustawia domyślny typ kształtu dla etykiet danych. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Pobiera lub ustawia domyślny typ kształtu dla etykiet danych. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Pobiera etykietę danych dla punktu danych o podanym indeksie.

--------------------

Alternatywny sposób dostępu do etykiety danych to: - getSeries().getDataPoints().get\_Item(i).getLabel() - zarządzanie właściwościami etykiety.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Zwraca domyślny format wszystkich etykiet danych w kolekcji. Tylko do odczytu [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Zwraca:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Reprezentuje format linii prowadzących etykiet danych. Tylko do odczytu [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

**Zwraca:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Fałsz oznacza, że etykieta danych nie jest widoczna domyślnie (a więc wszystkie flagi Show\*- (ShowValue, ...) właściwości DefaultDataLabelFormat są ustawione na false). Tylko do odczytu  boolean .

--------------------

Jeśli etykieta danych jest widoczna domyślnie, możesz ukryć ją domyślnie metodą Hide(). Natomiast jeśli etykieta danych nie jest widoczna domyślnie (IsVisible jest false), możesz ustawić ją jako "widoczna domyślnie", ustawiając flagi Show\*- (ShowValue, ...) właściwości DefaultDataLabelFormat na stan true.

**Zwraca:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Ukrywa etykietę danych domyślnie, ustawiając wszystkie flagi Show\*- (ShowValue, ...) właściwości DefaultDataLabelFormat na stan false. IsVisible będzie false po tej operacji.

--------------------

Jeśli etykieta danych nie jest widoczna domyślnie (IsVisible jest false), możesz uczynić ją "widoczną domyślnie", ustawiając flagi Show\*- (ShowValue, ...) właściwości DefaultDataLabelFormat na stan true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Pobiera liczbę widocznych etykiet danych w kolekcji. Tylko do odczytu  int .

**Zwraca:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Pobiera liczbę wszystkich etykiet danych w kolekcji. Tylko do odczytu  int .

**Zwraca:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Zwraca powiązaną serię wykresu. Tylko do odczytu [IChartSeries](../../com.aspose.slides/ichartseries).

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Zwraca indeks określonej DataLabel w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel do znalezienia. |

**Zwraca:**
int - Indeks DataLabel lub -1 jeśli DataLabel nie pochodzi z tej kolekcji.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```


Pobiera lub ustawia domyślny typ kształtu dla etykiet danych. Zwraca [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jeśli nie zdefiniowano kształtu.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ustaw typ kształtu wszystkich etykiet danych w pierwszej serii na Elipsę.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Ustawienie tej właściwości ustawia również właściwość IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) dla wszystkich etykiet danych w kolekcji na tę samą wartość.

**Zwraca:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```


Pobiera lub ustawia domyślny typ kształtu dla etykiet danych. Zwraca [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jeśli nie zdefiniowano kształtu.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ustaw typ kształtu wszystkich etykiet danych w pierwszej serii na Elipsę.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Ustawienie tej właściwości ustawia również właściwość IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) dla wszystkich etykiet danych w kolekcji na tę samą wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |