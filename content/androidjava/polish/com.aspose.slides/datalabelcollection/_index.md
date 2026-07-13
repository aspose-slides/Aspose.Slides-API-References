---
title: DataLabelCollection
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje etykiety serii.
type: docs
url: /pl/com.aspose.slides/datalabelcollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
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
| [isVisible()](#isVisible--) | False oznacza, że etykieta danych nie jest widoczna domyślnie (a więc wszystkie flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat są ustawione na false). |
| [hide()](#hide--) | Ukryj etykietę danych domyślnie, ustawiając wszystkie flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat w stan false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Pobiera liczbę widocznych etykiet danych w kolekcji. |
| [getCount()](#getCount--) | Pobiera liczbę wszystkich etykiet danych w kolekcji. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Pobiera domyślny format etykiet danych. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Reprezentuje format linii prowadzących etykiet danych. |
| [getParentSeries()](#getParentSeries--) | Pobiera serię nadrzędną. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Zwraca indeks określonej DataLabel w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera etykietę danych dla punktu danych o określonym indeksie. |
| [getSlide()](#getSlide--) | Zwraca slajd nadrzędny obiektu FillFormat. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację nadrzędną obiektu FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Zwraca wykres nadrzędny. tylko do odczytu [IChart](../../com.aspose.slides/ichart).

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

False oznacza, że etykieta danych nie jest widoczna domyślnie (a więc wszystkie flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat są ustawione na false). tylko do odczytu boolean.

--------------------

Jeśli etykieta danych jest widoczna domyślnie, możesz ukryć ją domyślnie za pomocą metody Hide(). Natomiast jeśli etykieta danych nie jest widoczna domyślnie (IsVisible jest false), możesz ustawić etykietę jako "widoczną domyślnie" ustawiając flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat na stan true.

**Zwraca:**  
boolean
### hide() {#hide--}
```
public final void hide()
```

Ukryj etykietę danych domyślnie, ustawiając wszystkie flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat w stan false. Po tym IsVisible będzie false.

--------------------

Jeśli etykieta danych nie jest widoczna domyślnie (IsVisible jest false), możesz ustawić etykietę jako "widoczną domyślnie" ustawiając flagi Show* (ShowValue, ...) właściwości DefaultDataLabelFormat w stan true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Pobiera liczbę widocznych etykiet danych w kolekcji. tylko do odczytu int.

**Zwraca:**  
int
### getCount() {#getCount--}
```
public final int getCount()
```

Pobiera liczbę wszystkich etykiet danych w kolekcji. tylko do odczytu int.

**Zwraca:**  
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Pobiera domyślny format etykiet danych. tylko do odczytu [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Zwraca:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Reprezentuje format linii prowadzących etykiet danych. tylko do odczytu [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Pobiera serię nadrzędną. tylko do odczytu [IChartSeries](../../com.aspose.slides/ichartseries).

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
int - Indeks DataLabel lub -1, jeśli DataLabel nie pochodzi z tej kolekcji.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Pobiera etykietę danych dla punktu danych o określonym indeksie.

--------------------

Alternatywny sposób dostępu do etykiety to: - series.getDataPoints().get_Item(i).getLabel() - zarządzanie właściwościami etykiety.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**  
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd nadrzędny obiektu FillFormat. tylko do odczytu [BaseSlide](../../com.aspose.slides/baseslide).

**Zwraca:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację nadrzędną obiektu FillFormat. tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**  
[IPresentation](../../com.aspose.slides/ipresentation)