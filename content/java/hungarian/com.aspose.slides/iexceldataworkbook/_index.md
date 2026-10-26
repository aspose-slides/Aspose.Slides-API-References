---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Egy munkafüzetet képvisel, amely általános felhasználásra hozzáférést biztosít az Excel adatokhoz.
type: docs
url: /hu/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Egy munkafüzetet képvisel, amely általános felhasználásra hozzáférést biztosít az Excel adatokhoz.
## Módszerek

| Módszer | Leírás |
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

Gyűjteményt ad vissza a munkafüzetből a megadott képlettel egyező cellákról.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Kimenet: 5
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | Képlet vagy tartománykifejezés (pl. "Sheet1!A1:B3"), amely a célcellákat azonosítja. |
| skipHiddenCells | boolean | Ha igaz, a rejtett cellák (pl. rejtett sorokban vagy oszlopokban) kizárásra kerülnek az eredményből. |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Írásvédett lista a megadott képlettel egyező cellákról.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Cellát ad vissza a megadott munkalapból a index és a cellakoordináták alapján.

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
| worksheetIndex | int | A munkalap nullától kezdődő indexe. |
| row | int | A cella nullától kezdődő sorindexe. |
| column | int | A cella nullától kezdődő oszlopindexe. |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

Cellát ad vissza a megadott munkalapról a neve és a cellakoordináták alapján.

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
| row | int | A cella nullától kezdődő sorindexe. |
| column | int | A cella nullától kezdődő oszlopindexe. |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Cellát ad vissza a megadott munkalapról az index és az Excel-stílusú cellanév alapján (pl. "B2").

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
| worksheetIndex | int | A munkalap nullától kezdődő indexe. |
| cellName | java.lang.String | Az Excel-stílusú cellahivatkozás (pl. "A1", "C5"). |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Cellát ad vissza a megadott munkalapról az Excel-stílusú cellanév alapján (pl. "B2").

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
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Szótárt ad vissza, amely az Excel munkalapon lévő összes diagram indexeit és neveit tartalmazza.

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
| worksheetName | java.lang.String | A diagramokat kereső munkalap neve. |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Szótár, ahol a kulcs a diagram index, az érték pedig a diagram neve.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Visszaadja az Excel munkafüzetben szereplő összes munkalap nevét.

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Az összes munkalap nevének listája