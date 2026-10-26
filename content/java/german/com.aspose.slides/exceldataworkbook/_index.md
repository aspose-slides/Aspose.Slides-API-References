---
title: ExcelDataWorkbook
second_title: Aspose.Slides für Java API Referenz
description: Stellt ein Arbeitsbuch dar, das Zugriff auf Excel-Daten für allgemeine Verwendung bietet.
type: docs
url: /de/com.aspose.slides/exceldataworkbook/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Stellt ein Arbeitsbuch dar, das Zugriff auf Excel-Daten für allgemeine Verwendung bietet.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Initialisiert eine neue Instanz mit dem angegebenen Dateipfad. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse mit dem bereitgestellten Stream. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Ruft eine Sammlung von Zellen aus dem Arbeitsbuch ab, die der angegebenen Formel entsprechen. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Index und ihrer Zellkoordinaten ab. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Namens und ihrer Zellkoordinaten ab. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Index und des Excel-artigen Zellnamens (z. B. "B2") ab. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand des Excel-artigen Zellnamens (z. B. "B2") ab. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Ruft ein Dictionary ab, das die Indizes und Namen aller Diagramme im angegebenen Arbeitsblatt eines Excel-Arbeitsbuchs enthält. |
| [getWorksheetNames()](#getWorksheetNames--) | Ruft die Namen aller Arbeitsblätter im Excel-Arbeitsbuch ab. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```


Initialisiert eine neue Instanz mit dem angegebenen Dateipfad.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der vollständige Pfad zur Excel-Arbeitsbuchdatei. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```


Initialisiert eine neue Instanz der Klasse mit dem bereitgestellten Stream.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Ein Stream, der die Excel-Arbeitsbuchdaten enthält. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Ruft eine Sammlung von Zellen aus dem Arbeitsbuch ab, die der angegebenen Formel entsprechen.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Output: 5
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | java.lang.String | Ein Formelausdruck oder Bereich (z. B. "Sheet1!A1:B3"), der die Zielzellen identifiziert. |
| skipHiddenCells | boolean | Wenn true, werden versteckte Zellen (z. B. in ausgeblendeten Zeilen oder Spalten) vom Ergebnis ausgeschlossen. |

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Eine schreibgeschützte Liste von Zellen, die der angegebenen Formel entsprechen.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Index und ihrer Zellkoordinaten ab.

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
| worksheetIndex | int | Null-basierter Index des Arbeitsblatts. |
| row | int | Null-basierter Zeilenindex der Zelle. |
| column | int | Null-basierter Spaltenindex der Zelle. |

**Rückgabewert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Die Zelle an der angegebenen Position.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```


Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Namens und ihrer Zellkoordinaten ab.

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
| row | int | Null-basierter Zeilenindex der Zelle. |
| column | int | Null-basierter Spaltenindex der Zelle. |

**Rückgabewert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Die Zelle an der angegebenen Position.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Index und des Excel-artigen Zellnamens (z. B. "B2") ab.

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
| worksheetIndex | int | Null-basierter Index des Arbeitsblatts. |
| cellName | java.lang.String | Die Excel-artige Zellreferenz (z. B. "A1", "C5"). |

**Rückgabewert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Die Zelle an der angegebenen Position.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```


Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand des Excel-artigen Zellnamens (z. B. "B2") ab.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts. |
| cellName | java.lang.String | Die Excel-artige Zellreferenz (z. B. "A1", "C5"). |

**Rückgabewert:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Die Zelle an der angegebenen Position.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Ruft ein Dictionary ab, das die Indizes und Namen aller Diagramme im angegebenen Arbeitsblatt eines Excel-Arbeitsbuchs enthält.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Ein Dictionary, wobei der Schlüssel der Diagrammindex und der Wert der Diagrammname ist.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```


Ruft die Namen aller Arbeitsblätter im Excel-Arbeitsbuch ab.

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Eine Liste von Arbeitsblattnamen