---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Egy Excel munkafüzet egyetlen celláját képviseli.
type: docs
url: /hu/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Egy Excel munkafüzet egyetlen celláját képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Lekéri a Excel cellában tárolt értéket. |
| [getName()](#getName--) | Lekéri a diagram adatcellájának nevét. |
| [getRow()](#getRow--) | Lekéri a cella található munkalapon lévő sor nulla alapú indexét. |
| [getColumn()](#getColumn--) | Lekéri a cella található munkalapon lévő oszlop nulla alapú indexét. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Lekéri a Excel cellában tárolt értéket. Csak olvasható  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Visszatér:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


Lekéri a diagram adatcellájának nevét. Csak olvasható String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Kimenet: "B2"
> ```


**Visszatér:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Lekéri a cella található munkalapon lévő sor nulla alapú indexét. Csak olvasható int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Kimenet: 1
> ```


**Visszatér:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Lekéri a cella található munkalapon lévő oszlop nulla alapú indexét. Csak olvasható int.

--------------------

> ```
> Example:
>  
> v
> ```

**Visszatér:**
int