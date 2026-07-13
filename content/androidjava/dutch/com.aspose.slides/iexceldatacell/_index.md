---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een enkele cel in een Excel-werkmap voor.
type: docs
url: /nl/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Stelt een enkele cel in een Excel-werkmap voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getValue()](#getValue--) | Haalt de waarde op die in de Excel-cel is opgeslagen. |
| [getName()](#getName--) | Haalt de naam van de grafiekdatacel op. |
| [getRow()](#getRow--) | Haalt de nulgebaseerde index van de rij in het werkblad op waarin de cel zich bevindt. |
| [getColumn()](#getColumn--) | Haalt de nulgebaseerde index van de kolom in het werkblad op waarin de cel zich bevindt. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Haalt de waarde op die in de Excel-cel is opgeslagen. Alleen-lezen  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Retour:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```

Haalt de naam van de grafiekdatacel op. Alleen-lezen String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Uitvoer: "B2"
> ```


**Retour:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```

Haalt de nulgebaseerde index van de rij in het werkblad op waarin de cel zich bevindt. Alleen-lezen int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Uitvoer: 1
> ```


**Retour:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Haalt de nulgebaseerde index van de kolom in het werkblad op waarin de cel zich bevindt. Alleen-lezen int.

--------------------

> ```
> Example:
>  
> v
> ```

**Retour:**
int