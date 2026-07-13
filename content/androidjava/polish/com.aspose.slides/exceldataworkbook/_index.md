---
title: ExcelDataWorkbook
second_title: Aspose.Slides dla Androida – referencja API Java
description: Reprezentuje skoroszyt, który zapewnia dostęp do danych Excel do ogólnego użytku.
type: docs
url: /pl/com.aspose.slides/exceldataworkbook/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Reprezentuje skoroszyt, który zapewnia dostęp do danych Excel do ogólnego użytku.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Inicjalizuje nową instancję przy użyciu określonej ścieżki do pliku. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Inicjalizuje nową instancję klasy przy użyciu dostarczonego strumienia. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Pobiera kolekcję komórek z skoroszytu, które pasują do określonego wzoru. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Pobiera komórkę z określonego arkusza przy użyciu jego indeksu i współrzędnych komórki. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Pobiera komórkę z określonego arkusza przy użyciu jego nazwy i współrzędnych komórki. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Pobiera komórkę z określonego arkusza przy użyciu jego indeksu i nazwy komórki w stylu Excel (np. "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Pobiera komórkę z określonego arkusza przy użyciu nazwy komórki w stylu Excel (np. "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Pobiera słownik zawierający indeksy i nazwy wszystkich wykresów w określonym arkuszu skoroszytu Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Pobiera nazwy wszystkich arkuszy zawartych w skoroszycie Excel. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```


Inicjalizuje nową instancję przy użyciu określonej ścieżki do pliku.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| filePath | java.lang.String | Pełna ścieżka do pliku skoroszytu Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```


Inicjalizuje nową instancję klasy przy użyciu dostarczonego strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień zawierający dane skoroszytu Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Pobiera kolekcję komórek z skoroszytu, które pasują do określonego wzoru.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Wyjście: 5
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| formula | java.lang.String | Wyrażenie formuły lub zakresu (np. "Sheet1!A1:B3") używane do określenia docelowych komórek. |
| skipHiddenCells | boolean | Jeśli true, ukryte komórki (np. w ukrytych wierszach lub kolumnach) zostaną wykluczone z wyniku. |

**Zwraca:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Lista komórek w trybie tylko do odczytu, które pasują do określonego wzoru.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Pobiera komórkę z określonego arkusza przy użyciu jego indeksu i współrzędnych komórki.

--------------------

> ```
> Przykład:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza zaczynający się od zera. |
| row | int | Indeks wiersza komórki zaczynający się od zera. |
| column | int | Indeks kolumny komórki zaczynający się od zera. |

**Zwraca:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Komórka w określonym miejscu.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```


Pobiera komórkę z określonego arkusza przy użyciu jego nazwy i współrzędnych komórki.

--------------------

> ```
> Przykład:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | java.lang.String | Nazwa arkusza. |
| row | int | Indeks wiersza komórki zaczynający się od zera. |
| column | int | Indeks kolumny komórki zaczynający się od zera. |

**Zwraca:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Komórka w określonym miejscu.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Pobiera komórkę z określonego arkusza przy użyciu jego indeksu i nazwy komórki w stylu Excel (np. "B2").

--------------------

> ```
> Przykład:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza zaczynający się od zera. |
| cellName | java.lang.String | Odwołanie do komórki w stylu Excel (np. "A1", "C5"). |

**Zwraca:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Komórka w określonym miejscu.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```


Pobiera komórkę z określonego arkusza przy użyciu nazwy komórki w stylu Excel (np. "B2").

--------------------

> ```
> Przykład:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | java.lang.String | Nazwa arkusza. |
| cellName | java.lang.String | Odwołanie do komórki w stylu Excel (np. "A1", "C5"). |

**Zwraca:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Komórka w określonym miejscu.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Pobiera słownik zawierający indeksy i nazwy wszystkich wykresów w określonym arkuszu skoroszytu Excel.

--------------------

> ```
> Przykład:
>  
  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | java.lang.String | Nazwa arkusza, w którym wyszukiwane są wykresy. |

**Zwraca:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Słownik, w którym kluczem jest indeks wykresu, a wartością jest nazwa wykresu.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```


Pobiera nazwy wszystkich arkuszy zawartych w skoroszycie Excel.

--------------------

> ```
> Przykład:
>  
  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```


**Zwraca:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Lista nazw arkuszy