---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar en enskild cell i en Excel-arbetsbok.
type: docs
url: /sv/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Representerar en enskild cell i en Excel-arbetsbok.
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Hämtar värdet som finns i Excel-cellen. |
| [getName()](#getName--) | Hämtar namnet på diagrammets datacell. |
| [getRow()](#getRow--) | Hämtar det nollbaserade indexet för raden i kalkylbladet där cellen är placerad. |
| [getColumn()](#getColumn--) | Hämtar det nollbaserade indexet för kolumnen i kalkylbladet där cellen är placerad. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Hämtar värdet som finns i Excel-cellen. Skrivskyddad Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Returns:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```

Hämtar namnet på diagrammets datacell. Skrivskyddad String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Utdata: "B2"
> ```

**Returns:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
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


**Returns:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Hämtar det nollbaserade indexet för kolumnen i kalkylbladet där cellen är placerad. Skrivskyddad int.

--------------------

> ```
> Example:
>  
> v
> ```

**Returns:**
int