---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
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
| [getValue()](#getValue--) | Mendapatkan nilai yang terdapat dalam sel Excel. |
| [getName()](#getName--) | Mendapatkan nama sel data diagram. |
| [getRow()](#getRow--) | Mendapatkan indeks berbasis nol dari baris di lembar kerja tempat sel berada. |
| [getColumn()](#getColumn--) | Mendapatkan indeks berbasis nol dari kolom di lembar kerja tempat sel berada. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Mendapatkan nilai yang terdapat dalam sel Excel. Baca-saja  Object .

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

Mendapatkan nama sel data diagram. Baca-saja String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Output: "B2"
> ```

**Mengembalikan:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```

Mendapatkan indeks berbasis nol dari baris di lembar kerja tempat sel berada. Baca-saja int.

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

Mendapatkan indeks berbasis nol dari kolom di lembar kerja tempat sel berada. Baca-saja int.

--------------------

> ```
> Example:
>  
> v
> ```

**Mengembalikan:**
int