---
title: ExcelDataCell
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili satu sel tunggal dalam buku kerja Excel.
type: docs
url: /id/com.aspose.slides/exceldatacell/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Mewakili satu sel tunggal dalam buku kerja Excel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getValue()](#getValue--) | Mendapatkan nilai yang terdapat dalam sel Excel. |
| [getName()](#getName--) | Mendapatkan nama sel data diagram. |
| [getRow()](#getRow--) | Mendapatkan indeks berbasis nol dari baris di lembar kerja tempat sel berada. |
| [getColumn()](#getColumn--) | Mendapatkan indeks berbasis nol dari kolom di lembar kerja tempat sel berada. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Mendapatkan nilai yang terdapat dalam sel Excel.

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
public final String getName()
```


Mendapatkan nama sel data diagram.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Hasil: "B2"
> ```


**Mengembalikan:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```


Mendapatkan indeks berbasis nol dari baris di lembar kerja tempat sel berada. Baca-saja int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Hasil: 1
> ```


**Mengembalikan:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


Mendapatkan indeks berbasis nol dari kolom di lembar kerja tempat sel berada. Baca-saja int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Hasil: 1
> ```


**Mengembalikan:**
int