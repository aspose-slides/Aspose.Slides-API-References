---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Egyetlen cellát képvisel egy Excel munkafüzetben.
type: docs
url: /hu/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Egyetlen cellát képvisel egy Excel munkafüzetben.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getValue()](#getValue--) | Visszaadja az Excel cellában tárolt értéket. |
| [getName()](#getName--) | Visszaadja a diagram adatcellájának nevét. |
| [getRow()](#getRow--) | Visszaadja a cella helyét tartalmazó munkalapon a sor nulla-alapú indexét. |
| [getColumn()](#getColumn--) | Visszaadja a cella helyét tartalmazó munkalapon az oszlop nulla-alapú indexét. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Visszaadja az Excel cellában tárolt értéket. **Csak olvasható**  Object .

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


Visszaadja a diagram adatcellájának nevét. **Csak olvasható** String.

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


Visszaadja a cella helyét tartalmazó munkalapon a sor nulla-alapú indexét. **Csak olvasható** int.

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


Visszaadja a cella helyét tartalmazó munkalapon az oszlop nulla-alapú indexét. **Csak olvasható** int.

--------------------

> ```
> Example:
>  
  
> v
> ```

**Visszatér:**
int