---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir Excel çalışma kitabındaki tek bir hücreyi temsil eder.
type: docs
url: /tr/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Bir Excel çalışma kitabındaki tek bir hücreyi temsil eder.
## Metotlar

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Excel hücresinde bulunan değeri alır. |
| [getName()](#getName--) | Grafik veri hücresinin adını alır. |
| [getRow()](#getRow--) | Hücrenin bulunduğu çalışma sayfasındaki satırın sıfır tabanlı indeksini alır. |
| [getColumn()](#getColumn--) | Hücrenin bulunduğu çalışma sayfasındaki sütunun sıfır tabanlı indeksini alır. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Excel hücresinde bulunan değeri alır. Yalnızca okuma Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
```

**Döndürür:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


Grafik veri hücresinin adını alır. Yalnızca okuma String.

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


Hücrenin bulunduğu çalışma sayfasındaki satırın sıfır tabanlı indeksini alır. Yalnızca okuma int.

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


Hücrenin bulunduğu çalışma sayfasındaki sütunun sıfır tabanlı indeksini alır. Yalnızca okuma int.

--------------------

> ```
> Example:
>  
> v
> ```

**Döndürür:**
int