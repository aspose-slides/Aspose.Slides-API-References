---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje skoroszyt, który umożliwia dostęp do danych Excel do ogólnego użytku.
type: docs
url: /pl/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Reprezentuje skoroszyt, który umożliwia dostęp do danych Excel do ogólnego użytku.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Pobiera kolekcję komórek z skoroszytu, które pasują do podanej formuły. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Pobiera komórkę z określonego arkusza, używając jej indeksu oraz współrzędnych komórki. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Pobiera komórkę z określonego arkusza, używając jej nazwy oraz współrzędnych komórki. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Pobiera komórkę z określonego arkusza, używając jej indeksu oraz nazwy komórki w stylu Excel (np. "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Pobiera komórkę z określonego arkusza, używając nazwy komórki w stylu Excel (np. "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Pobiera słownik zawierający indeksy i nazwy wszystkich wykresów w określonym arkuszu skoroszytu Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Pobiera nazwy wszystkich arkuszy zawartych w skoroszycie Excel. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Pobiera kolekcję komórek z skoroszytu, które pasują do podanej formuły.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Wyjście: 5
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| formula | java.lang.String | Formuła lub wyrażenie zakresu (np. "Sheet1!A1:B3") używane do określenia docelowych komórek. |
| skipHiddenCells | boolean | Jeśli true, ukryte komórki (np. w ukrytych wierszach lub kolumnach) zostaną wykluczone z wyniku. |

**Zwraca:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Lista komórek tylko do odczytu, które pasują do podanej formuły.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Pobiera komórkę z określonego arkusza, używając jej indeksu oraz współrzędnych komórki.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza, liczony od zera. |
| row | int | Indeks wiersza komórki, liczony od zera. |
| column | int | Indeks kolumny komórki, liczony od zera. |

**Zwraca:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Komórka w określonej lokalizacji.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

Pobiera komórkę z określonego arkusza, używając jej nazwy oraz współrzędnych komórki.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | java.lang.String | Nazwa arkusza. |
| row | int | Indeks wiersza komórki, liczony od zera. |
| column | int | Indeks kolumny komórki, liczony od zera. |

**Zwraca:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Komórka w określonej lokalizacji.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Pobiera komórkę z określonego arkusza, używając jej indeksu oraz nazwy komórki w stylu Excel (np. "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza, liczony od zera. |
| cellName | java.lang.String | Odniesienie do komórki w stylu Excel (np. "A1", "C5"). |

**Zwraca:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Komórka w określonej lokalizacji.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Pobiera komórkę z określonego arkusza, używając nazwy komórki w stylu Excel (np. "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | java.lang.String | Nazwa arkusza. |
| cellName | java.lang.String | Odniesienie do komórki w stylu Excel (np. "A1", "C5"). |

**Zwraca:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Komórka w określonej lokalizacji.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Pobiera słownik zawierający indeksy i nazwy wszystkich wykresów w określonym arkuszu skoroszytu Excel.

--------------------

> ```
> Example:
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
| worksheetName | java.lang.String | Nazwa arkusza, w którym mają zostać wyszukane wykresy. |

**Zwraca:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Słownik, w którym kluczem jest indeks wykresu, a wartością – nazwa wykresu.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Pobiera nazwy wszystkich arkuszy zawartych w skoroszycie Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Zwraca:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Lista nazw arkuszy