---
title: ChartDataWorkbook
second_title: Référence de l'API Aspose.Slides pour Java
description: Fournit un accès à un classeur Excel intégré
type: docs
url: /fr/com.aspose.slides/chartdataworkbook/
---
**Héritage:**  
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)  
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Fournit un accès à un classeur Excel intégré

## Méthodes

| Méthode | Description |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Obtient une collection de feuilles de calcul. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Obtient l'ensemble des cellules. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique |
| [clear(int sheetIndex)](#clear-int-) | Efface toutes les valeurs des cellules sur la feuille |
| [calculateFormulas()](#calculateFormulas--) | Calcule toutes les formules du classeur et met à jour les valeurs des cellules correspondantes. |

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

**Renvoie :**  
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Obtient l'ensemble des cellules.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Formule Excel comme "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Si vrai, la méthode renvoie la collection sans les cellules masquées. |

**Renvoie :**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Nom de la feuille de calcul. |
| row | int | La ligne. |
| column | int | La colonne. |

**Renvoie :**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objet Cell

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Indice de la feuille de calcul. |
| row | int | La ligne. |
| column | int | La colonne. |

**Renvoie :**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objet Cell

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Indice de la feuille de calcul. |
| cellName | java.lang.String | Nom de la cellule. |

**Renvoie :**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objet Cell

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Indice de la feuille de calcul. |
| cellName | java.lang.String | Nom de la cellule. |
| value | java.lang.Object | La valeur. |

**Renvoie :**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objet Cell

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Obtient la cellule pouvant être utilisée pour les séries ou catégories de graphique

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Indice de la feuille de calcul. |
| row | int | La ligne. |
| column | int | La colonne. |
| value | java.lang.Object | La valeur. |

**Renvoie :**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objet Cell

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

Efface toutes les valeurs des cellules sur la feuille

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sheetIndex | int | Indice de la feuille |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

Calcule toutes les formules du classeur et met à jour les valeurs des cellules correspondantes.

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