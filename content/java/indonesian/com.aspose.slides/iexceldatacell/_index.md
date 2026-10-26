---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Mewakili satu sel dalam buku kerja Excel.
type: docs
url: /id/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Mewakili satu sel dalam buku kerja Excel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getValue()](#getValue--) | Mengambil nilai yang terdapat di sel Excel. |
| [getName()](#getName--) | Mengambil nama sel data diagram. |
| [getRow()](#getRow--) | Mengambil indeks berbasis nol dari baris di lembar kerja tempat sel berada. |
| [getColumn()](#getColumn--) | Mengambil indeks berbasis nol dari kolom di lembar kerja tempat sel berada. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Mengambil nilai yang terdapat di sel Excel. Read-only Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Mengembalikan:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


Mengambil nama sel data diagram. Read-only String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Keluaran: "B2"
> ```

**Mengembalikan:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Mengambil indeks berbasis nol dari baris di lembar kerja tempat sel berada. Read-only int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Keluaran: 1
> ```

**Mengembalikan:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Mengambil indeks berbasis nol dari kolom di lembar kerja tempat sel berada. Read-only int.

--------------------

> ```
> Example:
>  
> v
> ```

**Mengembalikan:**
int