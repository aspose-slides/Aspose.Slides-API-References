---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje jedinou buňku v sešitu Excel.
type: docs
url: /cs/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Reprezentuje jedinou buňku v sešitu Excel.
## Metody

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Získá hodnotu obsaženou v buňce Excelu. |
| [getName()](#getName--) | Získá název buňky s daty grafu. |
| [getRow()](#getRow--) | Získá nulově založený index řádku v listu, kde se buňka nachází. |
| [getColumn()](#getColumn--) | Získá nulově založený index sloupce v listu, kde se buňka nachází. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Získá hodnotu obsaženou v buňce Excelu. Pouze pro čtení Object .

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


Získá nulově založený index řádku v listu, kde se buňka nachází. Pouze pro čtení int.

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


Získá nulově založený index sloupce v listu, kde se buňka nachází. Pouze pro čtení int.

--------------------

> ```
> Example:
>  
  
> v
> ```

**Vrací:**
int