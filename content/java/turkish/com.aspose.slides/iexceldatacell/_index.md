---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Represents a single cell in an Excel workbook.
type: docs
url: /tr/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Bir Excel çalışma kitabındaki tek bir hücreyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValue()](#getValue--) | Excel hücresinde bulunan değeri alır. |
| [getName()](#getName--) | Grafik veri hücresinin adını alır. |
| [getRow()](#getRow--) | Hücrenin bulunduğu çalışma sayfasındaki satırın sıfırdan başlayan dizinini alır. |
| [getColumn()](#getColumn--) | Hücrenin bulunduğu çalışma sayfasındaki sütunun sıfırdan başlayan dizinini alır. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Excel hücresinde bulunan değeri alır. Salt okunur  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Döndürür:**  
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```

Grafik veri hücresinin adını alır. Salt okunur String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Çıktı: "B2"
> ```


**Döndürür:**  
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```

Hücrenin bulunduğu çalışma sayfasındaki satırın sıfırdan başlayan dizinini alır. Salt okunur int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Çıktı: 1
> ```


**Döndürür:**  
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Hücrenin bulunduğu çalışma sayfasındaki sütunun sıfırdan başlayan dizinini alır. Salt okunur int.

--------------------

> ```
> Example:
>  
> v
> ```


**Döndürür:**  
int