---
title: ChartCategory
second_title: Referencja API Aspose.Slides dla Java
description: Reprezentuje kategorie wykresu.
type: docs
url: /pl/com.aspose.slides/chartcategory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Reprezentuje kategorie wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getUseCell()](#getUseCell--) | Jeśli true, to właściwość AsCell jest aktualna. |
| [getAsCell()](#getAsCell--) | Zwraca lub ustawia obiekt IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Zwraca lub ustawia obiekt IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Zwraca lub ustawia obiekt AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Zwraca lub ustawia obiekt AsLiteral. |
| [getValue()](#getValue--) | Jeśli UseCell jest true, to ta właściwość reprezentuje właściwość AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Jeśli UseCell jest true, to ta właściwość reprezentuje właściwość AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Zarządzany kontener wartości poziomów grupowania kategorii wykresu. |
| [remove()](#remove--) | Usuwa kategorię z wykresu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Jeśli true, to właściwość AsCell jest aktualna. Innymi słowy, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorię wielopoziomową). Jeśli false, to właściwość AsLiteral jest aktualna. Innymi słowy, arkusz NIE jest używany do przechowywania kategorii (i ten przypadek nie obsługuje kategorii wielopoziomowych). Boolean tylko do odczytu.

--------------------

Aby zmienić wartość tej właściwości (dla wszystkich kategorii w kolekcji), ustaw nową wartość w właściwości ChartCategoryCollection.UseCells.

**Zwraca:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Zwraca lub ustawia obiekt IChartDataCell. Jeśli kategoria jest wielopoziomowa, używany jest obiekt IChartDataCell dla poziomu "0". Odczyt/zapis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Zwraca lub ustawia obiekt IChartDataCell. Jeśli kategoria jest wielopoziomowa, używany jest obiekt IChartDataCell dla poziomu "0". Odczyt/zapis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Zwraca lub ustawia obiekt AsLiteral. Odczyt/zapis Object.

**Zwraca:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Zwraca lub ustawia obiekt AsLiteral. Odczyt/zapis Object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Jeśli UseCell jest true, to ta właściwość reprezentuje właściwość AsCell.Value. Jeśli UseCell jest false, to ta właściwość reprezentuje właściwość AsLiteral. Odczyt/zapis Object.

**Zwraca:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Jeśli UseCell jest true, to ta właściwość reprezentuje właściwość AsCell.Value. Jeśli UseCell jest false, to ta właściwość reprezentuje właściwość AsLiteral. Odczyt/zapis Object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Zarządzany kontener wartości poziomów grupowania kategorii wykresu. Kategoria wielopoziomowa zawiera więcej niż jeden poziom grupowania. Indeksowanie poziomów grupowania rozpoczyna się od zera. Tylko do odczytu [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Zwraca:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Usuwa kategorię z wykresu.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject