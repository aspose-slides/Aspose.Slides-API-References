---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android Java API referencia
description: Egy munkafüzetet reprezentál, amely általános felhasználásra hozzáférést biztosít az Excel adatokhoz.
type: docs
url: /hu/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Egy munkafüzetet reprezentál, amely általános felhasználásra hozzáférést biztosít az Excel adatokhoz.
## Módszerek

| Method | Description |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Lekér egy cellagyűjteményt a munkafüzetből, amely megfelel a megadott képletnek. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Lekér egy cellát a megadott munkalapról az indexe és a cella koordinátái alapján. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Lekér egy cellát a megadott munkalapról a neve és a cella koordinátái alapján. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Lekér egy cellát a megadott munkalapról az indexe és az Excel-stílusú cellanév (pl. "B2") alapján. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Lekér egy cellát a megadott munkalapról Excel-stílusú cellanév (pl. "B2") alapján. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Lekér egy szótárat, amely tartalmazza az adott Excel munkafüzet munkalapján lévő összes diagram indexeit és neveit. |
| [getWorksheetNames()](#getWorksheetNames--) | Lekéri az Excel munkafüzettel tartalmazott összes munkalap nevét. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Lekér egy cellagyűjteményt a munkafüzetből, amely megfelel a megadott képletnek.

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
| formula | java.lang.String | Egy képlet vagy tartománykifejezés (pl. "Sheet1!A1:B3"), amely a célcellák azonosítására szolgál. |
| skipHiddenCells | boolean | Ha igaz, a rejtett cellák (pl. rejtett sorokban vagy oszlopokban) kizárásra kerülnek az eredményből. |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Írásvédett lista a megadott képlettel egyező cellákról.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Lekér egy cellát a megadott munkalapról az indexe és a cella koordinátái alapján.

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
| worksheetIndex | int | Nullától kezdődő index a munkalaphoz. |
| row | int | Nullától kezdődő sorindex a cellához. |
| column | int | Nullától kezdődő oszlopindex a cellához. |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

Lekér egy cellát a megadott munkalapról a neve és a cella koordinátái alapján.

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
| row | int | Nullától kezdődő sorindex a cellához. |
| column | int | Nullától kezdődő oszlopindex a cellához. |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Lekér egy cellát a megadott munkalapról az indexe és az Excel-stílusú cellanév (pl. "B2") alapján.

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
| worksheetIndex | int | Nullától kezdődő index a munkalaphoz. |
| cellName | java.lang.String | Az Excel-stílusú cellahivatkozás (pl. "A1", "C5"). |

**Visszatérési érték:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - A megadott helyen lévő cella.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Lekér egy cellát a megadott munkalapról Excel-stílusú cellanév (pl. "B2") alapján.

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

Lekér egy szótárat, amely tartalmazza az adott Excel munkafüzet munkalapján lévő összes diagram indexeit és neveit.

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
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Lekéri az Excel munkafüzettel tartalmazott összes munkalap nevét.

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