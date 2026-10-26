---
title: ExcelDataCell
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en enskild cell i en Excel-arbetsbok.
type: docs
url: /sv/com.aspose.slides/exceldatacell/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Representerar en enskild cell i en Excel-arbetsbok.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValue()](#getValue--) | Hämtar värdet som finns i Excel-cellen. |
| [getName()](#getName--) | Hämtar namnet på diagrammets data cell. |
| [getRow()](#getRow--) | Hämtar det nollbaserade indexet för raden i kalkylbladet där cellen är placerad. |
| [getColumn()](#getColumn--) | Hämtar det nollbaserade indexet för kolumnen i kalkylbladet där cellen är placerad. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Hämtar värdet som finns i Excel-cellen.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Returnerar:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på diagrammets data cell.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Utdata: "B2"
> ```

**Returnerar:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```


Hämtar det nollbaserade indexet för raden i kalkylbladet där cellen är placerad. Skrivskyddad int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Utdata: 1
> ```

**Returnerar:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


Hämtar det nollbaserade indexet för kolumnen i kalkylbladet där cellen är placerad. Skrivskyddad int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Utdata: 1
> ```

**Returnerar:**
int