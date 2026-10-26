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
| [getUseCell()](#getUseCell--) | If true then AsCell property is actual. |
| [getAsCell()](#getAsCell--) | Returns or sets IChartDataCell object. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets IChartDataCell object. |
| [getAsLiteral()](#getAsLiteral--) | Returns or sets AsLiteral if UseCell is false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returns or sets AsLiteral if UseCell is false. |
| [getValue()](#getValue--) | If UseCell is true then this property represents AsCell.Value property. |
| [setValue(Object value)](#setValue-java.lang.Object-) | If UseCell is true then this property represents AsCell.Value property. |
| [getGroupingLevels()](#getGroupingLevels--) | Managed container of the values of the chart category grouping levels. |
| [remove()](#remove--) | Removes category from chart. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Jeśli true, to właściwość AsCell jest aktualna. Innymi słowy, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorię wielopoziomową). Jeśli false, to właściwość AsLiteral jest aktualna. Innymi słowy, arkusz NIE jest używany do przechowywania kategorii (i ten przypadek nie obsługuje kategorii wielopoziomowych). Boolean tylko do odczytu.

--------------------

Aby zmienić wartość tej właściwości (dla wszystkich kategorii w kolekcji), ustaw nową wartość właściwości [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Zwraca:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Zwraca lub ustawia obiekt IChartDataCell. Jeśli kategoria jest wielopoziomowa, używany jest obiekt IChartDataCell dla poziomu “0”. Odczyt/zapis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Zwraca lub ustawia obiekt IChartDataCell. Jeśli kategoria jest wielopoziomowa, używany jest obiekt IChartDataCell dla poziomu “0”. Odczyt/zapis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

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


Jeśli UseCell jest true, to ta właściwość reprezentuje właściwość AsCell.Value. Jeśli UseCell jest false, to ta właściwość reprezentuje właściwość AsLiteral. Odczyt/zapis Object.

**Zwraca:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Jeśli UseCell jest true, to ta właściwość reprezentuje właściwość AsCell.Value. Jeśli UseCell jest false, to ta właściwość reprezentuje właściwość AsLiteral. Odczyt/zapis Object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |

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