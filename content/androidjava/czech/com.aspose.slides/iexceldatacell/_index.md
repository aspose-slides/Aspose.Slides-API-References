---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a single cell in an Excel workbook.
type: docs
url: /cs/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Představuje jednu buňku v sešitu Excel.
## Metody

| Metoda | Popis |
| --- | --- |
| [getValue()](#getValue--) | Získá hodnotu obsaženou v buňce Excelu. |
| [getName()](#getName--) | Získá název buňky s daty grafu. |
| [getRow()](#getRow--) | Získá index řádku v listu, kde se buňka nachází, počítaný od nuly. |
| [getColumn()](#getColumn--) | Získá index sloupce v listu, kde se buňka nachází, počítaný od nuly. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Získá hodnotu obsaženou v buňce Excelu. Pouze pro čtení  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Vrací:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


Získá název buňky s daty grafu. Pouze pro čtení String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Výstup: "B2"
> ```

**Vrací:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Získá index řádku v listu, kde se buňka nachází, počítaný od nuly. Pouze pro čtení int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Výstup: 1
> ```

**Vrací:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Získá index sloupce v listu, kde se buňka nachází, počítaný od nuly. Pouze pro čtení int.

--------------------

> ```
> Example:
>  
> v
> ```

**Vrací:**
int