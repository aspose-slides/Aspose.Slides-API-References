---
title: ExcelDataCell
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een enkele cel in een Excel-werkmap voor.
type: docs
url: /nl/com.aspose.slides/exceldatacell/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Stelt een enkele cel in een Excel-werkmap voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getValue()](#getValue--) | Haalt de waarde op die in de Excel-cel staat. |
| [getName()](#getName--) | Haalt de naam op van de diagramgegevenscel. |
| [getRow()](#getRow--) | Haalt de nulgebaseerde index op van de rij in het werkblad waar de cel zich bevindt. |
| [getColumn()](#getColumn--) | Haalt de nulgebaseerde index op van de kolom in het werkblad waar de cel zich bevindt. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Haalt de waarde op die in de Excel-cel staat.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Retourneert:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```


Haalt de naam op van de diagramgegevenscel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Uitvoer: "B2"
> ```

**Retourneert:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
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

**Retourneert:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


Haalt de nulgebaseerde index op van de kolom in het werkblad waar de cel zich bevindt. Alleen-lezen int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Uitvoer: 1
> ```


**Retourneert:**
int