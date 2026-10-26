---
title: IChartDataWorkbook
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt Zugriff auf die eingebettete Excel-Arbeitsmappe bereit
type: docs
url: /de/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Stellt Zugriff auf die eingebettete Excel-Arbeitsmappe bereit
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Berechnet alle Formeln in der Arbeitsmappe und aktualisiert die entsprechenden Zellenwerte. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Ruft die Menge der Zellen ab. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann |
| [clear(int sheetIndex)](#clear-int-) | Löscht alle Zellenwerte im Blatt |
| [getWorksheets()](#getWorksheets--) | Ruft eine Sammlung von Arbeitsblättern ab. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

Berechnet alle Formeln in der Arbeitsmappe und aktualisiert die entsprechenden Zellenwerte.

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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Ruft die Menge der Zellen ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | java.lang.String | Excel-Formel wie "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Wenn true, gibt die Methode eine Sammlung ohne ausgeblendete Zellen zurück. |

**Rückgabewert:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Menge von Zellen [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetName | java.lang.String | Name des Arbeitsblatts. |
| row | int | Die Zeile. |
| column | int | Die Spalte. |

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Zellobjekt
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Index des Arbeitsblatts. |
| row | int | Die Zeile. |
| column | int | Die Spalte. |

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Zellobjekt
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Index des Arbeitsblatts. |
| cellName | java.lang.String | Name der Zelle. |

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Zellobjekt
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Index des Arbeitsblatts. |
| cellName | java.lang.String | Name der Zelle. |
| value | java.lang.Object | Der Wert. |

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Zellobjekt
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Ruft die Zelle ab, die für Diagrammserien oder Kategorien verwendet werden kann

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheetIndex | int | Index des Arbeitsblatts. |
| row | int | Die Zeile. |
| column | int | Die Spalte. |
| value | java.lang.Object | Der Wert. |

**Rückgabewert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Zellobjekt
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

Löscht alle Zellenwerte im Blatt

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sheetIndex | int | Index des Blatts |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
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