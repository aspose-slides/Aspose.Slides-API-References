---
title: ExcelDataWorkbook
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en arbetsbok som ger åtkomst till Excel-data för allmänt bruk.
type: docs
url: /sv/com.aspose.slides/exceldataworkbook/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Representerar en arbetsbok som ger åtkomst till Excel-data för allmänt bruk.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Initierar en ny instans med den angivna filsökvägen. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Initierar en ny instans av klassen med den angivna strömmen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Hämtar en samling celler från arbetsboken som matchar den angivna formeln. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Hämtar en cell från det angivna kalkylbladet med hjälp av dess index och cellkoordinater. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Hämtar en cell från det angivna kalkylbladet med hjälp av dess namn och cellkoordinater. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Hämtar en cell från det angivna kalkylbladet med hjälp av dess index och Excel-liknande cellnamn (t.ex. "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Hämtar en cell från det angivna kalkylbladet med hjälp av Excel-liknande cellnamn (t.ex. "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Hämtar en dictionary som innehåller index och namn för alla diagram i det angivna kalkylbladet i en Excel-arbetsbok. |
| [getWorksheetNames()](#getWorksheetNames--) | Hämtar namnen på alla kalkylblad i Excel-arbetsboken. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```


Initierar en ny instans med den angivna filsökvägen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Den fullständiga sökvägen till Excel-arbetsbokens fil. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```


Initierar en ny instans av klassen med den angivna strömmen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | En ström som innehåller Excel-arbetsbokens data. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Hämtar en samling celler från arbetsboken som matchar den angivna formeln.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Utdata: 5
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formula | java.lang.String | Ett formulär eller intervalluttryck (t.ex. "Sheet1!A1:B3") som används för att identifiera målcellern. |
| skipHiddenCells | boolean | Om true, kommer dolda celler (t.ex. i dolda rader eller kolumner) att uteslutas från resultatet. |

**Returnerar:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - En skrivskyddad lista med celler som matchar den angivna formeln.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Hämtar en cell från det angivna kalkylbladet med hjälp av dess index och cellkoordinater.

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

**Returnerar:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```


Hämtar en cell från det angivna kalkylbladet med hjälp av dess namn och cellkoordinater.

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

**Returnerar:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Hämtar en cell från det angivna kalkylbladet med hjälp av dess index och Excel-liknande cellnamn (t.ex. "B2").

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
| cellName | java.lang.String | Excel-liknande cellreferens (t.ex. "A1", "C5"). |

**Returnerar:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```


Hämtar en cell från det angivna kalkylbladet med hjälp av Excel-liknande cellnamn (t.ex. "B2").

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
| cellName | java.lang.String | Excel-liknande cellreferens (t.ex. "A1", "C5"). |

**Returnerar:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Cellen på den angivna platsen.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Hämtar en dictionary som innehåller index och namn för alla diagram i det angivna kalkylbladet i en Excel-arbetsbok.

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
| worksheetName | java.lang.String | Namnet på kalkylbladet som ska genomsökas efter diagram. |

**Returnerar:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - En dictionary där nyckeln är diagramindexet och värdet är diagramnamnet.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```


Hämtar namnen på alla kalkylblad i Excel-arbetsboken.

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - En lista med kalkylbladsnamn