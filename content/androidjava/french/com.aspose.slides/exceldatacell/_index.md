---
title: ExcelDataCell
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une seule cellule dans un classeur Excel.
type: docs
url: /fr/com.aspose.slides/exceldatacell/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Représente une seule cellule dans un classeur Excel.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue()](#getValue--) | Renvoie la valeur contenue dans la cellule Excel. |
| [getName()](#getName--) | Renvoie le nom de la cellule de données du diagramme. |
| [getRow()](#getRow--) | Renvoie l'indice basé sur zéro de la ligne dans la feuille de calcul où se trouve la cellule. |
| [getColumn()](#getColumn--) | Renvoie l'indice basé sur zéro de la colonne dans la feuille de calcul où se trouve la cellule. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Renvoie la valeur contenue dans la cellule Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Returns:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```

Gets the name of the chart data cell.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Sortie : "B2"
> ```

**Returns:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```
Gets the zero-based index of the row in the worksheet where the cell is located. Read-only int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Sortie : 1
> ```

**Returns:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()


Renvoie l'indice basé sur zéro de la colonne dans la feuille de calcul où se trouve la cellule. Lecture seule int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Output: 1
> ```

**Retour:**
int