---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a single cell in an Excel workbook.
type: docs
url: /pl/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Reprezentuje pojedynczą komórkę w skoroszycie Excel.

## Metody

| Metoda | Opis |
| --- | --- |
| [getValue()](#getValue--) | Pobiera wartość zawartą w komórce Excel. |
| [getName()](#getName--) | Pobiera nazwę komórki danych wykresu. |
| [getRow()](#getRow--) | Pobiera indeks zerowy wiersza w arkuszu, w którym znajduje się komórka. |
| [getColumn()](#getColumn--) | Pobiera indeks zerowy kolumny w arkuszu, w którym znajduje się komórka. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Pobiera wartość zawartą w komórce Excel. Tylko do odczytu  Object .

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
public abstract String getName()
```


Pobiera nazwę komórki danych wykresu. Tylko do odczytu String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Wynik: "B2"
> ```


**Zwraca:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
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
public abstract int getColumn()
```


Pobiera indeks zerowy kolumny w arkuszu, w którym znajduje się komórka. Tylko do odczytu int.

--------------------

> ```
> Example:
>  
> v
> ```

**Zwraca:**
int