---
title: IDataLabelCollection
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji API Java
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
| [get_Item(int index)](#get-Item-int-) | Gets the data label for the data point with the specified index. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Returns default format of all data labels in the collection. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Represents data labels leader lines format. |
| [isVisible()](#isVisible--) | False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). |
| [hide()](#hide--) | Make data label hidden by default by setting all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to false state. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Gets the number of visible data labels in the collection. |
| [getCount()](#getCount--) | Gets the number of all data labels in the collection. |
| [getParentSeries()](#getParentSeries--) | Returns parent chart series. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Returns an index of the specified DataLabel in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Pobiera etykietę danych dla punktu danych o określonym indeksie.

--------------------

Alternatywny sposób uzyskania dostępu do etykiety danych to:
- getSeries().getDataPoints().get_Item(i).getLabel()
- zarządzaj właściwościami etykiety.

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
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


False oznacza, że etykieta danych nie jest widoczna domyślnie (a więc wszystkie flagi Show\*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat są ustawione na false). Tylko do odczytu  boolean .

--------------------

Jeśli etykieta danych jest domyślnie widoczna, możesz ją ukryć domyślnie za pomocą metody Hide(). Natomiast jeśli etykieta danych nie jest domyślnie widoczna (IsVisible jest false), możesz ustawić etykietę jako „widoczną domyślnie” ustawiając flagi Show\*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat na stan true.

**Zwraca:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Ustaw etykietę danych jako ukrytą domyślnie, ustawiając wszystkie flagi Show\*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat w stanie false. IsVisible będzie false po tej operacji.

--------------------

Jeśli etykieta danych nie jest domyślnie widoczna (IsVisible jest false), możesz ustawić etykietę jako „widoczną domyślnie” ustawiając flagi Show\*-flags (ShowValue, ...) właściwości DefaultDataLabelFormat na stan true.

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


Zwraca indeks określonej DataLabel w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel do znalezienia. |

**Zwraca:**
int - indeks DataLabel lub -1, jeśli DataLabel nie pochodzi z tej kolekcji.