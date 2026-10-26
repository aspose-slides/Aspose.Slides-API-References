---
title: ExcelDataCell
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une cellule unique dans un classeur Excel.
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

Représente une cellule unique dans un classeur Excel.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue()](#getValue--) | Obtient la valeur contenue dans la cellule Excel. |
| [getName()](#getName--) | Obtient le nom de la cellule de données du graphique. |
| [getRow()](#getRow--) | Obtient l’index basé sur zéro de la ligne dans la feuille de calcul où la cellule est située. |
| [getColumn()](#getColumn--) | Obtient l’index basé sur zéro de la colonne dans la feuille de calcul où la cellule est située. |
### getValue() {#getValue--}
```
public final Object getValue()
```

Obtient la valeur contenue dans la cellule Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Retourne:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```

Obtient le nom de la cellule de données du graphique.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Sortie: "B2"
> ```


**Retourne:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

Obtient l’index basé sur zéro de la ligne dans la feuille de calcul où la cellule est située. Lecture seule int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Sortie: 1
> ```

**Retourne:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Obtient l’index basé sur zéro de la colonne dans la feuille de calcul où la cellule est située. Lecture seule int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Sortie: 1
> ```

**Retourne:**
int