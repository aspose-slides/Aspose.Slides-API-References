---
title: ExcelDataWorkbook
second_title: Aspose.Slides Java API referencia
description: Egy munkafüzetet képvisel, amely általános felhasználásra hozzáférést biztosít az Excel adatokhoz.
type: docs
url: /hu/com.aspose.slides/exceldataworkbook/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Egy munkafüzetet képvisel, amely általános felhasználásra hozzáférést biztosít az Excel adatokhoz.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Initializes a new instance using the specified file path. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Initializes a new instance of the class using the provided stream. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Retrieves a collection of cells from the workbook that match the specified formula. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Retrieves a cell from the specified worksheet using its index and cell coordinates. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Retrieves a cell from the specified worksheet using its name and cell coordinates. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook. |
| [getWorksheetNames()](#getWorksheetNames--) | Retrieves the names of all worksheets contained in the Excel workbook. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

Új példányt inicializál a megadott fájlúttal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filePath | java.lang.String | Az Excel munkafüzet fájl teljes elérési útja. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

Új példányt inicializál a megadott adatfolyammal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Egy adatfolyam, amely az Excel munkafüzet adatokat tartalmazza. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

A munkafüzetből olyan cellagyűjteményt ad vissza, amely megfelel a megadott képletnek.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Kimenet: 5
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | A cellákat azonosító képlet vagy tartománykifejezés (pl. "Sheet1!A1:B3"). |
| skipHiddenCells | boolean | Ha true, a rejtett cellák (pl. rejtett sorokban vagy oszlopokban) kizárásra kerülnek az eredményből. |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Egy csak olvasható lista a megadott képlettel egyező cellákról.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

A megadott munkalapon az index és a cellakoordináták alapján visszaad egy cellát.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | int | A munkalap nulla-alapú indexe. |
| row | int | A cella nulla-alapú sorindexe. |
| column | int | A cella nulla-alapú oszlopindexe. |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

A megadott munkalapról a munkalap neve és a cellakoordináták alapján visszaad egy cellát.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | java.lang.String | A munkalap neve. |
| row | int | A cella nulla-alapú sorindexe. |
| column | int | A cella nulla-alapú oszlopindexe. |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

A megadott munkalapból az index és az Excel-stílusú cellanév (pl. "B2") alapján visszaad egy cellát.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetIndex | int | A munkalap nulla-alapú indexe. |
| cellName | java.lang.String | Az Excel-stílusú cellahivatkozás (pl. "A1", "C5"). |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

A megadott munkalapról Excel-stílusú cellanév (pl. "B2") alapján visszaad egy cellát.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | java.lang.String | A munkalap neve. |
| cellName | java.lang.String | Az Excel-stílusú cellahivatkozás (pl. "A1", "C5"). |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Egy szótárt ad vissza, amely tartalmazza az adott Excel munkafüzet munkalapjában lévő összes diagram indexeit és neveit.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| worksheetName | java.lang.String | A diagramok keresésére szolgáló munkalap neve. |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Egy szótár, ahol a kulcs a diagram indexe, az érték pedig a diagram neve.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

Az Excel munkafüzetben található összes munkalap nevét adja vissza.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - A munkalap nevek listája