---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Représente un classeur qui fournit un accès aux données Excel pour une utilisation générale.
type: docs
url: /fr/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Représente un classeur qui fournit un accès aux données Excel pour une utilisation générale.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Récupère une collection de cellules du classeur qui correspondent à la formule spécifiée. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et ses coordonnées. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son nom et ses coordonnées. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et le nom de cellule au format Excel (par ex., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Récupère une cellule de la feuille de calcul spécifiée en utilisant le nom de cellule au format Excel (par ex., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Récupère un dictionnaire contenant les index et les noms de tous les graphiques dans la feuille de calcul spécifiée d'un classeur Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Récupère les noms de toutes les feuilles de calcul contenues dans le classeur Excel. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Récupère une collection de cellules du classeur qui correspondent à la formule spécifiée.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Sortie : 5
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Une expression de formule ou de plage (par ex., "Sheet1!A1:B3") utilisée pour identifier les cellules cibles. |
| skipHiddenCells | boolean | Si true, les cellules masquées (par ex., dans les lignes ou colonnes masquées) seront exclues du résultat. |

**Renvoie:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Une liste en lecture seule de cellules qui correspondent à la formule spécifiée.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et ses coordonnées.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index de la feuille de calcul basé sur zéro. |
| row | int | Indice de ligne basé sur zéro de la cellule. |
| column | int | Indice de colonne basé sur zéro de la cellule. |

**Renvoie:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La cellule à l'emplacement spécifié.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

Récupère une cellule de la feuille de calcul spécifiée en utilisant son nom et ses coordonnées.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Le nom de la feuille de calcul. |
| row | int | Indice de ligne basé sur zéro de la cellule. |
| column | int | Indice de colonne basé sur zéro de la cellule. |

**Renvoie:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La cellule à l'emplacement spécifié.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Récupère une cellule de la feuille de calcul spécifiée en utilisant son index et le nom de cellule au format Excel (par ex., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Index de la feuille de calcul basé sur zéro. |
| cellName | java.lang.String | La référence de cellule au format Excel (par ex., "A1", "C5"). |

**Renvoie:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La cellule à l'emplacement spécifié.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Récupère une cellule de la feuille de calcul spécifiée en utilisant le nom de cellule au format Excel (par ex., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Le nom de la feuille de calcul. |
| cellName | java.lang.String | La référence de cellule au format Excel (par ex., "A1", "C5"). |

**Renvoie:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La cellule à l'emplacement spécifié.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Récupère un dictionnaire contenant les index et les noms de tous les graphiques dans la feuille de calcul spécifiée d'un classeur Excel.

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Le nom de la feuille de calcul où rechercher les graphiques. |

**Renvoie:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Un dictionnaire où la clé est l'index du graphique et la valeur est le nom du graphique.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Récupère les noms de toutes les feuilles de calcul contenues dans le classeur Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Renvoie:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Une liste de noms de feuilles de calcul