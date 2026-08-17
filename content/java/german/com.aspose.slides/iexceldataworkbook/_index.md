---
title: IExcelDataWorkbook
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Arbeitsmappe dar, die Zugriff auf Excel-Daten für die allgemeine Verwendung bietet.
type: docs
url: /de/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Stellt eine Arbeitsmappe dar, die Zugriff auf Excel-Daten für die allgemeine Verwendung bietet.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Ruft eine Sammlung von Zellen aus der Arbeitsmappe ab, die der angegebenen Formel entsprechen. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt ab, wobei dessen Index und Zellkoordinaten verwendet werden. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt ab, wobei dessen Name und Zellkoordinaten verwendet werden. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt ab, wobei dessen Index und der Excel-artige Zellname (z.B. "B2") verwendet werden. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt ab, wobei der Excel-artige Zellname (z.B. "B2") verwendet wird. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Ruft ein Dictionary ab, das die Indizes und Namen aller Diagramme im angegebenen Arbeitsblatt einer Excel-Arbeitsmappe enthält. |
| [getWorksheetNames()](#getWorksheetNames--) | Ruft die Namen aller Arbeitsblätter in der Excel-Arbeitsmappe ab. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Ruft eine Sammlung von Zellen aus der Arbeitsmappe ab, die der angegebenen Formel entsprechen.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Ausgabe: 5
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | java.lang.String | Eine Formel- oder Bereichsausdruck (z.B. „Sheet1!A1:B3“), der zur Identifizierung der Zielzellen verwendet wird. |
| skipHiddenCells | boolean | Wenn true, werden ausgeblendete Zellen (z.B. in ausgeblendeten Zeilen oder Spalten) aus dem Ergebnis ausgeschlossen. |

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Eine schreibgeschützte Liste von Zellen, die der angegebenen Formel entsprechen.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Ruft eine Zelle aus dem angegebenen Arbeitsblatt ab, wobei dessen Index und Zellkoordinaten verwendet werden.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Nullbasierter Index des Arbeitsblatts. |
| row | int | Nullbasierter Zeilenindex der Zelle. |
| column | int | Nullbasierter Spaltenindex der Zelle. |

**Rückgabewert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Die Zelle am angegebenen Ort.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

Ruft eine Zelle aus dem angegebenen Arbeitsblatt ab, wobei dessen Name und Zellkoordinaten verwendet werden.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts. |
| row | int | Nullbasierter Zeilenindex der Zelle. |
| column | int | Nullbasierter Spaltenindex der Zelle. |

**Rückgabewert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Die Zelle am angegebenen Ort.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Ruft eine Zelle aus dem angegebenen Arbeitsblatt ab, wobei dessen Index und der Excel-artige Zellname (z.B. "B2") verwendet werden.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Nullbasierter Index des Arbeitsblatts. |
| cellName | java.lang.String | Der Excel-artige Zellbezug (z.B. „A1“, „C5“). |

**Rückgabewert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Die Zelle am angegebenen Ort.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Ruft eine Zelle aus dem angegebenen Arbeitsblatt ab, wobei der Excel-artige Zellname (z.B. "B2") verwendet wird.

--------------------

> ```
> Beispiel:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts. |
| cellName | java.lang.String | Der Excel-artige Zellbezug (z.B. „A1“, „C5“). |

**Rückgabewert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Die Zelle am angegebenen Ort.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Ruft ein Dictionary ab, das die Indizes und Namen aller Diagramme im angegebenen Arbeitsblatt einer Excel-Arbeitsmappe enthält.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts, in dem nach Diagrammen gesucht werden soll. |

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Ein Dictionary, bei dem der Schlüssel der Diagramm-Index und der Wert der Diagrammname ist.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Ruft die Namen aller Arbeitsblätter in der Excel-Arbeitsmappe ab.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Eine Liste von Arbeitsblätternamen