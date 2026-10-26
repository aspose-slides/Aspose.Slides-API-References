---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objek tak berubah yang berisi properti pengisian pola yang efektif.
type: docs
url: /id/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Objek tak berubah yang berisi properti pengisian pola yang efektif.

--------------------

Antarmuka ini digunakan sebagai bagian dari [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) dan [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Mengembalikan gaya pola. |
| [getForeColor()](#getForeColor--) | Mengembalikan warna pola latar depan. |
| [getBackColor()](#getBackColor--) | Mengembalikan warna pola latar belakang. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Mengembalikan gaya pola. Hanya-baca [PatternStyle](../../com.aspose.slides/patternstyle).

**Mengembalikan:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


Mengembalikan warna pola latar depan. Hanya-baca java.lang.Integer.

**Mengembalikan:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


Mengembalikan warna pola latar belakang. Hanya-baca java.lang.Integer.

**Mengembalikan:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| background | java.lang.Integer | java.lang.Integer latar belakang untuk pola. |
| foreground | java.lang.Integer | java.lang.Integer latar depan untuk pola. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Ubin [IImage](../../com.aspose.slides/iimage).