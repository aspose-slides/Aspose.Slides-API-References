---
title: ExcelDataCell
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: Egy Excel munkafüzet egyetlen celláját képviseli.
type: docs
url: /hu/com.aspose.slides/exceldatacell/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Egy Excel munkafüzet egyetlen celláját képviseli.
## Metódusok

| Method | Leírás |
| --- | --- |
| [getValue()](#getValue--) | A cellában lévő értéket adja vissza. |
| [getName()](#getName--) | A diagram adatcellájának nevét adja vissza. |
| [getRow()](#getRow--) | A munkalapon a cella helyét meghatározó sor nullával kezdődő indexét adja vissza. |
| [getColumn()](#getColumn--) | A munkalapon a cella helyét meghatározó oszlop nullával kezdődő indexét adja vissza. |
### getValue() {#getValue--}
```
public final Object getValue()
```

A cellában lévő értéket adja vissza.

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

A diagram adatcellájának nevét adja vissza.

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

A munkalapon a cella helyét meghatározó sor nullával kezdődő indexét adja vissza. Csak olvasható int.

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

A munkalapon a cella helyét meghatározó oszlop nullával kezdődő indexét adja vissza. Csak olvasható int.

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