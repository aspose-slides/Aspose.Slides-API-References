---
title: ExcelDataCell
second_title: Aspose.Slides Java API hivatkozás
description: Egyetlen cellát képvisel egy Excel munkafüzetben.
type: docs
url: /hu/com.aspose.slides/exceldatacell/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Egyetlen cellát képvisel egy Excel munkafüzetben.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getValue()](#getValue--) | Megkapja az Excel cellában tárolt értéket. |
| [getName()](#getName--) | Megkapja a diagram adatcellájának nevét. |
| [getRow()](#getRow--) | Megkapja a cella helyét tartalmazó munkalapon a sor nullától induló indexét. |
| [getColumn()](#getColumn--) | Megkapja a cella helyét tartalmazó munkalapon az oszlop nullától induló indexét. |
### getValue() {#getValue--}
```
public final Object getValue()
```

Megkapja az Excel cellában tárolt értéket.

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
public final String getName()
```

Megkapja a diagram adatcellájának nevét.

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
public final int getRow()
```

Megkapja a cella helyét tartalmazó munkalapon a sor nullától induló indexét. Csak olvasható int.

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
public final int getColumn()
```

Megkapja a cella helyét tartalmazó munkalapon az oszlop nullától induló indexét. Csak olvasható int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Kimenet: 1
> ```


**Visszatér:**
int