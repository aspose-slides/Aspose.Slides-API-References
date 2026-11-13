---
title: DataLabelCollection
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje etykiety serii.
type: docs
url: /pl/com.aspose.slides/datalabelcollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Reprezentuje etykiety serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [getChart()](#getChart--) | Zwraca wykres nadrzędny. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [isVisible()](#isVisible--) | False oznacza, że etykieta danych nie jest widoczna domyślnie (i więc wszystkie flagi Show*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat są false). |
| [hide()](#hide--) | Sprawia, że etykieta danych jest domyślnie ukryta, ustawiając wszystkie flagi Show*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat na stan false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Pobiera liczbę widocznych etykiet danych w kolekcji. |
| [getCount()](#getCount--) | Pobiera liczbę wszystkich etykiet danych w kolekcji. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Pobiera domyślny format etykiet danych. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Reprezentuje format linii prowadzących etykiet danych. |
| [getParentSeries()](#getParentSeries--) | Pobiera serię nadrzędną. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Zwraca indeks określonej DataLabel w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera etykietę danych dla punktu danych o określonym indeksie. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Pobiera lub ustawia domyślny typ kształtu dla etykiet danych. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Pobiera lub ustawia domyślny typ kształtu dla etykiet danych. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny formatu wypełnienia. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną formatu wypełnienia. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Zwraca wykres nadrzędny. Tylko do odczytu [IChart](../../com.aspose.slides/ichart).

**Zwraca:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - java.util.Iterator dla całej kolekcji.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False oznacza, że etykieta danych nie jest widoczna domyślnie (i więc wszystkie flagi Show*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat są false). Tylko do odczytu boolean.

--------------------

Jeśli etykieta danych jest domyślnie widoczna, możesz ukryć ją domyślnie metodą Hide(). Jeśli etykieta danych nie jest widoczna domyślnie (IsVisible jest false), możesz ustawić ją jako „widoczna domyślnie” ustawiając flagi Show*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat na stan true.

**Zwraca:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Sprawia, że etykieta danych jest domyślnie ukryta, ustawiając wszystkie flagi Show*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat na stan false. IsVisible będzie false po wykonaniu tej operacji.

--------------------

Jeśli etykieta danych nie jest widoczna domyślnie (IsVisible jest false), możesz ustawić ją jako „widoczna domyślnie” ustawiając flagi Show*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat na stan true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Pobiera liczbę widocznych etykiet danych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int

### getCount() {#getCount--}
```
public final int getCount()
```

Pobiera liczbę wszystkich etykiet danych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Pobiera domyślny format etykiet danych. Tylko do odczytu [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Zwraca:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
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

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Pobiera serię nadrzędną. Tylko do odczytu [IChartSeries](../../com.aspose.slides/ichartseries).

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Zwraca indeks określonej DataLabel w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel do znalezienia. |

**Zwraca:**
int - Indeks DataLabel lub -1 jeśli DataLabel nie pochodzi z tej kolekcji.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Pobiera etykietę danych dla punktu danych o określonym indeksie.

--------------------

Alternatywny sposób dostępu do etykiety danych to:
- series.getDataPoints().get_Item(i).getLabel()
- zarządzaj właściwościami etykiety.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

Pobiera lub ustawia domyślny typ kształtu dla etykiet danych. Zwraca [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jeśli żaden kształt nie jest zdefiniowany.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ustaw typ kształtu wszystkich etykiet danych w pierwszej serii na Ellipse.
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
public final void setDefaultLabelShapeType(int value)
```

Pobiera lub ustawia domyślny typ kształtu dla etykiet danych. Zwraca [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) jeśli żaden kształt nie jest zdefiniowany.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ustaw typ kształtu wszystkich etykiet danych w pierwszej serii na Ellipse.
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

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd nadrzędny formatu wypełnienia. Tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację nadrzędną formatu wypełnienia. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)