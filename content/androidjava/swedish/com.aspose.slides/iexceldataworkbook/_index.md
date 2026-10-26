---
title: IExcelDataWorkbook
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en arbetsbok som ger åtkomst till Excel-data för allmän användning.
type: docs
url: /sv/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Representerar en arbetsbok som ger åtkomst till Excel-data för allmän användning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Hämtar en samling celler från arbetsboken som matchar den angivna formeln. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Hämtar en cell från det angivna kalkylbladet med dess index och cellkoordinater. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Hämtar en cell från det angivna kalkylbladet med dess namn och cellkoordinater. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Hämtar en cell från det angivna kalkylbladet med dess index och Excel-stil cellnamn (t.ex. "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Hämtar en cell från det angivna kalkylbladet med Excel-stil cellnamn (t.ex. "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Hämtar en ordbok som innehåller index och namn för alla diagram i det angivna kalkylbladet i en Excel-arbetsbok. |
| [getWorksheetNames()](#getWorksheetNames--) | Hämtar namnen på alla kalkylblad som finns i Excel-arbetsboken. |
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
| formula | java.lang.String | En formel eller områdeuttryck (t.ex. "Sheet1!A1:B3") som används för att identifiera målcellerna. |
| skipHiddenCells | boolean | Om true, kommer dolda celler (t.ex. i dolda rader eller kolumner) att uteslutas från resultatet. |

**Returvärde:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - En skrivskyddad lista med celler som matchar den angivna formeln.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Hämtar en cell från det angivna kalkylbladet med dess index och cellkoordinater.

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
| worksheetIndex | int | Nollbaserat index för kalkylbladet. |
| row | int | Nollbaserat radindex för cellen. |
| column | int | Nollbaserat kolumnindex för cellen. |

**Returvärde:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Hämtar en cell från det angivna kalkylbladet med dess namn och cellkoordinater.

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
| worksheetName | java.lang.String | Namnet på kalkylbladet. |
| row | int | Nollbaserat radindex för cellen. |
| column | int | Nollbaserat kolumnindex för cellen. |

**Returvärde:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Hämtar en cell från det angivna kalkylbladet med dess index och Excel-stil cellnamn (t.ex. "B2").

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
| worksheetIndex | int | Nollbaserat index för kalkylbladet. |
| cellName | java.lang.String | Excel-stil cellreferens (t.ex. "A1", "C5"). |

**Returvärde:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Hämtar en cell från det angivna kalkylbladet med Excel-stil cellnamn (t.ex. "B2").

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
| worksheetName | java.lang.String | Namnet på kalkylbladet. |
| cellName | java.lang.String | Excel-stil cellreferens (t.ex. "A1", "C5"). |

**Returvärde:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Hämtar en ordbok som innehåller index och namn för alla diagram i det angivna kalkylbladet i en Excel-arbetsbok.

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
| worksheetName | java.lang.String | Namnet på kalkylbladet att söka efter diagram i. |

**Returvärde:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - En ordbok där nyckeln är diagramindexet och värdet är diagramnamnet.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Hämtar namnen på alla kalkylblad som finns i Excel-arbetsboken.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Returvärde:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - En lista med kalkylbladsnamn