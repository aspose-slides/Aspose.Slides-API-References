---
title: ExcelDataCell
second_title: Aspose.Slides dla Java – Referencja API
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
| [getValue()](#getValue--) | Pobiera wartość zawartą w komórce Excel. |
| [getName()](#getName--) | Pobiera nazwę komórki danych wykresu. |
| [getRow()](#getRow--) | Pobiera indeks wiersza w arkuszu, w którym znajduje się komórka, liczony od zera. |
| [getColumn()](#getColumn--) | Pobiera indeks kolumny w arkuszu, w którym znajduje się komórka, liczony od zera. |
### getValue() {#getValue--}
```
public final Object getValue()
```

Pobiera wartość zawartą w komórce Excel.

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

Pobiera indeks wiersza w arkuszu, w którym znajduje się komórka, liczony od zera. Tylko do odczytu int.

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

Pobiera indeks kolumny w arkuszu, w którym znajduje się komórka, liczony od zera. Tylko do odczytu int.

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