---
title: ExcelDataWorkbook
second_title: Aspose.Slides Androidra Java API hivatkozással
description: Egy munkafüzetet jelent, amely általános használatra biztosít hozzáférést az Excel adatokhoz.
type: docs
url: /hu/com.aspose.slides/exceldataworkbook/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Egy munkafüzetet képvisel, amely általános használatra biztosít hozzáférést az Excel adatokhoz.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Új példányt inicializál a megadott fájlúttal. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Új példányt inicializál az osztályból a megadott adatfolyam használatával. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | A munkafüzetből lekér egy cellagyűjteményt, amely megfelel a megadott képletnek. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | A megadott munkalapról lekér egy cellát az index és a cella koordináták alapján. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | A megadott munkalapról lekér egy cellát a neve és a cella koordináták alapján. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | A megadott munkalapról lekér egy cellát az index és az Excel-stílusú cellanév (pl. "B2") alapján. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | A megadott munkalapról lekér egy cellát az Excel-stílusú cellanév (pl. "B2") alapján. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Lekér egy szótárat, amely tartalmazza az összes diagram indexeit és nevét a megadott Excel munkafüzet munkalapján. |
| [getWorksheetNames()](#getWorksheetNames--) | Lekérdezi az Excel munkafüzetben található összes munkalap nevét. |
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


Új példányt inicializál az osztályból a megadott adatfolyam használatával.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Az Excel munkafüzet adatot tartalmazó adatfolyam. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


A munkafüzetből lekér egy cellagyűjteményt, amely megfelel a megadott képletnek.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Kimenet: 5
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | Egy képlet vagy tartománykifejezés (pl. "Sheet1!A1:B3") a célcellák azonosításához. |
| skipHiddenCells | boolean | Ha igaz, a rejtett cellák (pl. rejtett sorokban vagy oszlopokban) kizárásra kerülnek az eredményből. |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - A megadott képlettel egyező cellák csak-olvasású listája.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


A megadott munkalapról lekér egy cellát az index és a cella koordináták alapján.

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
| worksheetIndex | int | Nullával kezdődő index a munkalaphoz. |
| row | int | Nullával kezdődő sorindex a cellához. |
| column | int | Nullával kezdődő oszlopindex a cellához. |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen található cella.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```


A megadott munkalapról lekér egy cellát a neve és a cella koordináták alapján.

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
| row | int | Nullával kezdődő sorindex a cellához. |
| column | int | Nullával kezdődő oszlopindex a cellához. |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen található cella.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```


A megadott munkalapról lekér egy cellát az index és az Excel-stílusú cellanév (pl. "B2") alapján.

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
| worksheetIndex | int | Nullával kezdődő index a munkalaphoz. |
| cellName | java.lang.String | Az Excel-stílusú cellahivatkozás (pl. "A1", "C5"). |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen található cella.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```


A megadott munkalapról lekér egy cellát az Excel-stílusú cellanév (pl. "B2") alapján.

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
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen található cella.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Lekér egy szótárat, amely tartalmazza az összes diagram indexeit és nevét a megadott Excel munkafüzet munkalapján.

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


Lekérdezi az Excel munkafüzetben található összes munkalap nevét.

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - A munkalapneveket tartalmazó lista