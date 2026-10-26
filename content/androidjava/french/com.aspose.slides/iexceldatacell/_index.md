---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Représente une seule cellule d'un classeur Excel.
type: docs
url: /fr/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Représente une seule cellule d'un classeur Excel.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue()](#getValue--) | Obtient la valeur contenue dans la cellule Excel. |
| [getName()](#getName--) | Obtient le nom de la cellule de données du graphique. |
| [getRow()](#getRow--) | Obtient l'index zéro-base de la ligne dans la feuille de calcul où se trouve la cellule. |
| [getColumn()](#getColumn--) | Obtient l'index zéro-base de la colonne dans la feuille de calcul où se trouve la cellule. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Obtient la valeur contenue dans la cellule Excel. Lecture seule Object .

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
public abstract String getName()
```
Gets the name of the chart data cell. Read-only String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Sortie: "B2"
> ```

**Returns:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```

Gets the zero-based index of the row in the worksheet where the cell is located. Read-only int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Sortie: 1
> ```

**Returns:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()


Obtient l'index zéro-base de la colonne dans la feuille de calcul où se trouve la cellule. Lecture seule int.

--------------------

> ```
> Exemple :
>  
> v
> ```

**Retour :**  
int