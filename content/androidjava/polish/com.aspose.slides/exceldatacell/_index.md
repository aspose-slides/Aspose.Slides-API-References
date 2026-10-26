---
title: ExcelDataCell
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje pojedynczą komórkę w skoroszycie Excel.
type: docs
url: /pl/com.aspose.slides/exceldatacell/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Reprezentuje pojedynczą komórkę w skoroszycie Excel.
## Metody

| Metoda | Opis |
| --- | --- |
| [getValue()](#getValue--) | Pobiera wartość znajdującą się w komórce Excel. |
| [getName()](#getName--) | Pobiera nazwę komórki danych wykresu. |
| [getRow()](#getRow--) | Pobiera indeks zerowy wiersza w arkuszu, w którym znajduje się komórka. |
| [getColumn()](#getColumn--) | Pobiera indeks zerowy kolumny w arkuszu, w którym znajduje się komórka. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Pobiera wartość znajdującą się w komórce Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Zwraca:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```


Pobiera nazwę komórki danych wykresu.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Wyjście: "B2"
> ```

**Zwraca:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```


Pobiera indeks zerowy wiersza w arkuszu, w którym znajduje się komórka. Tylko do odczytu int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Wyjście: 1
> ```


**Zwraca:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


Pobiera indeks zerowy kolumny w arkuszu, w którym znajduje się komórka. Tylko do odczytu int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Wyjście: 1
> ```


**Zwraca:**
int