---
title: ExcelDataCell
second_title: Aspose.Slides for Android için Java API Referansı
description: Excel çalışma kitabında tek bir hücreyi temsil eder.
type: docs
url: /tr/com.aspose.slides/exceldatacell/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Excel çalışma kitabındaki tek bir hücreyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValue()](#getValue--) | Excel hücresinde bulunan değeri alır. |
| [getName()](#getName--) | Grafik veri hücresinin adını alır. |
| [getRow()](#getRow--) | Hücrenin bulunduğu çalışma sayfasındaki satırın sıfır tabanlı indeksini alır. |
| [getColumn()](#getColumn--) | Hücrenin bulunduğu çalışma sayfasındaki sütunun sıfır tabanlı indeksini alır. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Excel hücresinde bulunan değeri alır.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Dönüş:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```


Grafik veri hücresinin adını alır.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Çıktı: "B2"
> ```

**Dönüş:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```


Hücrenin bulunduğu çalışma sayfasındaki satırın sıfır tabanlı indeksini alır. Yalnızca okunabilir int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Çıktı: 1
> ```

**Dönüş:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


Hücrenin bulunduğu çalışma sayfasındaki sütunun sıfır tabanlı indeksini alır. Yalnızca okunabilir int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Çıktı: 1
> ```


**Dönüş:**
int