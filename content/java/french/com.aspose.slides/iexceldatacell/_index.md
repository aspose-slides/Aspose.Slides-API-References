---
title: IExcelDataCell
second_title: Aspose.Slides for Java Référence API
description: Représente une seule cellule dans un classeur Excel.
type: docs
url: /fr/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Représente une seule cellule dans un classeur Excel.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue()](#getValue--) | Renvoie la valeur contenue dans la cellule Excel. |
| [getName()](#getName--) | Renvoie le nom de la cellule de données du graphique. |
| [getRow()](#getRow--) | Renvoie l’indice zéro-base de la ligne dans la feuille où la cellule est située. |
| [getColumn()](#getColumn--) | Renvoie l’indice zéro-base de la colonne dans la feuille où la cellule est située. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Renvoie la valeur contenue dans la cellule Excel. Lecture seule Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Renvoie :**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


Renvoie le nom de la cellule de données du graphique. Lecture seule String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Sortie: "B2"
> ```

**Renvoie :**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Renvoie l’indice zéro-base de la ligne dans la feuille où la cellule est située. Lecture seule int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Sortie: 1
> ```

**Renvoie :**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Renvoie l’indice zéro-base de la colonne dans la feuille où la cellule est située. Lecture seule int.

--------------------

> ```
> Example:
>  
> v
> ```

**Renvoie :**
int