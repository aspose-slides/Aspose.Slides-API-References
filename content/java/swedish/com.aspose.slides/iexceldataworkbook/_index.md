---
title: IExcelDataWorkbook
second_title: Aspose.Slides för Java API-referens
description: Representerar en arbetsbok som ger åtkomst till Excel-data för allmänt bruk.
type: docs
url: /sv/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Representerar en arbetsbok som ger åtkomst till Excel-data för allmänt bruk.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Retrieves a collection of cells from the workbook that match the specified formula. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Retrieves a cell from the specified worksheet using its index and cell coordinates. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Retrieves a cell from the specified worksheet using its name and cell coordinates. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook. |
| [getWorksheetNames()](#getWorksheetNames--) | Retrieves the names of all worksheets contained in the Excel workbook. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Hämtar en samling celler från arbetsboken som matchar den angivna formeln.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Utdata: 5
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formula | java.lang.String | En formel eller områdesuttryck (t.ex. "Sheet1!A1:B3") som används för att identifiera målcellar. |
| skipHiddenCells | boolean | Om true, kommer dolda celler (t.ex. i dolda rader eller kolumner) att uteslutas från resultatet. |

**Returnerar:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - En skrivskyddad lista med celler som matchar den angivna formeln.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Hämtar en cell från den angivna arbetsbladet med hjälp av dess index och cellkoordinater.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Nollbaserat index för arbetsbladet. |
| row | int | Nollbaserat radindex för cellen. |
| column | int | Nollbaserat kolumnindex för cellen. |

**Returnerar:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Hämtar en cell från det angivna arbetsbladet med dess namn och cellkoordinater.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | java.lang.String | Namnet på arbetsbladet. |
| row | int | Nollbaserat radindex för cellen. |
| column | int | Nollbaserat kolumnindex för cellen. |

**Returnerar:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Hämtar en cell från det angivna arbetsbladet med dess index och Excel-stil cellnamn (t.ex. "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetIndex | int | Nollbaserat index för arbetsbladet. |
| cellName | java.lang.String | Excel-stil cellreferens (t.ex. "A1", "C5"). |

**Returnerar:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Hämtar en cell från det angivna arbetsbladet med Excel-stil cellnamn (t.ex. "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | java.lang.String | Namnet på arbetsbladet. |
| cellName | java.lang.String | Excel-stil cellreferens (t.ex. "A1", "C5"). |

**Returnerar:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Hämtar en dictionary som innehåller index och namn på alla diagram i det angivna arbetsbladet i en Excel-arbetsbok.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheetName | java.lang.String | Namnet på arbetsbladet att söka efter diagram i. |

**Returnerar:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - En dictionary där nyckeln är diagrammets index och värdet är diagrammets namn.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Hämtar namnen på alla arbetsblad som finns i Excel-arbetsboken.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Returnerar:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - En lista med arbetsbladsnamn