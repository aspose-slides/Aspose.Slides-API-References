---
title: IDataLabelCollection
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje etykiety serii.
type: docs
url: /pl/com.aspose.slides/idatalabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Reprezentuje etykiety serii.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera etykietę danych dla punktu danych o określonym indeksie. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Zwraca domyślny format wszystkich etykiet danych w kolekcji. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Reprezentuje format linii prowadzących etykiet danych. |
| [isVisible()](#isVisible--) | Fałsz oznacza, że etykieta danych nie jest widoczna domyślnie (a więc wszystkie flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat są ustawione na false). |
| [hide()](#hide--) | Ukrywa etykietę danych domyślnie, ustawiając wszystkie flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat na stan false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Pobiera liczbę widocznych etykiet danych w kolekcji. |
| [getCount()](#getCount--) | Pobiera liczbę wszystkich etykiet danych w kolekcji. |
| [getParentSeries()](#getParentSeries--) | Zwraca nadrzędną serię wykresu. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Zwraca indeks określonej etykiety danych w kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Pobiera etykietę danych dla punktu danych o określonym indeksie.

--------------------

Alternatywny sposób uzyskania etykiety danych to: - getSeries().getDataPoints().get_Item(i).getLabel() - zarządzanie właściwościami etykiety.

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

Fałsz oznacza, że etykieta danych nie jest widoczna domyślnie (a więc wszystkie flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat są ustawione na false). Tylko do odczytu  boolean .

--------------------

Jeśli etykieta danych jest widoczna domyślnie, możesz ją ukryć domyślnie za pomocą metody Hide(). Jeśli etykieta danych nie jest widoczna domyślnie (IsVisible jest false), możesz sprawić, że będzie „widoczna domyślnie”, ustawiając flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat w stan true.

**Zwraca:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Ukrywa etykietę danych domyślnie, ustawiając wszystkie flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat w stan false. Po tym IsVisible będzie false.

--------------------

Jeśli etykieta danych nie jest widoczna domyślnie (IsVisible jest false), możesz sprawić, że będzie „widoczna domyślnie”, ustawiając flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat w stan true.

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

Zwraca nadrzędną serię wykresu. Tylko do odczytu [IChartSeries](../../com.aspose.slides/ichartseries).

**Zwraca:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Zwraca indeks określonej etykiety danych w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | Etykieta danych do znalezienia. |

**Zwraca:**
int - Indeks etykiety danych lub -1 jeśli etykieta danych nie pochodzi z tej kolekcji.