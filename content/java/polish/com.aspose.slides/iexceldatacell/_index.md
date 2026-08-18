---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje pojedynczą komórkę w skoroszycie Excel.
type: docs
url: /pl/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Reprezentuje pojedynczą komórkę w skoroszycie Excel.
## Metody

| Metoda | Opis |
| --- | --- |
| [getValue()](#getValue--) | Zwraca wartość zawartą w komórce Excel. |
| [getName()](#getName--) | Zwraca nazwę komórki danych wykresu. |
| [getRow()](#getRow--) | Zwraca indeks wiersza (liczony od zera) w arkuszu, w którym znajduje się komórka. |
| [getColumn()](#getColumn--) | Zwraca indeks kolumny (liczony od zera) w arkuszu, w którym znajduje się komórka. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Zwraca wartość zawartą w komórce Excel. Tylko do odczytu  Object .

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

Zwraca nazwę komórki danych wykresu. Tylko do odczytu String.

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
public abstract int getRow()
```

Zwraca indeks wiersza (liczony od zera) w arkuszu, w którym znajduje się komórka. Tylko do odczytu int.

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

Zwraca indeks kolumny (liczony od zera) w arkuszu, w którym znajduje się komórka. Tylko do odczytu int.

--------------------

> ```
> Example:
>  
> v
> ```

**Zwraca:**
int