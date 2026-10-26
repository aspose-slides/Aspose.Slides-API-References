---
title: IMasterTheme
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili tema master.
type: docs
url: /id/com.aspose.slides/imastertheme/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Mewakili tema master.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Mengembalikan koleksi skema warna tambahan. |
| [getName()](#getName--) | Mengembalikan nama tema. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan nama tema. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Mengembalikan koleksi skema warna tambahan. Skema ini tidak memengaruhi tampilan presentasi, mereka dapat dipilih sebagai skema warna utama untuk sebuah slide. Hanya-baca [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Mengembalikan:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Mengembalikan nama tema. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Mengembalikan nama tema. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |