---
title: ExcelDataWorkbook
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un classeur qui fournit un accès aux données Excel pour une utilisation générale.
type: docs
url: /fr/com.aspose.slides/exceldataworkbook/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)  
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Représente un classe de classeur qui fournit un accès aux données Excel pour une utilisation générale.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Initialise une nouvelle instance en utilisant le chemin de fichier spécifié. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Initialise une nouvelle instance de la classe en utilisant le flux fourni. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Récupère une collection de cellules du classeur qui correspondent à la formule spécifiée. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et ses coordonnées de cellule. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son nom et ses coordonnées de cellule. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et le nom de cellule au format Excel (par ex., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Récupère une cellule de la feuille de calcul spécifiée en utilisant le nom de cellule au format Excel (par ex., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Récupère un dictionnaire contenant les index et les noms de tous les graphiques dans la feuille de calcul spécifiée d’un classeur Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Récupère les noms de toutes les feuilles de calcul contenues dans le classeur Excel. |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

Initialise une nouvelle instance en utilisant le chemin de fichier spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin complet vers le fichier du classeur Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

Initialise une nouvelle instance de la classe en utilisant le flux fourni.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Un flux contenant les données du classeur Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Récupère une collection de cellules du classeur qui correspondent à la formule spécifiée.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Output: 5
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | A formula or range expression (e.g., "Sheet1!A1:B3") used to identify target cells. |
| skipHiddenCells | boolean | If true, hidden cells (e.g., in hidden rows or columns) will be excluded from the result. |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - A read-only list of cells that match the specified formula.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Retrieves a cell from the specified worksheet using its index and cell coordinates.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Zero-based index of the worksheet. |
| row | int | Zero-based row index of the cell. |
| column | int | Zero-based column index of the cell. |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - The cell at the specified location.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

Retrieves a cell from the specified worksheet using its name and cell coordinates.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | The name of the worksheet. |
| row | int | Zero-based row index of the cell. |
| column | int | Zero-based column index of the cell. |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - The cell at the specified location.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Zero-based index of the worksheet. |
| cellName | java.lang.String | The Excel-style cell reference (e.g., "A1", "C5"). |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - The cell at the specified location.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | The name of the worksheet. |
| cellName | java.lang.String | The Excel-style cell reference (e.g., "A1", "C5"). |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - The cell at the specified location.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | The name of the worksheet to search for charts. |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - A dictionary where the key is the chart index and the value is the chart name.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()

Récupère les noms de toutes les feuilles de calcul contenues dans le classeur Excel.

--------------------

> ```
> Exemple :
>   
>   IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>   List<String> sheetNames = wb.getWorksheetNames();
>   for (String name : sheetNames)
>       System.out.println(name);
> ```

**Renvoie :**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Une liste de noms de feuilles de calcul