---
title: ChartCellCollection
second_title: Aspose.Slides dla Androida – referencja API Java
description: Reprezentuje kolekcję komórek z danymi.
type: docs
url: /pl/com.aspose.slides/chartcellcollection/
---
**Inheritance:**  
Dziedziczenie:
java.lang.Object

**All Implemented Interfaces:**  
Wszystkie zaimplementowane interfejsy:
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Represents collection of a cells with data.  
Reprezentuje kolekcję komórek z danymi.

## Methods  
## Metody

| Method | Description |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Zwraca adres zestawu komórek w skoroszycie. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Łączy ciąg znaków ze wszystkich wartości komórek. |
| [get_Item(int index)](#get-Item-int-) | Zwraca komórkę (IChartDataCell) według indeksu. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Dodaje nową komórkę do kolekcji. |
| [add(Object value)](#add-java.lang.Object-) | Tworzy [ChartDataCell](../../com.aspose.slides/chartdatacell) z określonej wartości i dodaje ją do kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa komórkę z kolekcji według indeksu. |
| [getCount()](#getCount--) | Pobiera liczbę komórek w kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Zwraca adres zestawu komórek w skoroszycie.

**Returns:**  
Zwraca:  
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

Łączy ciąg znaków ze wszystkich wartości komórek.

**Returns:**  
Zwraca:  
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

Zwraca komórkę (IChartDataCell) według indeksu.

**Parameters:**  
**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a cell. → Indeks komórki. |

**Returns:**  
Zwraca:  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Komórka z danymi.

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Dodaje nową komórkę do kolekcji.

**Parameters:**  
**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | New cell to add. → Nowa komórka do dodania. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Tworzy [ChartDataCell](../../com.aspose.slides/chartdatacell) z określonej wartości i dodaje ją do kolekcji.

**Parameters:**  
**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value. → Wartość. |

--------------------

Ta metoda dodaje arkusz roboczy o nazwie AUTO_DATA i umieszcza w nim wszystkie wartości. Jeśli używasz [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) do dodawania lub edytowania wartości komórek, upewnij się, że nie używasz tego arkusza. Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekraczać 16711680.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa komórkę z kolekcji według indeksu.

**Parameters:**  
**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a cell to remove. → Indeks komórki do usunięcia. |

### getCount() {#getCount--}
```
public final int getCount()
```

Pobiera liczbę komórek w kolekcji. int – tylko do odczytu.

**Returns:**  
Zwraca:  
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Returns:**  
Zwraca:  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - IGenericEnumerator, który może być używany do iteracji po kolekcji.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Returns:**  
Zwraca:  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - java.util.Iterator dla całej kolekcji.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. IDOMObject – tylko do odczytu.

**Returns:**  
Zwraca:  
com.aspose.slides.IDOMObject