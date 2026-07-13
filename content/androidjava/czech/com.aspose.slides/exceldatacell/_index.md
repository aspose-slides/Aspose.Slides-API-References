---
title: ExcelDataCell
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje jednu buňku v sešitu Excel.
type: docs
url: /cs/com.aspose.slides/exceldatacell/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Reprezentuje jednu buňku v sešitu Excel.
## Metody

| Metoda | Popis |
| --- | --- |
| [getValue()](#getValue--) | Získá hodnotu obsaženou v buňce Excel. |
| [getName()](#getName--) | Získá název buňky dat grafu. |
| [getRow()](#getRow--) | Získá nulově založený index řádku v listu, kde se buňka nachází. |
| [getColumn()](#getColumn--) | Získá nulově založený index sloupce v listu, kde se buňka nachází. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Získá hodnotu obsaženou v buňce Excel.

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
public final String getName()
```


Získá název buňky dat grafu.

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
public final int getRow()
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
public final int getColumn()
```


Získá nulově založený index sloupce v listu, kde se buňka nachází. Pouze pro čtení int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Výstup: 1
> ```

**Vrací:**
int