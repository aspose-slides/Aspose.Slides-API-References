---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Vertegenwoordigt een enkele cel in een Excel-werkmap.
type: docs
url: /nl/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Vertegenwoordigt een enkele cel in een Excel-werkmap.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getValue()](#getValue--) | Haalt de waarde op die in de Excel-cel zit. |
| [getName()](#getName--) | Haalt de naam op van de grafiekdatacel. |
| [getRow()](#getRow--) | Haalt de nulgebaseerde index op van de rij in het werkblad waar de cel zich bevindt. |
| [getColumn()](#getColumn--) | Haalt de nulgebaseerde index op van de kolom in het werkblad waar de cel zich bevindt. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Haalt de waarde op die in de Excel-cel zit. Alleen-lezen  Object .

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


Haalt de naam op van de grafiekdatacel. Alleen-lezen String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Uitvoer: "B2"
> ```

**Returns:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Haalt de nulgebaseerde index op van de rij in het werkblad waar de cel zich bevindt. Alleen-lezen int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Uitvoer: 1
> ```

**Returns:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Haalt de nulgebaseerde index op van de kolom in het werkblad waar de cel zich bevindt. Alleen-lezen int.

--------------------

> ```
> Example:
>  
> v
> ```

**Returns:**
int