---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
url: /id/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Mengizinkan membuat Portion uji

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createPortion()](#createPortion--) | Membuat Portion teks kosong. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Membuat Portion teks dari string yang ditentukan. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Membuat Portion dengan menggunakan data Portion yang ditentukan. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Membuat Portion teks kosong.

**Mengembalikan:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Membuat Portion teks dari string yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | java.lang.String | String. |

**Mengembalikan:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


Membuat Portion dengan menggunakan data Portion yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Sebuah Portion untuk digunakan. |

**Mengembalikan:**
[IPortion](../../com.aspose.slides/iportion) - Portion.