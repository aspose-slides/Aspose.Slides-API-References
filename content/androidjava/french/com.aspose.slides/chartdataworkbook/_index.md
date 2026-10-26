---
title: ChartDataWorkbook
second_title: Aspose.Slides pour Android via la référence API Java
description: Fournit l'accès au classeur Excel intégré
type: docs
url: /fr/com.aspose.slides/chartdataworkbook/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Fournit l'accès au classeur Excel intégré
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Obtient une collection de feuilles de calcul. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Obtient l'ensemble des cellules. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories de graphique |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories de graphique |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories de graphique |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories de graphique |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Obtient la cellule qui peut être utilisée pour les séries ou les catégories de graphique |
| [clear(int sheetIndex)](#clear-int-) | Efface toutes les valeurs de cellules sur la feuille |
| [calculateFormulas()](#calculateFormulas--) | Calcule toutes les formules du classeur et met à jour les valeurs correspondantes des cellules. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```


Obtient une collection de feuilles de calcul.

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

**Returns:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Gets the set of cells.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Excel formula like "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | If true then method returns collection without hidden cells. |

**Returns:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Name of the worksheet. |
| row | int | The row. |
| column | int | The column. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| row | int | The row. |
| column | int | The column. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| cellName | java.lang.String | Name of the cell. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| cellName | java.lang.String | Name of the cell. |
| value | java.lang.Object | The value. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Gets the cell that can be used for chart series or categories

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index of the worksheet. |
| row | int | The row. |
| column | int | The column. |
| value | java.lang.Object | The value. |

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

Clear all cells values on sheet

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheetIndex | int | Index of sheet |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()

Calculates all formulas in the workbook and updates corresponding cells values.

--------------------

> L'exemple montre comment attribuer une formule à la cellule et calculer une valeur. La valeur de la cellule "B4" est fixée à 5.
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