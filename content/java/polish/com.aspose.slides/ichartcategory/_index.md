---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje kategorie wykresu.
type: docs
url: /pl/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Reprezentuje kategorie wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getUseCell()](#getUseCell--) | Jeśli true, właściwość AsCell jest aktualna. |
| [getAsCell()](#getAsCell--) | Zwraca lub ustawia obiekt IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Zwraca lub ustawia obiekt IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Zwraca lub ustawia AsLiteral, jeśli UseCell jest false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Zwraca lub ustawia AsLiteral, jeśli UseCell jest false. |
| [getValue()](#getValue--) | Jeśli UseCell jest true, ta właściwość reprezentuje właściwość AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Jeśli UseCell jest true, ta właściwość reprezentuje właściwość AsCell.Value. |
| [getCachedValue()](#getCachedValue--) | Pobiera buforowaną wartość kategorii wykresu. |
| [getGroupingLevels()](#getGroupingLevels--) | Zarządzany kontener wartości poziomów grupowania kategorii wykresu. |
| [remove()](#remove--) | Usuwa kategorię z wykresu. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Jeśli true, właściwość AsCell jest aktualna. Inaczej mówiąc, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorię wielopoziomową). Jeśli false, właściwość AsLiteral jest aktualna. Inaczej mówiąc, arkusz NIE jest używany do przechowywania kategorii (i ten przypadek nie obsługuje wielopoziomowych kategorii). Tylko do odczytu boolean.

--------------------

Aby zmienić wartość tej właściwości (dla wszystkich kategorii w kolekcji), ustaw nową wartość właściwości [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Zwraca:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Zwraca lub ustawia obiekt IChartDataCell. Jeśli kategoria jest wielopoziomowa, używany jest obiekt IChartDataCell dla poziomu "0". Odczyt/zapis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Zwraca lub ustawia obiekt IChartDataCell. Jeśli kategoria jest wielopoziomowa, używany jest obiekt IChartDataCell dla poziomu "0". Odczyt/zapis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Zwraca lub ustawia AsLiteral, jeśli UseCell jest false. Odczyt/zapis Object.

**Zwraca:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Zwraca lub ustawia AsLiteral, jeśli UseCell jest false. Odczyt/zapis Object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Jeśli UseCell jest true, ta właściwość reprezentuje właściwość AsCell.Value. Jeśli UseCell jest false, ta właściwość reprezentuje właściwość AsLiteral. Odczyt/zapis Object.

**Zwraca:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Jeśli UseCell jest true, ta właściwość reprezentuje właściwość AsCell.Value. Jeśli UseCell jest false, ta właściwość reprezentuje właściwość AsLiteral. Odczyt/zapis Object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Pobiera buforowaną wartość kategorii wykresu. Tylko do odczytu [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Wypisz wszystkie buforowane wartości kategorii wykresu.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Zarządzany kontener wartości poziomów grupowania kategorii wykresu. Kategoria wielopoziomowa zawiera więcej niż jeden poziom grupowania. Indeksowanie poziomów grupowania zaczyna się od zera. Tylko do odczytu [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Zwraca:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Usuwa kategorię z wykresu.