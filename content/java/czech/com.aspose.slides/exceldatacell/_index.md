---
title: ExcelDataCell
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Representuje jednu buňku v sešitu Excelu.
type: docs
url: /cs/com.aspose.slides/exceldatacell/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Representuje jednu buňku v sešitu Excelu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getValue()](#getValue--) | Získá hodnotu obsaženou v buňce Excelu. |
| [getName()](#getName--) | Získá název buňky s daty grafu. |
| [getRow()](#getRow--) | Získá index řádku (číslování od nuly) v listu, kde se buňka nachází. |
| [getColumn()](#getColumn--) | Získá index sloupce (číslování od nuly) v listu, kde se buňka nachází. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Získá hodnotu obsaženou v buňce Excelu.

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


Získá název buňky s daty grafu.

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


Získá index řádku (číslování od nuly) v listu, kde se buňka nachází. Pouze pro čtení int.

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


Získá index sloupce (číslování od nuly) v listu, kde se buňka nachází. Pouze pro čtení int.

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