---
title: IChartCellCollection
second_title: Aspose.Slides dla Androida - odwołanie do API Java
description: Reprezentuje kolekcję komórek z danymi.
type: docs
url: /pl/com.aspose.slides/ichartcellcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Reprezentuje kolekcję komórek z danymi.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Zwraca adres zestawu komórek w skoroszycie. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | Łączy ciągi znaków ze wszystkich wartości komórek. |
| [get_Item(int index)](#get-Item-int-) | Zwraca komórkę (IChartDataCell) według indeksu. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Dodaje nową komórkę do kolekcji. |
| [add(Object value)](#add-java.lang.Object-) | Tworzy [IChartDataCell](../../com.aspose.slides/ichartdatacell) z określonej wartości i dodaje go do kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa komórkę z kolekcji według indeksu. |
| [getCount()](#getCount--) | Pobiera liczbę komórek w kolekcji. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


Zwraca adres zestawu komórek w skoroszycie.

**Zwraca:**
java.lang.String - Adres zestawu komórek w skoroszycie String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


Łączy ciągi znaków ze wszystkich wartości komórek.

**Zwraca:**
java.lang.String - Wynikowy ciąg znaków String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


Zwraca komórkę (IChartDataCell) według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks komórki. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Komórka z danymi.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


Dodaje nową komórkę do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Nowa komórka do dodania. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


Tworzy [IChartDataCell](../../com.aspose.slides/ichartdatacell) z określonej wartości i dodaje go do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object | Wartość.

--------------------

Ta metoda dodaje arkusz o nazwie AUTO_DATA i wstawia tam wszystkie wartości. Jeśli używasz [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) do dodawania lub edytowania wartości komórek, upewnij się, że nie używasz tego arkusza. Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekroczyć 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa komórkę z kolekcji według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks komórki do usunięcia. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Pobiera liczbę komórek w kolekcji. Tylko do odczytu int.

**Zwraca:**
int