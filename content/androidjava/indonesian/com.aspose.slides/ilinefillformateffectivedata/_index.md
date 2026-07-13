---
title: ILineFillFormatEffectiveData
second_title: Referensi API Java Aspose.Slides untuk Android
description: Objek tidak dapat diubah yang berisi properti pengisian garis yang efektif.
type: docs
url: /id/com.aspose.slides/ilinefillformateffectivedata/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

Objek tidak dapat diubah yang berisi properti pengisian baris yang efektif.

--------------------

Antarmuka ini digunakan sebagai bagian dari [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | Mengembalikan tipe pengisian. |
| [getSolidFillColor()](#getSolidFillColor--) | Mengembalikan warna pengisian solid. |
| [getGradientFormat()](#getGradientFormat--) | Mengembalikan format pengisian gradien. |
| [getPatternFormat()](#getPatternFormat--) | Mengembalikan format pengisian pola. |
| [getRotateWithShape()](#getRotateWithShape--) | Menentukan apakah pengisian harus diputar bersama bentuk. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Mengembalikan tipe pengisian. Hanya-baca [FillType](../../com.aspose.slides/filltype).

**Mengembalikan:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Mengembalikan warna pengisian solid. Hanya-baca java.lang.Integer.

**Mengembalikan:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Mengembalikan format pengisian gradien. Hanya-baca [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**Mengembalikan:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Mengembalikan format pengisian pola. Hanya-baca [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**Mengembalikan:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Menentukan apakah pengisian harus diputar bersama bentuk. Hanya-baca boolean.

**Mengembalikan:**
boolean