---
title: ChartDataWorkbook
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Zugriff auf eingebettete Excel-Arbeitsmappe bereit
type: docs
url: /de/com.aspose.slides/chartdataworkbook/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Stellt Zugriff auf eingebettete Excel-Arbeitsmappe bereit
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Ruft eine Sammlung von Arbeitsblättern ab. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Ruft die Menge der Zellen ab. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann |
| [clear(int sheetIndex)](#clear-int-) | Löscht alle Zellwerte im Blatt |
| [calculateFormulas()](#calculateFormulas--) | Berechnet alle Formeln in der Arbeitsmappe und aktualisiert die entsprechenden Zellwerte. |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

Ruft eine Sammlung von Arbeitsblättern ab.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Ruft die Menge der Zellen ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | java.lang.String | Excel-Formel wie "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Wenn true, gibt die Methode eine Sammlung ohne ausgeblendete Zellen zurück. |

**Rückgabe:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | java.lang.String | Name des Arbeitsblatts. |
| row | int | Die Zeile. |
| column | int | Die Spalte. |

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Index des Arbeitsblatts. |
| row | int | Die Zeile. |
| column | int | Die Spalte. |

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Index des Arbeitsblatts. |
| cellName | java.lang.String | Name der Zelle. |

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Index des Arbeitsblatts. |
| cellName | java.lang.String | Name der Zelle. |
| value | java.lang.Object | Der Wert. |

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Ruft die Zelle ab, die für Diagrammserien oder -kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Index des Arbeitsblatts. |
| row | int | Die Zeile. |
| column | int | Die Spalte. |
| value | java.lang.Object | Der Wert. |

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

Löscht alle Zellwerte im Blatt

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sheetIndex | int | Index des Blatts |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

Berechnet alle Formeln in der Arbeitsmappe und aktualisiert die entsprechenden Zellwerte.

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```