---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Biedt toegang tot ingesloten Excel-werkmap
type: docs
url: /nl/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Biedt toegang tot ingesloten Excel-werkmap
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Bereken alle formules in de werkmap en werk de bijbehorende celwaarden bij. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Haalt de verzameling cellen op. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën |
| [clear(int sheetIndex)](#clear-int-) | Wis alle celwaarden op het blad |
| [getWorksheets()](#getWorksheets--) | Haalt een verzameling werkbladen op. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

Bereken alle formules in de werkmap en werk de bijbehorende celwaarden bij.

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

Haalt de verzameling cellen op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formula | java.lang.String | Excel-formule zoals "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Indien true retourneert de methode een verzameling zonder verborgen cellen. |

**Retour:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Set of cells [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetName | java.lang.String | Naam van het werkblad. |
| row | int | De rij. |
| column | int | De kolom. |

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | int | Index van het werkblad. |
| row | int | De rij. |
| column | int | De kolom. |

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | int | Index van het werkblad. |
| cellName | java.lang.String | Naam van de cel. |

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | int | Index van het werkblad. |
| cellName | java.lang.String | Naam van de cel. |
| value | java.lang.Object | De waarde. |

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Haalt de cel op die kan worden gebruikt voor diagramreeksen of -categorieën

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheetIndex | int | Index van het werkblad. |
| row | int | De rij. |
| column | int | De kolom. |
| value | java.lang.Object | De waarde. |

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

Wis alle celwaarden op het blad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sheetIndex | int | Index van het blad |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

Haalt een verzameling werkbladen op.

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

**Retour:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)