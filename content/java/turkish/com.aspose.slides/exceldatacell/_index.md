---
title: ExcelDataCell
second_title: Aspose.Slides for Java API Referansı
description: Bir Excel çalışma kitabındaki tek bir hücreyi temsil eder.
type: docs
url: /tr/com.aspose.slides/exceldatacell/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Bir Excel çalışma kitabındaki tek bir hücreyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValue()](#getValue--) | Excel hücresinde bulunan değeri alır. |
| [getName()](#getName--) | Grafik veri hücresinin adını alır. |
| [getRow()](#getRow--) | Hücresinin bulunduğu çalışma sayfasındaki satırın sıfırdan başlayan dizinini alır. |
| [getColumn()](#getColumn--) | Hücresinin bulunduğu çalışma sayfasındaki sütunun sıfırdan başlayan dizinini alır. |
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

**Döndürür:**
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

**Döndürür:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

Hücresinin bulunduğu çalışma sayfasındaki satırın sıfırdan başlayan dizinini alır. Salt okunur int.

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
public final int getColumn()
```

Hücresinin bulunduğu çalışma sayfasındaki sütunun sıfırdan başlayan dizinini alır. Salt okunur int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Çıktı: 1
> ```

**Döndürür:**
int