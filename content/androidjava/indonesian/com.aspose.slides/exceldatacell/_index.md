---
title: ExcelDataCell
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili satu sel dalam buku kerja Excel.
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

Mewakili satu sel dalam buku kerja Excel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getValue()](#getValue--) | Mengambil nilai yang terdapat dalam sel Excel. |
| [getName()](#getName--) | Mengambil nama sel data diagram. |
| [getRow()](#getRow--) | Mengambil indeks berbasis nol baris di lembar kerja tempat sel berada. |
| [getColumn()](#getColumn--) | Mengambil indeks berbasis nol kolom di lembar kerja tempat sel berada. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Mengambil nilai yang terdapat dalam sel Excel.

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


Mengambil nama sel data diagram.

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
public final int getRow()
```


Mengambil indeks berbasis nol baris di lembar kerja tempat sel berada. Hanya-baca int.

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
public final int getColumn()
```


Mengambil indeks berbasis nol kolom di lembar kerja tempat sel berada. Hanya-baca int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Keluaran: 1
> ```


**Mengembalikan:**
int